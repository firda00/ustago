## 2024-05-24 - Missing ARIA Labels on Icon-only Buttons
**Learning:** Found several icon-only buttons in the top navigation and bottom navigation that are missing `aria-label` attributes, making them inaccessible to screen reader users. The application also uses non-semantic clickable divs for brand logo navigation.
**Action:** Always add `aria-label` using the localization object (or a safe fallback) to icon-only buttons to ensure they are perceivable by assistive technologies.
