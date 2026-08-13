# Guia de identidade visual para o site

## Ateliê Doce Encanto by Amanda Medeiros

Este pacote é uma curadoria dos elementos vetoriais mais úteis para o site. Os nomes dos arquivos descrevem **conteúdo**, **formato** e **fundo**, permitindo que designers e desenvolvedores escolham o ativo correto sem precisar abri-lo primeiro.

> Convenção adotada: o nome oficial da marca é **Doce Encanto**. Por isso, os arquivos usam `doce_encanto`, e não `recanto`.

## Escolha rápida

- Cabeçalho em fundo claro: `logo_principal_completo_horizontal_fundo_transparente.svg`
- Cabeçalho em fundo branco garantido: `logo_principal_completo_horizontal_fundo_branco.svg`
- Rodapé carvão: `logo_negativo_completo_horizontal_fundo_carvao.svg`
- Menu mobile, avatar ou selo: `logo_principal_completo_circular_fundo_transparente.svg`
- Botões, detalhes e divisores: `simbolo_agulha_fio_coracao_fundo_transparente.svg`
- Favicon e ícone de aplicativo: `icone_favicon_agulha_fio_coracao_fundo_creme.svg`
- Compartilhamento em WhatsApp, Instagram e buscadores: `imagem_compartilhamento_social_logo_horizontal_fundo_creme.svg` ou o PNG correspondente em `previews_png/`.

## Inventário dos arquivos vetoriais

| Arquivo | O que contém | Uso recomendado | Fundo | Proporção |
|---|---|---|---|---|
| `logo_principal_completo_horizontal_fundo_transparente.svg` | Agulha, fio-coração e nome completo em rosa e carvão. | Cabeçalho, barra de navegação e áreas horizontais claras. | Transparente; aplicar sobre branco, creme ou blush muito claro. | 5:2 |
| `logo_principal_completo_horizontal_fundo_branco.svg` | Assinatura horizontal completa com fundo branco incorporado. | Integrações que não preservam transparência e blocos brancos. | Branco incorporado. | 5:2 |
| `logo_principal_completo_circular_fundo_transparente.svg` | Selo circular completo com agulha, fio-coração e nome. | Menu mobile, avatar, selo de qualidade e áreas quadradas. | Transparente; aplicar sobre fundo claro. | 1:1 |
| `logo_principal_completo_circular_fundo_branco.svg` | Selo circular completo com fundo branco incorporado. | Cards, widgets e plataformas que removem transparência. | Branco incorporado. | 1:1 |
| `logo_negativo_completo_horizontal_fundo_carvao.svg` | Assinatura horizontal em branco e rosa sobre carvão. | Rodapé, faixa escura e seção institucional noturna. | Carvão incorporado. | 5:2 |
| `logo_negativo_completo_circular_fundo_carvao.svg` | Selo circular em branco e rosa sobre carvão. | Avatar escuro, selos e destaques de alto contraste. | Carvão incorporado. | 1:1 |
| `logo_monocromatico_horizontal_carvao_fundo_transparente.svg` | Assinatura completa em uma única cor carvão. | Interfaces discretas, impressão simples, marca d'água e estados neutros. | Transparente; usar sobre fundo muito claro. | 5:2 |
| `simbolo_agulha_fio_coracao_fundo_transparente.svg` | Símbolo isolado: agulha, fio rosa em coração, pontos e coração final. | Detalhes decorativos, abertura de seções, carregamento e selo sem texto. | Transparente; preferir fundos claros. | 1:1 |
| `simbolo_agulha_fio_coracao_monocromatico_fundo_transparente.svg` | Símbolo isolado inteiramente em carvão. | Estados neutros, marca d'água e aplicações de uma cor. | Transparente; usar sobre fundo claro. | 1:1 |
| `icone_favicon_agulha_fio_coracao_fundo_creme.svg` | Ícone compacto com agulha, fio-coração, aro rosa e cantos arredondados. | Favicon, atalho do celular, PWA e marcador do navegador. | Creme incorporado. | 1:1 |
| `imagem_compartilhamento_social_logo_horizontal_fundo_creme.svg` | Cartão social com assinatura horizontal e fundo creme. | Open Graph, compartilhamento em WhatsApp, Instagram, Facebook e buscadores. | Creme incorporado. | 1200:630 |

## Estrutura recomendada do site

### 1. Cabeçalho

- Use a assinatura horizontal em fundo branco ou creme.
- Altura visual sugerida do logo: **56 a 72 px no desktop** e **38 a 48 px no celular**.
- Mantenha o menu curto: `Início`, `Produtos`, `Sobre`, `Encomendas` e `Contato`.
- Botão principal: **Fazer encomenda** ou **Chamar no WhatsApp**.

### 2. Seção principal

- Mostre uma fotografia forte do trabalho artesanal, com espaço livre para o texto.
- Título sugerido: **Encantos feitos à mão para momentos especiais.**
- Texto curto, com um único botão de ação.
- Evite colocar o logo completo novamente em tamanho grande; o cabeçalho já cumpre essa função.

### 3. Produtos ou serviços

