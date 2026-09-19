# Fotos e vídeos da documentação

A documentação do Heimdall vem dentro do app (a aba **Documentação**,
`Ctrl+Shift+H`). Os textos são do app; as fotos (`.png`) e os vídeos (`.webm`)
ficam aqui e são carregados por HTTP, para o instalador não crescer.

O app lê cada arquivo pelo nome, em
`https://raw.githubusercontent.com/dlduarte/heimdall-releases/main/docs/<nome>`.
Renomear ou apagar um arquivo quebra a imagem nas versões que o citam.

Os arquivos são gravados com `tools/docs-media/` do repositório principal,
num ambiente de demonstração: nenhum servidor ou dado real aparece neles.
