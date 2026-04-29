# Projektstudium

## Überblick

Dieses Repository enthält den gesamten Code zum Projektstudium.
Alle Komponenten, die für die Durchführung der Prognosen notwendig sind, befinden sich im Verzeichnis **`forecasting/`**.

Das Forecasting-Modul ist in drei zentrale Bereiche unterteilt: **data**, **preprocessing** und **models**.

---

### 📁 Ordnerstruktur

```text
forecasting/
├─ data/
│  ├─ raw/
│  │  └─ (unveränderte Rohdaten im CSV-Format)
│  └─ processed/
│     └─ (aufbereitete Daten)
│
├─ exploratory_data_analysis/
│  └─ exploratory_data_analysisg.ipynb
│     (Notebook zur Datenaufbereitung für das Verständnis der Daten)
│
├─ preprocessing/
│  └─ preprocessing.ipynb
│     (Notebook zur automatisierten Datenaufbereitung)
│
└─ models/
   ├─ arima/
   │  └─ arima_forecast.ipynb
   │     (Implementierung des ARIMA-Prognosemodells)
   │
   └─ xgboost/
      └─ xgboost_forecast.ipynb
         (Implementierung des XGBoost-Prognosemodells)
```


---

## Git Konventionen


### Branches

**Namensschema:**

`[type]/[ticket-number]-[brief-description]`


**Typen:**
- `arima` –ARIMA Implementierung
- `xgboost` – XGBoost Implementierung
- `data` – Datenaufbereitung, Hinzufügen von Daten
- `na` – Sonstige Änderungen

**Beispiel:**

`xgboost/PROJ-50-model-anwenden`



---

### Commits

**Namensschema:**

`[ticket-number]: [brief-description]`


**Beispiel:**

`PROJ-50: trained xgboost model`
