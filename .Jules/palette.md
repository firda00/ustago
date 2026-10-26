## 2026-10-26 - [Navigation Accessibility]
**Learning:** [The codebase has historically used an anti-pattern of non-semantic clickable divs for top-level navigation (like the logo) and missing focus indicators on icon buttons.]
**Action:** [When creating or modifying interactive layout components, always ensure they use semantic HTML `<button>` tags with appropriate `aria-label` attributes and keyboard focus indicators (`focus-visible:ring-2 focus-visible:ring-black outline-none`). If the element has a dark background, add `focus-visible:ring-offset-2`.]
