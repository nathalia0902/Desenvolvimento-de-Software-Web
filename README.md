# Site Estático (HTML + CSS)

> Projeto: **Desenvolvimento de Software Web** — um site estático criado apenas com HTML e CSS.
---

## Descrição

Este repositório contém um site estático (apenas **HTML** e **CSS**) desenvolvido para atender aos requisitos de **semântica**, **acessibilidade** e **responsividade**. O objetivo é demonstrar boas práticas de marcação, navegação acessível e layout adaptável para diferentes tamanhos de tela.

---

## Funcionalidades principais

* Navegação clara com header e menu responsivo (hamburger em telas pequenas).
* Uso correto de elementos semânticos (`<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<aside>`, `<footer>`).
* Formulário de contato acessível (labels, `aria-*`, validação básica).
* Imagens com `alt` descritivo e `picture`/`srcset` para responsividade (quando aplicável).
* Link “pular para o conteúdo” (skip link) para facilitar navegação por teclado.
* Contraste de cores compatível com WCAG AA (indicativo — validar).
* Layout fluido que funciona em mobile, tablet e desktop.
* Grid/flexbox sem dependências externas.
* CSS organizado e comentado (arquivo único ou com partials se desejar).

---

## Como rodar localmente

1. Clone o repositório:

```
git clone https://github.com/seu-usuario/seu-repo.git
```

2. Abra o `index.html` no navegador (duplo clique ou `Ctrl+O` → abrir arquivo).
   (Como é somente HTML/CSS, não é necessário servidor; opcionalmente use um servidor local para evitar bloqueios de CORS em algumas features: `npx http-server` ou `python -m http.server`.)

---

* Autor: Nathalia Lima

