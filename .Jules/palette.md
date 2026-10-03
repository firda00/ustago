## 2024-10-24 - Accessible Icon-Only Buttons
**Learning:** Icon-only buttons lack accessible names by default, making them unreadable to screen readers. They also often lack clear focus states for keyboard users.
**Action:** Always verify icon-only buttons include an `aria-label` (preferably tied to a localized string) and explicitly add `focus-visible` states (e.g., `focus-visible:ring-2 focus-visible:ring-black outline-none`).
