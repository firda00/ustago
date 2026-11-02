## 2025-05-19 - Semantic HTML and Focus Visibility
**Learning:** Top-level navigation relies on non-semantic clickable `div`s. Icon buttons across the UI lack focus-visible classes for keyboard accessibility.
**Action:** When working on navigation or buttons, replace clickable `div`s with semantic `<button>` tags with `aria-label`s. Ensure to add `focus-visible:ring-2 focus-visible:ring-black outline-none` to interactive elements. For elements with dark backgrounds (like `bg-black`), ensure to add `focus-visible:ring-offset-2`.
