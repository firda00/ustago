## 2026-10-11 - Icon Button Accessibility
**Learning:** Adding ARIA labels and focus rings to icon-only buttons significantly improves navigation and clarity for keyboard and screen reader users without altering visual design. Fallbacks for translation strings (e.g., `t.back || 'Back'`) are necessary to prevent rendering literal 'undefined' strings when keys are missing.
**Action:** Always include `aria-label` (using translation strings with safe fallbacks) and `focus-visible` utility classes for interactive elements missing visible text.
