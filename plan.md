1. **Analyze UX Issues**: Identify accessibility or usability issues in the current UI components. In particular, we see numerous icon-only `<button>`s without `aria-label` attributes. Missing labels on icon-only buttons severely hinder accessibility for screen-reader users, as they are not informed of the button's action. This is a common and impactful issue. Examples:
    - ArrowLeft button in `GetQuoteModal`: `<button onClick={back} ...><ArrowLeft size={20}/></button>`
    - Navigation ArrowLeft to go back to dashboard.
    - Delete button in master dashboard: `<button onClick={() => removeService(s.id)} ...><Trash2 size={20}/></button>`
    - Send button in support modal: `<button onClick={send} ...><Send size={20}/></button>`
2. **Select Enhancement**: The best quick enhancement to improve accessibility is to add `aria-label` attributes to these icon-only `<button>` tags using the translation keys where appropriate, or a standard label, ensuring that screen readers convey the button's purpose correctly. Additionally, ensure they have proper focus-visible styles. Wait, the system uses `<T>` elements heavily and translating ARIA labels might be harder. Since `t.back` exists, we can use `aria-label={t.back || 'Back'}`. Or simply adding `aria-label` for common actions.
3. **Write Implementation Details**: Find icon-only buttons across `index.tsx` and add `aria-label` attribute and ensure focus states are accessible (by adding `focus-visible:ring-2 focus-visible:ring-black outline-none` to their class names where missing).
4. **Pre Commit Steps**: Run tests and lint to ensure it meets requirements before submission.
5. **Submit**: Create PR.
