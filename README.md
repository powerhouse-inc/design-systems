# Powerhouse Design Systems

Design system packages for the various Powerhouse products and brands.

## Contents

This repository contains self-contained design system packages for the following brands:

- **Achra** (`achra/`) — Includes style guide, color tokens, logos, website templates, document templates, and animations.
- **Vetra** (`vetra/`) — Includes style guide, color tokens, logos, website templates, document templates, and animations.
- **Connect** — Coming soon
- **Powerhouse** — Coming soon

Each package contains:

| Path | Description |
| --- | --- |
| `index.html` | Main design system overview |
| `styleguide.html` | Component and typography style guide |
| `colors.css` | Color token definitions |
| `presentation.html` | Presentation template |
| `documents.html` | Document template previews |
| `logos/` | Brand logos in SVG format |
| `website/` | Website page templates (landing page, pricing, blog, dashboard, etc.) |
| `animation/` | Animation references and assets |

## Viewing

Open any `index.html` file in a browser to explore the design system for that brand:

```
achra/index.html
vetra/index.html
```

All HTML files are **self-contained** — no build step or local server is required. Simply open them directly in your browser.

## Usage with Coding Agents

These files are designed to be referenced by coding agents (such as Claude Code) when implementing designs. Point the agent at the relevant HTML or CSS files and it can extract colors, typography, component patterns, and layout structures to apply the correct brand design to your project.
