---
name: accessible-component-generator
description: Generate fully accessible React/Vue/HTML components with correct ARIA roles, keyboard handlers, and focus management.
---

# Accessible Component Generator

## When to use

- Building new interactive UI components
- Replacing inaccessible legacy components
- Creating form elements, modals, dropdowns, tabs

## Instructions

1. Identify component type (modal, dropdown, tabs, accordion, tooltip, etc.)
2. Apply correct ARIA pattern from WAI-ARIA Authoring Practices
3. Implement keyboard interactions:
   - Modal: Escape closes, focus trap, return focus on close
   - Dropdown: Arrow keys navigate, Enter selects, Escape closes
   - Tabs: Arrow keys switch tabs, Tab moves to panel
4. Add visible focus styles
5. Include screen reader announcements for dynamic changes
6. Test with axe-core assertions in component tests

## Output

Complete accessible component with:
- Correct semantic HTML or ARIA roles
- Full keyboard support
- Focus management
- Screen reader announcements
- axe-core passing test
