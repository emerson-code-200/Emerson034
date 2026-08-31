# Portfólio Emerson

Portfólio pessoal de desenvolvedor Full Stack com identidade visual brutalist/technical.

## Design

Identidade visual afiada com paleta **acid green + signal orange**, geometria quadrada (0-4px radius) e animações fluidas. Sem clichês de AI (sem purple, sem glassmorphism, sem bento grids).

## Tecnologias

- HTML5 (estrutura semântica)
- CSS3 (variáveis CSS, animações, grid, flexbox)
- JavaScript (ES6+, Canvas API, Intersection Observer)
- Express.js (servidor local)

## Cores

| Cor        | Código    | Uso                       |
| ---------- | --------- | ------------------------- |
| Background | `#0a0a0b` | Fundo principal           |
| Primary    | `#b4f72e` | Acid green - destaque     |
| Secondary  | `#ff4d2d` | Signal orange - contraste |
| Text       | `#f0f0f0` | Texto principal           |

## Funcionalidades

- Header sticky com fundo sólido
- Menu mobile com hamburger animation
- Scroll reveal animations (staggered)
- Partículas interativas com Canvas (acid green + orange)
- Micro-interactions nos cards (hover glow)
- Botões com inversão de cores
- Scroll progress bar com glow
- Loading screen
- Formulário com validação
- Social links com SVG icons
- Favicon e Open Graph meta tags
- Lazy loading em imagens

## Como Rodar

```bash
npm install
npm start
```

Acesse: http://localhost:3000

## Estrutura

```
├── index.html          # Página principal
├── server.js           # Servidor Express
├── package.json        # Dependências
├── css/
│   └── styles.css      # Estilos e tema
├── js/
│   └── main.js         # Lógica principal
├── assets/
│   └── images/         # Imagens
└── docs/
    └── PLAN.md         # Documentação
```

## Design Decisions

- **Sem glassmorphism** - Fundos sólidos com bordas visíveis
- **Sem purple/lavender** - Paleta acid green + orange
- **Geometria afiada** - Border-radius 0-4px
- **Animações fluidas** - cubic-bezier easing
- **Social links com SVG** - Ícones reais
