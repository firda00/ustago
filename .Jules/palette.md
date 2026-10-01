## 2026-10-01 - [Icon-Only Buttons Missing Accessibility Attributes]
**Learning:** Several icon-only buttons (like back, proceed, send, logout, and delete) in `index.tsx` were missing `aria-label` attributes and visible focus states, making them inaccessible to screen readers and keyboard users.
**Action:** Systematically add `aria-label`s and Tailwind focus classes (`focus-visible:ring-2 focus-visible:ring-black outline-none`) to icon-only buttons to ensure a smooth, accessible experience for all users.
