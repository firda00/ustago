
## 2023-10-10 - Screen Reader Accessibility Pattern Discovered
**Learning:** This application heavily relies on lucide-react icons mapped inside `<button>` elements across nearly every interactive screen (e.g., Modals, Dashboards, Quoting Flow), but universally missed providing `aria-label` tags for icon-only usage.
**Action:** When adding new functional buttons with only icons, always wrap them in semantic elements and explicitly define `aria-label` tags paired with `focus-visible:ring-2 focus-visible:ring-black outline-none` for optimal usability, preferring translated `t.key` values.
