## 2025-01-09 - Accessible Icon Buttons & Focus Rings
**Learning:** Many icon-only buttons in the application lacked proper ARIA labels, making them inaccessible to screen readers. Additionally, interactive elements lacked keyboard focus states (`focus-visible`).
**Action:** Implemented `aria-label` with localizations and consistent `focus-visible:ring-2 focus-visible:ring-black outline-none` styling across all icon buttons to improve keyboard and screen reader accessibility.
