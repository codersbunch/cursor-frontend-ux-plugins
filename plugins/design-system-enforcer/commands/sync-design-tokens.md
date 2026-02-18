---
name: sync-design-tokens
description: Sync design tokens from Figma to codebase and regenerate token files.
---

# Sync Design Tokens

Pull latest tokens from Figma and update all token files.

## Steps

1. Connect to Figma API and fetch latest Variables/Styles
2. Compare with current token files
3. Generate diff of changes
4. Update token source files
5. Run Style Dictionary to compile tokens to CSS/JS/SCSS
6. Run `npm run build:tokens`
7. List deprecated tokens still referenced in code
