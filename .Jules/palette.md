## 2024-05-18 - Missing ARIA labels on Icon-only Elements
**Learning:** Found an accessibility issue pattern specific to this app where clickable `div` and `button` tags functioning as icon buttons omit semantic text, leaving them inaccessible to screen readers.
**Action:** Always ensure that interactive elements with only icons receive proper `aria-label` tags with translatable context like `t.home` or descriptive text, and enforce focus outlines like `focus-visible:ring-2 focus-visible:ring-black outline-none` to aid keyboard navigation.
