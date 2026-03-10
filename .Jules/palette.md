## 2026-03-10 - Explicit focus-visible styles missing for interactive elements
**Learning:** Found that keyboard navigation was lacking clear focus indicators across the application for elements like links, buttons, and form inputs.
**Action:** Always ensure that `a:focus-visible`, `.button:focus-visible`, `input:focus-visible`, and `textarea:focus-visible` are defined in `global.css` or equivalent to provide clear keyboard accessibility cues.
