# Ateliê Doce Encanto — site

Site institucional de página única do **Ateliê Doce Encanto by Amanda Medeiros**, ateliê de
peças artesanais em feltro para festas infantis (Jaboatão dos Guararapes — PE).

Site estático: HTML e CSS puros, sem build, sem dependências e sem framework.

---

## Estrutura

```
.
├── index.html                        página única do site
├── css/estilo.css                    estilos, cores e tipografia da marca
├── assets/                           logos, símbolo, favicon e imagem social (kit da marca)
├── fotos/                            fotos das peças (33 imagens otimizadas)
│   ├── thumbs/                       miniaturas usadas na galeria
│   └── LEIA-ME.md                    como acrescentar ou trocar fotos
├── docs_guia_identidade_visual.md    guia de identidade visual original da marca
├── .github/workflows/deploy.yml      publicação automática no GitHub Pages
├── .nojekyll                         evita que o Pages ignore arquivos
└── robots.txt
```

## Fotos das peças

As 33 fotos das peças já estão em `fotos/` (otimizadas, máx. 1200 px) e as miniaturas da
galeria em `fotos/thumbs/` (máx. 620 px). Para acrescentar ou trocar fotos, veja
[`fotos/LEIA-ME.md`](fotos/LEIA-ME.md).

Se um arquivo referenciado não existir, o site mostra um espaço pontilhado no lugar,
sem quebrar o layout.

## Publicar no GitHub Pages

1. Crie um repositório vazio no GitHub (por exemplo, `atelie-doce-encanto`), **sem** README.
2. Na pasta do projeto, rode:

```bash
git remote add origin https://github.com/SEU-USUARIO/atelie-doce-encanto.git
git branch -M main
git push -u origin main
```

3. No GitHub, vá em **Settings → Pages** e, em *Source*, escolha **GitHub Actions**.
4. O workflow publica sozinho a cada `git push`. O endereço final fica:
   `https://SEU-USUARIO.github.io/atelie-doce-encanto/`

> Alternativa sem Actions: em **Settings → Pages**, escolha *Deploy from a branch*,
> branch `main` e pasta `/ (root)`.

### Domínio próprio

Ao registrar um domínio (ex.: `ateliedoceencanto.com.br`), aponte o DNS para o GitHub Pages
e informe o domínio em **Settings → Pages → Custom domain**. O GitHub cria o arquivo `CNAME`
no repositório automaticamente.

## Alterar textos e contatos

Todos os dados de contato estão no `index.html` e podem ser trocados com busca e substituição:

| Procurar por          | Onde aparece                                  |
|-----------------------|-----------------------------------------------|
| `5581998027618`       | links do WhatsApp (formato internacional)     |
| `(81) 99802-7618`     | telefone exibido na tela                      |
| `ateliedoce2413`      | links do Instagram                            |
| `medeirosamanda1720@` | e-mail de contato                             |

Os depoimentos estão marcados no HTML com o comentário `SUBSTITUIR` e devem ser trocados
por comentários reais de clientes, com autorização.

## Identidade visual

Cores e tipografia seguem o guia da marca:

| Cor      | Código    | Uso                                  |
|----------|-----------|--------------------------------------|
| Rosa     | `#E95F78` | botões, links e destaques            |
| Carvão   | `#2B2B2B` | textos e rodapé                      |
| Creme    | `#FFF8F5` | fundos de seção                      |
| Blush    | `#FBE8EC` | detalhes e selos                     |
| Grafite  | `#5A5557` | textos secundários                   |

Tipografia: **Bodoni Moda** nos títulos e **Montserrat** no texto corrido, carregadas do
Google Fonts.

## Testar localmente

Basta abrir o `index.html` no navegador. Para simular o ambiente de produção:

```bash
python3 -m http.server 8000
# acesse http://localhost:8000
```
