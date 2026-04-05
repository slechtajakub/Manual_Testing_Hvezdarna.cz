# Manual Testing — Hvězdárna a planetárium Brno

Portfolio projekt manuálního testování reálného produkčního webu.

**Jira:** [odkaz](https://slechtajakub.atlassian.net/jira/software/projects/KAN/boards/2?jql=&atlOrigin=eyJpIjoiMjY5OGVkYTlhZDAwNGU1Y2JkZjU0YjM2Njc5NDM3ZTUiLCJwIjoiaiJ9)

**Testovaný web:** [hvezdarna.cz](https://www.hvezdarna.cz)  
**Typ testování:** Black-box, manuální funkční testování  
**Nástroje:** Jira, Chrome DevTools, Google Docs  
**Datum:** Duben 2026

---

<img width="1418" height="948" alt="Hvezdarna_Jira_manual_testing" src="https://github.com/user-attachments/assets/70122224-f019-4d64-9d4b-09c3007581dc" />

---

## Výsledky

| Metrika | Hodnota |
|---|---|
| Test cases celkem | 11 |
| PASS | 8 |
| FAIL | 3 |
| Nalezené bugy | 3 |
| Pass rate | 72,7 % |
| Závažnost bugů | Minor (žádný Critical / Major) |

---

## Pokryté oblasti

| Oblast | TC |
|---|---|
| Navigace | TC-001, TC-002 |
| Program / Vstupenky | TC-003, TC-004 |
| Formulář (newsletter) | TC-005, TC-006 |
| Responzivita (DevTools) | TC-007 |
| Cross-browser | TC-008 |
| UI / Broken links | TC-009 |
| Výkon (DevTools Network) | TC-010 |
| DevTools Console | TC-011 |

---

## Nalezené bugy

**KAN-10** — Newsletter formulář nepřijme neplatný e-mail, ale nezobrazí chybovou hlášku  
**KAN-11** — Tlačítko "Více informací" — text oříznut na mobilním zařízení (iPhone 14)  
**KAN-15** — JS error v Console: No Listener: tabs:outgoing.message.ready (vendor.js:159)

---

## Dokumenty

- [`docs/test_plan_hvezdarna.docx`](docs/test_plan_hvezdarna.docx) — Test Plan
- [`docs/test_summary_hvezdarna.docx`](docs/test_summary_hvezdarna.docx) — Test Summary Report

---

## Struktura projektu

```
Manual-Testing-Hvezdarna.cz/
├── README.md
├── test_plan_hvezdarna.pdf
├── test_summary_hvezdarna.pdf
├── hvezdarna_jira_manual_testing.png


```

---

