## 2024-05-15 - Missing ARIA Labels on Icon Buttons
**Learning:** The application uses many icon-only buttons for critical actions (logout, edit, back, admin, support, delete) without any `aria-label` attributes. This makes it impossible for screen reader users to understand what these buttons do.
**Action:** Add `aria-label` attributes to icon-only buttons using translations when possible or English fallbacks to ensure accessibility.
