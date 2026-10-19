## 2025-02-26 - [Top-Level Navigation Accessibility]
**Learning:** [The codebase has historically used an anti-pattern of non-semantic clickable divs for top-level navigation, which breaks screen reader support and keyboard navigation.]
**Action:** [When creating or modifying interactive layout components, always ensure they use semantic HTML `<button>` tags with appropriate `aria-label` attributes and focus-visible utilities.]
