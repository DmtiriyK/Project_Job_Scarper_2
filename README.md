# Project Job Scraper 🇩🇪

## Übersicht  
Ein Portfolio-Projekt zur Analyse von Data-Analytics- und Junior-Data-Analyst-Stellenanzeigen in Deutschland.  
Es umfasst:

- **Scraper** (LinkedIn-Jobdaten)
- **Datenbereinigung**
- **Merkmalsanreicherung** (Bool-Werte, Remote, Sprache, Senioritätsklasse)
- **Visualisierungen & Modellierung**
- **Maschinelles Lernen** (Random Forest, K-Means)
- **Interaktiver Notebook** im Jupyter Format  
- Alle Visualisierungen zur leichten Integration

---

## 📁 Projektstruktur

├── data
├── Jupyter_code
│ ├── linkedin_scraper.ipynb
│ ├── cleaner.ipynb
│ └── ...
├── visualizations/
│ ├── skills_bar_chart.png
│ ├── skills_bar_chart_top5.png
│ ├── skills_heatmap_python_sql.png
│ └── ... Weitere Diagramme
├── Final_Visual.ipynb
├── README.md
└── requirements.txt

---

## 🚀 Installation und Setup

1. Repository klonen  
   ```bash
   git clone https://github.com/DmtiriyK/Project_Job_Scarper_2.git
   cd Project_Job_Scarper_2

🧩 Datenworkflow
LinkedIn-Scraper
– Verwendung von requests + BeautifulSoup
– Sammeln von Titel, Firmen, Ort, Beschreibung usw.
– Erkennung: Remote, Sprache, Seniorität, Fähigkeit-Features

Datenbereinigung
– Entfernen von Duplikaten & ungültigen URLs
– Standardisierung von Title, Company, Seniority, Lang
– Konvertierung der Bool-Werte (Has_*, Remote)

Reiche Datenerweiterung
– Bool-Spalten für verschiedene Skills (z. B. Has_PYTHON)
– Bestimmung der Sprache (Lang) & Senioritätslevel

Maschinelles Lernen
– Random Forest Classifier zur Vorhersage von Python-Anforderung
– K-Means Clustering + PCA zur Gruppierung von Skill-Profilen

📊 Visualisierungen
1. Fähigkeiten – Gesamtsicht

2. Top 5 gesuchte Skills

3. Anteil Python-Jobs

4. Kombination Python & SQL
Weitere Grafiken
Verteilung nach Sprache der Anzeige
Häufigkeitsanalyse nach Stadt/Ort
Histogramm: Anzahl Skills pro Job
Vergleich nach Arbeitsmodell (Remote / Hybrid / Vor-Ort)

🧠 Maschinelles Lernen – Ergebnisse
Random Forest Klassifikator:
Training/Test-Split
classification_report + confusion_matrix
Top 5 Einflussfaktoren (Feature Importances) für Python-Anforderungen
K-Means + PCA
Visualisierung der Skill-Cluster
Profilanalyse pro Cluster (Top-10 Skills)

🗣️ Nutzungsanleitung
Final_Visual.ipynb starten, um alle Analysen & Modelle nachzuvollziehen
data/linkedin_jobs_germany_enriched.csv lädt alle genutzten Daten
requirements.txt enthält alle benötigten Python-Pakete
Visualisierungen sind fertig exportiert im Ordner visualizations/


🔧 Erweiterungsmöglichkeiten
Automatisierung mit GitHub Actions (für scrapes im Zeitintervall)
Textanalyse (z. B. Begriffe mit wordcloud) oder Sentiment-Analyse
Ausbau mit zusätzlichen Datenquellen wie Indeed oder StepStone
Deployment der Visualisierungen mit Dash oder Streamlit


📄 Lizenz
MIT-Lizenz – schreib, veränder, nutz frei.
© 2025 Dmitriy König

Danke fürs Reinschauen 👊
Bei Fragen, Feedback oder Kooperationen — einfach melden 😉

