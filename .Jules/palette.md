## 2024-05-15 - Initial\n**Learning:** Initial Palette memory file.\n**Action:** Create.
## 2024-05-15 - Icon Button Accessibility
**Learning:** Icon-only interactive elements in the application navigation/dashboards were missing critical screen-reader ARIA descriptions and keyboard focus states, causing degraded accessibility.
**Action:** Ensure `aria-label` utilizing the translation system (`t.key || 'Fallback'`) and robust focus classes (`focus-visible:ring-2 focus-visible:ring-black outline-none focus-visible:ring-offset-2`) are applied uniformly to all non-text buttons.
