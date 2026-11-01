
## 2024-11-01 - [Semantic Navigation Improvements]
**Learning:** The codebase has historically used an anti-pattern of non-semantic clickable divs for top-level navigation (such as logos) which impacts keyboard accessibility and screen readers.
**Action:** When creating or modifying interactive layout components, always ensure they use semantic HTML `<button>` tags with appropriate `aria-label` attributes and keyboard focus states (`focus-visible:ring-2`, `focus-visible:ring-black`, `outline-none`).
