<div align="center">

# ✦ Portfólio — Lucas Ferreira

**Site de portfólio pessoal desenvolvido com HTML, CSS e JavaScript puro.**  
Design escuro, animações interativas no Canvas e experiência totalmente responsiva.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
[![Licença MIT](https://img.shields.io/badge/licen%C3%A7a-MIT-green?style=flat)](./LICENSE)

</div>

---

## Sobre o projeto

Site de portfólio construído do zero, sem frameworks ou dependências externas. Apresenta uma hero page com efeito typewriter, página de contato e um conjunto de **6 demos interativos** criados com Canvas API — cada um com física e animações em tempo real.

---

## Páginas

| Rota | Descrição |
|------|-----------|
| `/` | Hero page com typewriter, badges e cards de navegação |
| `/Contato` | Cards de contato (LinkedIn) de Lucas e Nícolas |
| `/Formulario` | Briefing de solicitação de desenvolvimento de blog |
| `/demos/1-particles.html` | Partículas Interativas — repulsão pelo mouse |
| `/demos/2-fluid.html` | Fluid Ink Blobs — manchas fluidas |
| `/demos/3-grid.html` | Grid Magnético — grade que reage ao cursor |
| `/demos/4-aurora.html` | Aurora Boreal — ondas de luz animadas |
| `/demos/5-matrix.html` | Tech Matrix — chuva de caracteres estilo Matrix |
| `/demos/6-galaxy.html` | Galáxia — campo de estrelas em rotação |

---

## Destaques

- **Zero dependências** — sem npm, sem bundler, sem framework. Abre direto no navegador.
- **Canvas API** — 6 animações independentes com física customizada e interação por mouse.
- **Design system coeso** — paleta escura `#0a0a0f`, gradientes indigo/cyan, tipografia Inter, bordas glassmorphism.
- **Typewriter dinâmico** — alternância automática de títulos na hero com cursor piscante.
- **Totalmente responsivo** — layout fluido com `clamp()` e media queries para todos os tamanhos de tela.
- **Animações CSS** — entrada `fadeUp`, pulso de status e transições suaves em hover.

---

## Estrutura

```
site-portifolho/
├── index.html          # Hero page (landing principal)
├── Contato/
│   └── index.html      # Página de contato
├── Formulario/
│   └── index.html      # Formulário de briefing
└── demos/
    ├── 1-particles.html
    ├── 2-fluid.html
    ├── 3-grid.html
    ├── 4-aurora.html
    ├── 5-matrix.html
    └── 6-galaxy.html
```

---

## Como rodar localmente

Não é necessário instalar nada. Basta clonar e abrir no navegador:

```bash
git clone https://github.com/seu-usuario/site-portifolho.git
cd site-portifolho
# Abra o index.html no navegador, ou use um servidor local:
npx serve .
```

> Recomendado usar um servidor local (como `npx serve` ou a extensão **Live Server** do VS Code) para evitar restrições de CORS ao navegar entre as páginas.

---

## Deploy

O site é estático e pode ser publicado em qualquer hospedagem gratuita:

- **GitHub Pages** — ative nas configurações do repositório (`Settings → Pages → Deploy from branch`)
- **Vercel** — importe o repositório e faça deploy com um clique
- **Netlify** — arraste a pasta do projeto para o painel de deploy

---

## Tecnologias

| Tecnologia | Uso |
|------------|-----|
| HTML5 Semântico | Estrutura de todas as páginas |
| CSS3 | Estilização, animações, gradientes, responsividade |
| JavaScript (ES6+) | Typewriter, Canvas API, física das animações |
| Google Fonts (Inter) | Tipografia |
| Canvas API | Todos os 6 demos interativos |

---

## Autor

<table>
  <tr>
    <td align="center">
      <strong>Lucas Ferreira</strong><br>
      Desenvolvedor Fullstack<br>
      <a href="https://www.linkedin.com/in/seu-perfil">LinkedIn</a>
    </td>
  </tr>
</table>

---

## Licença

Distribuído sob a licença **MIT**. Veja o arquivo [LICENSE](./LICENSE) para mais detalhes.