- Organize por categorias e use fotografias reais, consistentes e bem iluminadas.
- Cada cartão deve conter nome, descrição curta, faixa de preço ou indicação “sob consulta” e ação clara.
- Para peças personalizadas, informe prazo médio, materiais e etapas da encomenda.

### 4. Sobre Amanda e o ateliê

- Combine uma fotografia autoral com uma história breve.
- Reforce cuidado manual, personalização, acabamento e propósito afetivo.
- Use o símbolo isolado como detalhe decorativo, sem repeti-lo em excesso.

### 5. Prova social

- Inclua depoimentos, fotos de clientes autorizadas e links para o Instagram.
- Evite carrosséis rápidos; priorize leitura confortável e controles acessíveis.

### 6. Contato e rodapé

- WhatsApp deve ser o contato principal quando esse for o canal de vendas.
- Inclua Instagram, cidade/região atendida, horário de resposta e política de encomendas.
- No rodapé carvão, use `logo_negativo_completo_horizontal_fundo_carvao.svg`.

## Direção visual principal

### Cores

```css
:root {
  --cor-rosa-encanto: #E95F78;
  --cor-carvao-elegante: #2B2B2B;
  --cor-branco: #FFFFFF;
  --cor-creme: #FFF8F5;
  --cor-blush: #FBE8EC;
  --cor-grafite: #5A5557;
}
```

- Fundo dominante: branco ou creme.
- Rosa: ações, detalhes, links ativos e pequenos destaques.
- Carvão: textos, rodapé e elementos de alto contraste.
- Não use rosa claro para textos longos; o contraste é insuficiente em tamanhos pequenos.

### Tipografia

- Títulos: **Bodoni Moda**; alternativas: Libre Bodoni ou Playfair Display.
- Textos e interface: **Montserrat**; alternativas: Avenir, Raleway, Poppins ou Aptos.
- Use no máximo duas famílias e mantenha o texto corrido com pelo menos **16 px**.

Sugestão de carregamento:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bodoni+Moda:opsz,wght@6..96,400;6..96,500&family=Montserrat:wght@400;500;600&display=swap" rel="stylesheet">
```

## Como inserir os SVGs

Para logotipos comuns:

```html
<img
  src="/assets/logo_principal_completo_horizontal_fundo_transparente.svg"
  alt="Ateliê Doce Encanto by Amanda Medeiros"
  width="450"
  height="180"
>
```

Para o símbolo decorativo, use `alt=""` quando ele não adicionar informação:

```html
<img
  src="/assets/simbolo_agulha_fio_coracao_fundo_transparente.svg"
  alt=""
  aria-hidden="true"
  width="96"
  height="96"
>
```

## Responsividade e desempenho

- Prefira SVG para logos e ícones: são nítidos em qualquer resolução.
- Declare `width` e `height` para evitar movimentação do layout durante o carregamento.
- Não aplique `filter`, sombra, contorno ou recoloração automática nos logos.
- Reserve imagens fotográficas em AVIF/WebP; os vetores deste pacote não precisam ser convertidos.
- Use carregamento tardio em fotografias abaixo da primeira tela, mas não no logo do cabeçalho.
- A imagem social deve ser exportada em **1200 × 630 px** quando a plataforma exigir raster.

## Acessibilidade

- Contraste mínimo recomendado: **4,5:1** para texto normal e **3:1** para texto grande.
- Botões devem ter área clicável mínima de aproximadamente **44 × 44 px**.
- Todo controle precisa funcionar por teclado e exibir foco visível.
- Use texto alternativo descritivo em fotos de produtos; em elementos apenas decorativos, use `alt=""`.
- Não substitua títulos ou informações importantes por texto dentro de imagens.

## SEO e conversão

- Título da página inicial: `Ateliê Doce Encanto | Peças artesanais por Amanda Medeiros`.
- Descrição sugerida: `Peças artesanais personalizadas, feitas com cuidado por Amanda Medeiros. Conheça o Ateliê Doce Encanto e solicite sua encomenda.`
- Crie uma página individual ou seção detalhada para cada categoria importante.
- Mantenha botão de WhatsApp visível, mas sem bloquear conteúdo no celular.
- Instale medição de cliques em WhatsApp, envio de formulário e visualização de produtos.

## Regras que não devem ser quebradas

1. Não distorcer ou mudar a proporção do logo.
2. Não alterar rosa, carvão ou branco fora das versões fornecidas.
3. Não reorganizar agulha, fio, coração ou textos.
4. Não aplicar o logo sobre fotografia sem contraste e área de respiro.
5. Não usar a assinatura horizontal com largura inferior a **240 px**.
6. Para tamanhos menores, usar o favicon ou o símbolo isolado.

## Checklist de entrega do site

- [ ] Logo correto no cabeçalho e no rodapé.
- [ ] Favicon configurado em 32, 192 e 512 px quando necessário.
- [ ] Imagem de compartilhamento 1200 × 630 px configurada.
- [ ] Menu e botões testados no celular.
- [ ] Contraste e navegação por teclado verificados.
- [ ] WhatsApp, Instagram e formulário funcionando.
- [ ] Fotografias otimizadas sem perder qualidade.
- [ ] Títulos, descrição e dados sociais configurados.
