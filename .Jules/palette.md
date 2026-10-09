## 2024-05-20 - Icon-Only Navigation Button Pattern
**Learning:** Icon-only navigation buttons across the UstaGo application (like Back buttons and Language Switchers) consistently lack accessible labels and keyboard focus indicators, making the primary navigation flows inaccessible for screen reader and keyboard users.
**Action:** Enforce strict inclusion of `aria-label` (using translation keys with fallbacks like `t.back || 'Back'`) and Tailwind focus ring utilities (`focus-visible:ring-2 outline-none`) on all icon-only components.
