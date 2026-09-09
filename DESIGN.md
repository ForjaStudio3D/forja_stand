# Forja Stand — direção visual

## Direção
Vitrine de colecionáveis com composição centrada. Logo, CTA e QR permanecem no eixo central; dois vídeos reais do Instagram de cada lado, com legendas e links, enquadram o convite. Uma faixa independente de fotografias MakerWorld fica abaixo.

## Contrato
- THESIS: converter a atenção despertada pelos objetos em uma visita ao Instagram.
- OWN-WORLD: a marca de bigorna da Forja e suas fotografias reais são os elementos de identidade.
- STORY: ver os objetos, reconhecer a Forja, escanear o QR.
- FIRST VIEWPORT: em 1920 × 1080, uma superfície inteira sem rolagem, logo central, Siga a Forja, QR de 360 px no centro, quatro vídeos verticais em reprodução e seis fotografias do MakerWorld abaixo.
- FORM: carvão #171918, papel #f3ede3, bronze #d9aa71, tipografia Ubuntu, bordas discretas. O fundo escuro mantém a identidade de stand estável independentemente do tema do computador.

## Tipografia e espaçamento
Ubuntu regular e bold incorporadas. Headline até 76 px. Margens fluidas e hierarquia adaptada à altura disponível; QR de 250 px em notebook 1366 × 768.

## Motion
Fila de quatro reels: livro-caixa, dragõezinhos e ovos, plaquinhas para colorir, porta-lápis dragão. Todos reproduzem simultaneamente, sem faixa de áudio. O término do primeiro dispara saída de 180 ms à esquerda e deslocamento de 650 ms. Os outros três mantêm nós DOM e currentTime; o vídeo concluído reinicia na última posição. Um vídeo que termina antes de chegar à primeira posição reinicia enquanto aguarda. Os pares recortam o movimento para preservar o centro fixo. A faixa MakerWorld mostra seis fotos e muda a cada 8 segundos, embaralhando após a rodada. Pausa manual e aba oculta suspendem a reprodução; movimento reduzido inicia pausado e desativa deslocamentos.

## Adaptação
Desktop/notebook com dois vídeos de cada lado do centro. Em celular, cada par empilha seus dois vídeos, mantendo o QR central, e a faixa inferior mostra quatro fotos. Em paisagem baixa, as miniaturas são ocultadas para preservar vídeos e QR. Vídeos usam contain para preservar o enquadramento original; o espaço livre recebe o próprio poster desfocado, sem cortar o vídeo.

As referências MakerWorld usam imagens inteiras com contain em áreas quadradas. Em desktop/notebook, nomes e créditos ficam ao lado, sem sobrepor a fotografia; em celular, o nome fica abaixo.

## Limitações do conteúdo
Os quatro vídeos do Instagram foram obtidos da página pública renderizada. Fontes MP4 originais preservadas em scratch; versões de exibição H.264 de até 960 px de altura, sem áudio. Textos já presentes nos vídeos permanecem como na fonte. A coleção MakerWorld também tem etiquetas e marcas originais, preservadas nas imagens.
