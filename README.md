# Playverse

A **Playverse** é uma loja fictícia de jogos desenvolvida como projeto avaliativo da disciplina de Desenvolvimento Web.

O projeto tem como objetivo aplicar conceitos de **HTML e CSS**, incluindo Flexbox, CSS Grid, responsividade, animações, pseudo-classes, pseudo-elementos, backgrounds e outros recursos estudados durante a disciplina.

## Como executar

1. Clone ou baixe este repositório.
2. Abra a pasta do projeto.
3. Instale as dependências:

```bash
npm install
```

4. Execute o projeto utilizando o Vite:

```bash
npm run dev
```

5. Abra no navegador o endereço informado pelo Vite.

## Integrantes

* Arthur Souza de Carvalho

## Tema

**Loja de jogos online**

O site simula uma plataforma de venda de jogos, apresentando jogo em destaque, catálogo de jogos, página de login e página com informações sobre o projeto.

## Páginas

* `index.html` — Página principal e catálogo de jogos.
* `about.html` — Informações sobre a Playverse e sobre a atividade.
* `login.html` — Página de login.

# Checklist da atividade

* [x] **Flexbox**
  `src/style.css` — `.navbar`, `.menus ul`, `.hero`, `.main-content` e `.about-hero`.

* [x] **CSS Grid**
  `src/style.css` — `.galeria-grid` e `.about-grid`.

* [x] **Media Queries / Responsividade**
  `src/style.css` — `@media screen and (max-width: 800px)` e `@media (max-width: 768px)`.

* [x] **Media Queries (condições/recursos)**
  `src/style.css` — `@media screen and (orientation: landscape) and (max-width: 900px)`, utilizado para alterar a altura da seção `.hero` quando o dispositivo está na orientação horizontal.

* [x] **CSS Variables**
  `src/style.css` — `:root`, com as variáveis `--primary-color`, `--secondary-color` e `--test-color`.

* [x] **Image Modal**
  `index.html` — modais utilizados para ampliar as capas dos jogos.
  `src/style.css` — `.image-modal`, `.image-modal:target`, `.image-modal img` e `.modal-close`.

* [x] **Animations / @keyframes**
  `src/style.css` — `.about-animation` / `.game-icon` e `@keyframes flutuar`, utilizados para criar a animação do ícone na página Sobre.

* [x] **Backgrounds**
  `src/style.css` — `.hero` utiliza `linear-gradient()` junto com `url()`. `.main-content::before` utiliza `background-image`, `background-size` e `background-position`.

* [x] **CSS Units**
  `src/style.css` — uso de `%`, `rem`, `vh` e `px` em diferentes elementos do layout.

* [x] **Pseudo-elements**
  `src/style.css` — `.main-content::before` e `.main-content::after`, utilizados para criar a imagem de fundo com blur e uma camada escura sobre ela.

* [x] **Pseudo-classes**
  `src/style.css` — `.btn-comprar:hover`, `.card-jogo:hover`, `.btn-card:hover`, `.menus li a:hover`, `.login input:focus` e `.image-modal:target`.

* [x] **Float**
  `about.html` / `src/style.css` — `.about-float-img` utiliza `float: left` para posicionar a imagem à esquerda e permitir que o texto fique ao seu redor.

* [x] **Position + z-index**
  `src/style.css` — `.main-content` utiliza `position: relative`; `.main-content::before` e `.main-content::after` utilizam `position: absolute` e `z-index`; `.login` utiliza `z-index`; o modal de imagens utiliza `position: fixed` e `z-index`.

## Uso de IA generativa

Durante o desenvolvimento do projeto, ferramentas de IA generativa foram utilizadas como apoio para estudo e desenvolvimento.

A IA foi utilizada para auxiliar na compreensão de propriedades CSS, identificação e correção de problemas no código e sugestões para implementação de alguns dos requisitos da atividade.

Todo código utilizado no projeto foi revisado e adaptado de acordo com as necessidades do site.
