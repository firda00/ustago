## 2024-05-19 - Semantic Main Navigation
**Learning:** Found a pattern of non-semantic clickable divs used for logo navigation and missing ARIA labels on core icon-only buttons (like Admin and Edit) within the persistent top navigation layout.
**Action:** Ensure all interactive elements in top-level persistent layout components use semantic HTML `<button>` tags with keyboard focus styling (`focus-visible:ring-2 focus-visible:ring-black outline-none`) and proper `aria-label` attributes for icon-only instances.
