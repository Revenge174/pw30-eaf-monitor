# PW30 – EAF Monitor

Piattaforma digitale per il monitoraggio energetico, economico e operativo di un forno elettrico ad arco (EAF) in ottica Industria 5.0.

Project Work – Corso di Laurea L-31 Informatica per le aziende digitali, Università Telematica Pegaso.
Autore: Sebastiano Daniele Condorelli.

> Prototipo didattico. I dati sono **simulati** e calibrati su fonti pubbliche: non contiene dati aziendali reali.

## Componenti

| Componente | Tecnologia | Cartella |
| --- | --- | --- |
| Simulatore dei cicli di fusione | Python, NumPy | `simulatore/` |
| Back-end API | FastAPI | `app/` |
| Database | SQLite | `db/` |
| Dashboard | HTML, CSS, JavaScript, Chart.js | `app/static/` |
| Test | pytest | `tests/` |

## Avvio rapido (Windows)

```powershell
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```

Le istruzioni per avviare API, simulatore e dashboard verranno aggiunte man mano che i componenti saranno pronti.

## Stato

- [ ] Database e schema
- [ ] Simulatore
- [ ] Modulo KPI
- [ ] API
- [ ] Dashboard
- [ ] Test
