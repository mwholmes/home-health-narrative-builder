# Home Health Narrative Builder

A standalone browser app with 135 reusable sentences for home health nursing narratives, including assessments, wound care, verbal and written education, homebound statements, and functional limitations.

## Use the builder

Choose sentences, fill in visit details, rearrange them, and review the finished narrative. You can edit the final text, copy it, download it as a text file, or print it.

All application code and sentence templates are included in `index.html`. Open that file in a browser to use the app offline.

## Draft handling

Drafts stay in memory in the current browser tab. The app does not include a database, analytics, cloud saving, or automatic local storage. Copy your note before closing or refreshing, and clear the draft between visits.

Use only statements that accurately reflect the visit and follow your organization's documentation and privacy requirements.

## Hosting

GitHub Pages serves the `main` branch from the repository root. The `.nojekyll` file lets GitHub serve the app without Jekyll processing.
