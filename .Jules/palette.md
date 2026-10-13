## 2026-10-13 - Accessible Icon Buttons
**Learning:** Icon-only buttons (like Log Out, Send, and Remove Service) lack accessible names, making them invisible to screen readers. Furthermore, focus rings are missing across the app.
**Action:** Always include `aria-label` on `<button>` elements that only contain an icon, and apply `focus-visible:ring-2 focus-visible:ring-black outline-none` (or appropriate ring color) for keyboard navigation.
