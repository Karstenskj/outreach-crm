# Outreach CRM

Et lille, privat CRM til universitets-outreach (forhåndsmerit AI-check).

- **Appen** (denne repo, offentlig): `index.html` — vises via GitHub Pages.
- **Dataene** (privat repo `outreach-crm-data`): `data.json` — hentes/gemmes via GitHubs API, aldrig offentligt.

## Åbn CRM'et
👉 https://karstenskj.github.io/outreach-crm/

Første gang bliver du bedt om en adgangsnøgle (fine-grained token) med **Contents: Read and write** til repoet `outreach-crm-data`. Den gemmes kun i din egen browser.

## Sådan virker det
- Kanban-board efter fase (Emner → Kontakt fundet → Kontaktet → I dialog → Tilbud sendt → Vundet/Tabt).
- Træk kort mellem kolonner for at flytte fase.
- Klik et kort for at redigere kontaktpersoner, næste handling, aktivitetslog og noter.
- Ændringer gemmes automatisk til GitHub (commit i `outreach-crm-data`).
- Claude kan også tilføje/rette data direkte i `data.json` — tryk ↻ for at hente nyeste.

Ingen byggeværktøjer, ingen Node — bare en HTML-fil.
