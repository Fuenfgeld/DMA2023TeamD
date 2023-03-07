# **Projekt ReHealthCo**   |  Gruppe DMA2023TeamD

![](https://github.com/Fuenfgeld/DMA2023TeamD/blob/main/Diagramme/Logo2.png)

**ReHealthCo** ist ein Data Management Projekt zu Studienzwecken im Rahmen des [Berufsbegleitenden Online-Master „Biomedizinische Informatik und Data Science“ der Hochschule Mannheim](https://www.master-bids.hs-mannheim.de/). 
Es betrachtet **Zusammenhänge zwischen Behandlungskosten und Gesundheitszustand** für Patient:innen mit **Asthma, Covid-19 und Metabolischem Syndrom** und basierend auf synthetischen Patientendaten, die mit [Synthea TM](https://synthetichealth.github.io/synthea/) erzeugt wurden ([Walonoski et al. 2017](https://doi.org/10.1093/jamia/ocx079)).

📑 Die Dokumentation des Projektes steht unter [ReHealthCo WIKI](https://github.com/Fuenfgeld/DMA2023TeamD/wiki) zur Verfügung.

Das Projekt entstand über mehrere Entwicklungsschritte: 
Ein vertiefter Einblick ist dem WIKI-Abschnitt [Projektmanagement](https://github.com/Fuenfgeld/DMA2023TeamD/wiki/Projektmanagment) zu entnehmen.

📊 Die entstandenen Ergebnisse werden unter [Analysen und Ergebnisse](https://github.com/Fuenfgeld/DMA2023TeamD/wiki/Analysen-und-Ergebnisse) dargestellt.

### Überblick der Projektschritte und des Datenflusses
![](https://github.com/Fuenfgeld/DMA2023TeamD/blob/main/Diagramme/Datenfluss_V3_300.png)

### Codeentwicklung
1. 🟡 [Code zur Herstellung der Rohdatenbank](https://github.com/Fuenfgeld/DMA2023TeamD/blob/main/Code/ReHealthCo_Rohdatenbank.ipynb)

2. 🟠 [Code zum ETL-Prozess](https://github.com/Fuenfgeld/DMA2023TeamD/blob/main/Code/ReHealthCo_ETL.ipynb)

3. 🟣 [Code zum EDA-Prozess](https://github.com/Fuenfgeld/DMA2023TeamD/blob/main/Code/ReHealthCo_EDA.ipynb)

4. 🔵 [Code zum Vorhersagemodell-Prädiction](https://github.com/Fuenfgeld/DMA2023TeamD/blob/main/Code/ReHealthCo_Prediction.ipynb)


### Hinweis zur Reproduzierbarkeit
Die Rohdaten können über die Module Asthma, Covid-19 und Metabolic-Syndrom von [Synthea TM](https://synthetichealth.github.io/synthea/) bezogen werden. Anonymisierte Daten, auf denen die Auswertungen und das Prädiktionsmodell basieren, wurden in diesem Repositorium abgelegt ([anonym_rhcpat.csv](https://github.com/Fuenfgeld/DMA2023TeamD/blob/main/csv_data/anonym_rhcpat.csv)). 
Weitere Hinweise zur verwendeten Systemumgebung und Tools sind dem Abschnitt [Systemumgebung und verwendete Tools](https://github.com/Fuenfgeld/DMA2023TeamD/wiki/Datenmanagementplan-%28basierend-auf-FAIR-Kriterien%29#33-datendokumentation-und-metadaten-erstellen) zu entnehmen.

### 📹 Videopräsentation des Projektes ReHealthCo
[ReHealthCo_Video](--)

![](https://github.com/Fuenfgeld/DMA2023TeamD/blob/main/Diagramme/ReHealthCo_final_First_Frame.png)



