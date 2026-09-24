## 2024-05-15 - Playwright Tests with Localized UIs
**Learning:** This app heavily relies on localized text (via the `t` object). Writing tests or automated verifications that query by text (e.g., "HOME") will fail or timeout if the app loads with a different default language (e.g., Russian "ГЛАВНАЯ").
**Action:** When creating verification scripts, use generic selectors (like test-ids, classes, ARIA roles/labels) or wait for a known localized string instead of hardcoding English text if the app defaults to another language.
