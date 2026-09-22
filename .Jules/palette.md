## 2024-05-24 - Missing ARIA labels on Icon-only Back Buttons
**Learning:** The app extensively uses `<ArrowLeft>` and `<LogOut>` components as icon-only buttons for navigation and actions without any accessible names (`aria-label`) or focus visible styles. This makes them invisible to screen readers and keyboard users.
**Action:** Always add `aria-label` utilizing the translation dictionary (e.g., `aria-label={t.back}`) and `focus-visible:ring-2 outline-none` to provide clear keyboard focus states on all icon-only interactive elements.
