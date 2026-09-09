# Forja Stand — direção visual

## Direção
Vitrine de colecionáveis com duas composições aprovadas. Na lateral, logo, CTA e QR à esquerda acompanham dois vídeos grandes à direita. No centro, logo, CTA e QR ocupam o eixo central com dois vídeos de cada lado. A faixa independente MakerWorld acompanha a reorganização e mantém as imagens inteiras.

## Contrato
- THESIS: converter a atenção despertada pelos objetos em uma visita ao Instagram.
- OWN-WORLD: a marca de bigorna da Forja e suas fotografias reais são os elementos de identidade.
- STORY: ver os objetos, reconhecer a Forja, escanear o QR.
- FIRST VIEWPORT: em 1920 × 1080, uma superfície inteira sem rolagem, identidade e QR lateral, dois vídeos grandes e quatro referências MakerWorld. Após 120 segundos, QR de 360 px no centro, quatro vídeos e seis referências MakerWorld por 30 segundos.
- FORM: carvão #171918, papel #f3ede3, bronze #d9aa71, tipografia Ubuntu, bordas discretas. O fundo escuro mantém a identidade de stand estável independentemente do tema do computador.

## Tipografia e espaçamento
Ubuntu regular e bold incorporadas. Headline até 96 px na lateral e 76 px no centro. Margens fluidas e hierarquia adaptada à altura disponível; QR central de 250 px em notebook 1366 × 768.

## Motion

O momento principal é a migração da identidade entre as duas composições. Metadados saem em 160 ms; elementos compartilhados reorganizam-se por FLIP/WAAPI em 900 ms com cubic-bezier(.65,0,.15,1). Um plano carvão mantém a identidade legível enquanto os vídeos passam atrás. Vídeos adicionais e metadados entram no fim da viagem. A contrascala dos vídeos é calculada em 32 passos para manter a proporção dos retratos durante o movimento. Não há reinício de vídeo durante a troca de layout.

Cada permanência começa após o movimento terminar: 120 segundos na lateral e 30 segundos no centro. Pausa e aba oculta congelam o relógio e a reprodução; retomada usa o tempo restante. O botão Layout permite troca manual; L troca sem animação. Redução de movimento inicia a página pausada e troca as composições sem deslocamento. Trocas de composição e da fila de vídeos são serializadas.

Fila de quatro reels: livro-caixa, dragõezinhos e ovos, plaquinhas para colorir, porta-lápis dragão. No centro, todos reproduzem simultaneamente; na lateral, os dois ocultos ficam pausados. Todos permanecem sem faixa de áudio. O término do primeiro dispara saída de 180 ms à esquerda e deslocamento de 650 ms. Os outros três mantêm nós DOM e currentTime; o vídeo concluído reinicia na última posição. Um vídeo visível que termina antes de chegar à primeira posição reinicia enquanto aguarda. Os pares recortam o movimento para preservar o centro fixo. A faixa MakerWorld muda a cada 8 segundos, com quatro fotos na lateral e seis no centro, embaralhando após a rodada.

## Adaptação
Desktop/notebook alterna entre dois vídeos à direita da identidade lateral e dois vídeos de cada lado do centro. Em celular, o modo lateral coloca identidade/QR acima de dois vídeos; o modo central empilha cada par ao lado do QR. Em paisagem baixa, as miniaturas são ocultadas para preservar vídeos e QR. Vídeos usam contain para preservar o enquadramento original; o espaço livre recebe o próprio poster desfocado, sem cortar o vídeo.

As referências MakerWorld usam imagens inteiras com contain em áreas quadradas. Em desktop/notebook, nomes e créditos ficam ao lado, sem sobrepor a fotografia; em celular, o nome fica abaixo.

## Limitações do conteúdo
Os quatro vídeos do Instagram foram obtidos da página pública renderizada. Fontes MP4 originais preservadas em scratch; versões de exibição H.264 de até 960 px de altura, sem áudio. Textos já presentes nos vídeos permanecem como na fonte. A coleção MakerWorld também tem etiquetas e marcas originais, preservadas nas imagens.
