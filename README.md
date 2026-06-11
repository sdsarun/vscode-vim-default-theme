# Vim Default

A bold, high-contrast Vim-inspired dark theme for VS Code.

Vim Default is designed for strong syntax separation, fast scanning, and long coding sessions with a retro neon tone.

## Features

- Dark background optimized for focus
- Semantic token highlighting enabled
- Clear contrast between keywords, types, functions, variables, and constants
- Works well across JavaScript, TypeScript, Python, Rust, Go, Java, PHP, JSON, Markdown, and more

## Install

### From VS Code Marketplace

1. Open Extensions in VS Code
2. Search for Vim Default
3. Click Install
4. Open Preferences: Color Theme
5. Select Vim Default

### Local VSIX Install

1. Build package:
   npm run pack
2. Install package:
   code --install-extension vim-default-0.0.1.vsix --force
3. Reload window
4. Select Vim Default in Preferences: Color Theme

## Recommended Settings

Enable semantic highlighting for best results:

```json
{
  "editor.semanticHighlighting.enabled": true
}
```
