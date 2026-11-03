## 2025-03-09 - Accessible Interactive Navigation
**Learning:** The codebase has historically used an anti-pattern of non-semantic clickable divs for top-level navigation, along with missing accessible labels and focus indicators for icon buttons.
**Action:** Replace `div` tags with `<button>` for semantic interactions, provide `aria-label` with dynamic fallbacks to ensure screen reader support, and use Tailwind utilities (`focus-visible:ring-2`, `focus-visible:ring-offset-2`) for proper keyboard focus indication.
