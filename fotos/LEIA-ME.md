# Fotos do site

As fotos das peças já estão nesta pasta, otimizadas para a web (máx. 1200 px de largura).
A pasta `thumbs/` guarda as miniaturas usadas na galeria — cada foto precisa existir nos
**dois** lugares, com o mesmo nome.

## Adicionar uma foto nova

1. Salve a foto em `fotos/` com nome em minúsculas, sem acento e sem espaço.
   Exemplo: `princesa-elsa-em-feltro.jpg`
2. Salve uma versão menor (máx. 620 px) com o **mesmo nome** em `fotos/thumbs/`.
3. Em `index.html`, procure a seção `<!-- GALERIA -->` e copie um bloco `<button class="g-item">`,
   trocando o nome do arquivo e a legenda.

## Trocar a foto de um card ou do destaque

Basta editar o `src` da imagem correspondente no `index.html`. Se o arquivo não existir,
o site mostra automaticamente um espaço pontilhado no lugar — nada quebra.

## Dicas de fotografia

- Fundo liso e claro, luz natural, sem flash.
- Peça levemente inclinada, não totalmente de frente.
- Uma foto com a peça na mão ajuda a mostrar o tamanho real.
- Antes de subir, reduza a imagem para no máximo 1200 px e 200 KB.

## Observação sobre pessoas nas fotos

Fotos que mostrem o rosto de crianças não foram publicadas. Para usar qualquer imagem
com uma criança identificável, é preciso autorização por escrito dos responsáveis.
