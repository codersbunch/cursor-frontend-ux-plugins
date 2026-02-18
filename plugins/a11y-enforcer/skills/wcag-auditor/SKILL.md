---
name: wcag-auditor
description: Audit UI components and pages for WCAG 2.1 AA compliance. Identifies violations and provides remediation code.
---

# WCAG Auditor

## When to use

- Before shipping new UI components
- During accessibility audits
- When preparing for VPAT documentation
- After receiving accessibility bug reports

## Instructions

1. **Perceivable** - Check alt text, color contrast, captions for media
2. **Operable** - Test keyboard navigation, focus indicators, skip links
3. **Understandable** - Check form error messages, language attribute, consistent navigation
4. **Robust** - Verify valid HTML, ARIA usage, screen reader compatibility

## Output

- WCAG criterion violated (e.g., 1.4.3 Contrast)
- Element location in code
- Severity: Critical/Serious/Moderate/Minor
- Remediation code snippet
