## 2026-11-09 - Icon-only buttons lacking ARIA labels
**Learning:** Found several icon-only buttons (like LogOut, ArrowLeft for back, Trash2 for delete, and Edit3 for edit mode) that are missing 'aria-label' attributes. This makes them inaccessible to screen readers.
**Action:** When adding or maintaining icon-only buttons, always ensure they have an appropriate descriptive 'aria-label'.
