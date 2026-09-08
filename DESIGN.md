# Forja Stand — direção visual

## Direção
Vitrine de colecionáveis com composição assimétrica. CTA e QR permanecem fixos à esquerda; dois vídeos reais do Instagram dominam o campo direito, com legendas e links. Uma faixa independente de fotografias MakerWorld fica abaixo.

## Contrato
- THESIS: converter a atenção despertada pelos objetos em uma visita ao Instagram.
- OWN-WORLD: a marca de bigorna da Forja e suas fotografias reais são os elementos de identidade.
- STORY: ver os objetos, reconhecer a Forja, escanear o QR.
- FIRST VIEWPORT: em 1920 × 1080, uma superfície inteira sem rolagem, logo, Siga a Forja, QR grande, dois vídeos verticais em reprodução e quatro fotografias do MakerWorld abaixo.
- FORM: carvão #171918, papel #f3ede3, bronze #d9aa71, tipografia Ubuntu, bordas discretas. O fundo escuro mantém a identidade de stand estável independentemente do tema do computador.

## Tipografia e espaçamento
Ubuntu regular e bold incorporadas. Headline até 96 px, metadados a partir de 11 px. Margens fluidas e hierarquia adaptada à altura disponível.

## Motion
Fila de quatro reels: livro-caixa, dragõezinhos e ovos, plaquinhas para colorir, porta-lápis dragão. Ambos os vídeos reproduzem simultaneamente, sem faixa de áudio. O término do primeiro dispara deslocamento de 650 ms à esquerda. O segundo mantém nó DOM e currentTime. Se acabar à direita antes da promoção, reinicia enquanto aguarda. A faixa MakerWorld mostra quatro fotos e muda a cada 8 segundos, embaralhando após a rodada. Pausa manual e aba oculta suspendem a reprodução; movimento reduzido inicia pausado e desativa deslocamentos.

## Adaptação
Desktop em duas colunas. Em celular, identidade e QR ficam lado a lado acima da galeria. Em paisagem baixa, as miniaturas são ocultadas para preservar a imagem e o QR. Vídeos usam contain para preservar o enquadramento original; o espaço lateral recebe o próprio poster desfocado, sem cortar o vídeo.

## Limitações do conteúdo
Os quatro vídeos do Instagram foram obtidos da página pública renderizada. Fontes MP4 originais preservadas em scratch; versões de exibição H.264 de até 960 px de altura, sem áudio. Textos já presentes nos vídeos permanecem como na fonte. A coleção MakerWorld também tem etiquetas e marcas originais, preservadas nas imagens.
