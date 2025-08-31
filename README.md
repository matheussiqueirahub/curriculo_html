# Currículo HTML — Matheus Siqueira

Currículo simples em HTML/CSS com tema claro/escuro automático e layout responsivo. Mantém as informações atuais do perfil, com foco em Full Stack e Dados.

## Como visualizar

Abra `index.html` no navegador.

- Windows (PowerShell): `start index.html`
- macOS: `open index.html`
- Linux (GNOME): `xdg-open index.html`

## Estrutura

```
.
├─ index.html   # Página do currículo (estilos embutidos)
└─ assets/
   ├─ perfil.jpg  # Foto usada no cabeçalho
   └─ foto.jpeg/  # Pasta com outras fotos originais (backup)
```

## Ajustes feitos

- Corrigido caminho da foto (agora em `assets/perfil.jpg`).
- Acentuação/encoding padronizados em UTF-8.
- Pequenos aprimoramentos de acessibilidade (alt, `rel="noopener noreferrer"`) e performance (`loading=lazy`).

## Personalização rápida

- Trocar a foto: substitua `assets/perfil.jpg` por outra imagem.
- Editar conteúdo: altere os textos diretamente em `index.html`.
- Cores: ajuste os tokens no `:root` (variáveis CSS).

## Licença

MIT

