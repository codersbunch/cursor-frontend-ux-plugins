---
name: figma-component-generator
description: Generate React/Vue components from Figma designs using the Figma MCP connection. Ensures components match design specs exactly.
---

# Figma Component Generator

## When to use

- Implementing new designs from Figma
- Verifying existing components match Figma specs
- Syncing design changes to code

## Instructions

1. Connect to Figma via MCP to fetch component specs
2. Extract: dimensions, colors, typography, spacing, variants
3. Map Figma properties to design tokens
4. Generate component code using design system primitives
5. Add all Figma variants as component props
6. Include responsive breakpoints from Figma frames
7. Generate Storybook story for each variant

## Output

- Component file using design system tokens
- Storybook story with all variants
- CSS/Tailwind classes using token values only
