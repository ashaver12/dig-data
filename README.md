# dig-data

Published league data for **Dig**, the Cincinnati sand volleyball schedule app.

These files are written by the Dig repo's daily GitHub Action and read by the app at
launch. Nothing here is edited by hand.

| File | What |
|---|---|
| `grandsands.json` | Grand Sands schedules and standings |
| `cincinnatisand.json` | Cincinnati Sand schedules and brackets (read from images by free OCR) |
| `history.json` | Season archive: past divisions with final standings |

Everything is scraped from the venues' own public sites and carries a `generatedAt`
timestamp; the app keeps whichever copy is newest.