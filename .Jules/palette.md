
## 2024-05-15 - Interactive Non-Semantic Divs
**Learning:** The app's top-level logo navigation used a non-semantic `<div>` with an `onClick` handler, lacking both keyboard accessibility and screen reader support.
**Action:** Always convert interactive top-level navigation elements to semantic `<button>` or `<a>` tags with `aria-label` and visible focus states.
