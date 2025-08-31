# Currículo HTML — Matheus Siqueira

## Visão Geral
- Página de currículo estática em HTML/CSS, responsiva e leve.
- Suporte automático a tema claro/escuro via `prefers-color-scheme`.
- Estruturada com foco em legibilidade, semântica e manutenção.

## Visualização
Abra `index.html` no navegador.

- Windows: `start index.html`
- macOS: `open index.html`
- Linux: `xdg-open index.html`

## Estrutura
```
.
- index.html           (página do currículo; estilos embutidos)
- assets/
  - perfil.jpg         (foto exibida no cabeçalho)
  - foto.jpeg/         (outras fotos mantidas como backup)
```

## Detalhes Técnicos
- Codificação em UTF‑8 para acentuação correta.
- Acessibilidade: `alt` em imagens; `rel="noopener noreferrer"` em links externos.
- Performance: imagens com `loading="lazy"` e `decoding="async"`.

## Personalização
- Foto: substitua `assets/perfil.jpg`.
- Conteúdo: edite os textos em `index.html`.
- Cores: ajuste as variáveis CSS no seletor `:root`.

## Licença
MIT
