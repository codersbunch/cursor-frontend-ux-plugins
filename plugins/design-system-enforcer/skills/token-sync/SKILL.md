---
name: token-sync
description: Sync design tokens from Figma to code. Keeps colors, spacing, and typography tokens in sync automatically.
---

# Token Sync

## When to use

- After design tokens are updated in Figma
- During design system setup
- When onboarding a new project to the design system

## Instructions

1. Connect to Figma API via MCP
2. Extract all token values from Figma Variables or Styles
3. Map to token format (Style Dictionary, Theo, or CSS custom properties)
4. Generate token files:
   - `tokens/colors.json`
   - `tokens/spacing.json`
   - `tokens/typography.json`
5. Run Style Dictionary to compile to CSS/JS/SCSS
6. Flag any tokens used in code that no longer exist in Figma

## Output

- Updated token files
- Diff of changed token values
- List of deprecated tokens still in use
