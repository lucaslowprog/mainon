# Creatina Integralmédica — vídeo com motion

## Entrega

- `Central_Creatina_Motion_1080x1920_30fps.mp4`: versão para redes, vertical 9:16, 8 segundos, H.264/AAC, BT.709.
- `Central_Creatina_Motion_2160x3840_60fps.mp4`: máster vertical, 8 segundos.
- Sem brinde ou prazo incorporados. Oferta: Creatina Hardcore Integralmédica 500 g por R$ 89,90.

## Origem e limites

`IMG_0174_ORIGINAL.MOV` é uma cópia sem alteração do arquivo fornecido pelo usuário: 464 × 848, H.264, 30 fps, áudio AAC, duração 2,833333 segundos. O vídeo é comprimido e foi ampliado: a entrega 2160 × 3840 não é captação nativa 4K. O fundo a 60 fps repete quadros da montagem de 30 fps; não há interpolação para fabricar detalhe nem alegação de câmera nativa 60 fps. O motion e as letras são renderizados nativamente em cada resolução final.

## Montagem

Três repetições do vídeo em velocidade original, com dissoluções de aproximadamente 0,25 segundo nas junções, para completar 8 segundos. Não foi aplicado slow motion. Áudio original preservado com crossfades de 0,25 segundo, fade curto no início e no fim; nenhuma trilha musical foi adicionada.

Reenquadramento para cima preserva a marca e o nome principal do pote na região de protagonismo. O contraste inferior vem de um documento SVG com gradiente contínuo, não de reconstrução da embalagem. O topo não recebe assinatura de marca, localização ou slogan.

## Motion e texto

- 0,08–0,63 s: “BLACK FRIDAY” entra lateralmente.
- 0,35–0,95 s: “CREATINA HARDCORE” sobe com ajuste de escala.
- A partir de 0,75 s: “INTEGRALMÉDICA • 500 g”.
- 0,90–1,40 s: linha vermelha entra lateralmente.
- 1,15–1,80 s: “R$ 89,90” muda posição e escala, com breve acomodação.
- A partir de 1,60 s: “Aproveite a oferta na Central Suplementos.”
- 1,90–2,55 s: botão e “Chame no WhatsApp” entram pela lateral. Permanecem estáveis até 8 segundos.
- A partir de 2,25 s: “Consulte disponibilidade e condições.”

Escala tipográfica revisada e aprovada: BLACK FRIDAY ocupa aproximadamente 77% da largura total, CREATINA HARDCORE 82% e preço 73%, com Inter e CTA ampliados. Não é a primeira versão com texto pequeno.

O botão é gráfico. Ao publicar no Instagram, adicionar e testar o link oficial **https://wa.me/5531999461445**. Caso seja usado texto pré-preenchido no link, referir-se à **creatina**, não ao whey. Nenhuma publicação foi realizada pelo subagente.

## Fontes editáveis e reprodução

`motion_1080x1920.ass` e `motion_2160x3840.ass` preservam textos, posições, timings e animações. `contraste_*.svg` preservam o gradiente vetorial; os PNGs correspondentes são derivados técnicos. `render_video.py` gera a base, as legendas animadas e os MP4s. `filtro_*.txt` registra os filtros aplicados; `render_*.log` registra a execução.

Fontes oficiais: **BarlowCondensed-Black.ttf, peso OS/2 900**, e **Inter-Bold.ttf, peso OS/2 700**. Os logs de libass devem apontar para BarlowCondensed-Black e Inter-Bold, sem fallback. Cópias das fontes e licenças estão na pasta local `FONTES/`; originais preservados em `../fontes-oficiais/`.

Reproduzir no projeto com Python e fontTools, FFmpeg com libass/libx264 e Inkscape instalados:

```bash
python render_video.py 1
python render_video.py 2
```

Não alterar o texto da oferta sem nova orientação. Arquivos são entregues localmente para o agente principal revisar e disponibilizar no GitHub.
