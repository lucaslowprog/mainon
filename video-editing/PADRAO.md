# Padrão de edição da comporta-se

Aplicar por padrão aos novos vídeos enviados neste projeto. Pedidos específicos do usuário prevalecem. Referência de formato: `../outputs/video-comporta-se-legenda-interativa.mp4`. Configuração estruturada: `padrao.json`.

## Legendas e ritmo

Legendas em português, caixa alta, até quatro palavras por grupo e duas linhas. Fonte Comporta Caption (DM Sans Black), texto branco com contorno grafite. Destacar a palavra falada com fundo lilás; palavras importantes com sol suave. Posicionar abaixo do rosto, na região central. Usar entrada suave e destaque sincronizado por palavra. Ajustar todas as medidas proporcionalmente à resolução e conferir em tamanho de celular.

Transcrever cada novo vídeo e revisar nomes, termos e trechos incertos. Criar os tempos a partir do áudio do novo material. Fazer cortes leves em pausas, com margem para respiração, e remontar os tempos depois dos cortes. Preservar frases, voz, intenção e ordem das ideias. Não acelerar a fala por padrão.

## Efeitos visuais

Usar poucos grafismos vinculados ao que foi realmente dito. Em aproximadamente 35 segundos, começar com até três entradas, uma por vez: por exemplo, bicicleta quando mencionar pedalar, árvore ao falar de plantar e violão quando mencionar música. Adaptar os ícones aos assuntos de cada vídeo; não repetir automaticamente esses objetos.

Não colocar caixas de informações, rótulos extras ou diagramas em todos os momentos. A legenda é o elemento principal. Manter espaço em volta do rosto e do texto. Usar o logo no alto à esquerda. Encerrar com até três segundos nas cores da marca e uma pergunta curta ligada ao assunto.

## Áudio

Manter a voz em primeiro plano, com trilha instrumental suave e redução de volume enquanto a pessoa fala. Usar trilhas originais ou com licença adequada. Sons curtos e discretos apenas em entradas importantes; evitar som por palavra. Referência técnica de mixagem: aproximadamente -17 LUFS, pico verdadeiro no máximo -1,5 dBTP. Verificar o resultado, sem sacrificar a inteligibilidade para atingir números.

## Produção e entrega

Exportar MP4 H.264/AAC com faststart e 30 fps, preservando o detalhe do original. Não ampliar alegando ganho de resolução. Conferir o arquivo completo, a sincronia da fala com os destaques, a ausência de sobreposição e os níveis de áudio. Publicar apenas a versão final em `outputs/` deste repositório e fornecer o link de download do GitHub. Preservar as versões anteriores. Não publicar o vídeo original, referências ou documentos de marca sem solicitação.

Os helpers em `/workspace/outputs/` registram edições anteriores e contêm caminhos e tempos específicos. Não executá-los como se fossem um editor genérico. Adaptar o processamento e validar para cada novo vídeo. Este padrão não é um monitor automático de uploads nem altera outros chats.
