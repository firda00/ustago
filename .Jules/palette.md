## 2023-10-25 - [Added ARIA Labels to Icon-Only Buttons]
**Learning:** Found several icon-only buttons (admin, edit mode, back buttons) missing accessible names and keyboard focus indicators, which degrades the experience for screen reader users and keyboard navigators.
**Action:** Applied `aria-label` properties to these buttons using the existing translation object `t` (e.g., `aria-label={t.back}`) and added the recommended Tailwind CSS focus state utilities (`focus-visible:ring-2 focus-visible:ring-black outline-none`) as per the codebase conventions.
