## 2024-05-18 - Icon-Only Button Accessibility
**Learning:** Found several icon-only buttons (like Admin, Back, Send) missing `aria-label` attributes. This breaks the experience for screen reader users who just hear "button" without context.
**Action:** Add `aria-label` to these buttons using the translation system (`t.key || 'Fallback'`) for better accessibility.
