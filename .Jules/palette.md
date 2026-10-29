## 2024-03-24 - Semantic Logo Navigation
**Learning:** The main application logo navigation was implemented using a non-semantic `div` with an `onClick` handler, causing it to be inaccessible to keyboard users as it could not receive focus.
**Action:** Always replace clickable structural `div` elements intended for navigation with semantic `<button>` or `<a>` tags. Ensure they have appropriate `aria-label` attributes (e.g., "Home") and focus-visible styling (`focus-visible:ring-2 focus-visible:ring-black outline-none`) to support keyboard navigation.
