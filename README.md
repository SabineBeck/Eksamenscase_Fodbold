# Fodbold-Datadrevne-beslutninger-med-Wyscout-StatsBomb-og-Machine-Learning
⚽ Fodbolddataanalyse: Machine Learning, xG, Expected Points, Clustering, Tracking- & Eventdata
Dette projekt fokuserer på dataanalyse i fodbold med udgangspunkt i Brøndby IF. Gennem beregning af Expected Goals (xG), Expected Points (xP), klyngeanalyse af afleveringsmønstre og trackingvisualisering, undersøges hvordan data kan bruges til at understøtte sportslige og strategiske beslutninger. Der arbejdes med data fra Superligaen 2023/24, 2024/25 samt kvinde- og herrefodboldens VM.

⚽ Introduktion
Dette projekt indeholder følgende:
Indlæsning og forbehandling af fodbolddata fra flere kilder (CSV, JSON, Excel, SQL).


Udvikling og evaluering af xG-modeller for Superliga-sæsonen 2023/2024.


Beregning af Expected Points (xP) for Brøndby IF baseret på xG og kampresultater.


Clustering af spillere ud fra afleveringsdata og præstationsmønstre.


Visualiseringer via statiske plots og interaktive Shiny Dashboards.


Analyse af tracking- og eventdata fra Superligaen og VM 2023.


Etiske og juridiske refleksioner omkring dataejerskab, GDPR og brugsret.


Videnskabsteoretiske perspektiver på dataens rolle i moderne sport.



⚽ Indhold (R-scripts)
Eksamen – Datapreparation.R: Klargøring og transformation af data fra CSV, Excel, JSON og SQL til analyseformat.


Opgave 1.R: Udvikling af xG-modeller med afstand, vinkel og kropsdel som forklarende variable.


Opgave 2.R: Simulering af Expected Points for Brøndby IF via Poissonfordeling og kampdata.


Opgave 3.R: Klyngeanalyse af afleveringsmønstre i Superligaen baseret på afleveringslængde, nøjagtighed og volumen.


Opgave 4.R: Udarbejdelse af interaktivt Shiny-dashboard til visualisering og præsentation af resultater til Brøndby IF.


Opgave 5.R: Analyse af forskelle mellem kvinde- og herrefodbold med fokus på skud, xA og spilintensitet.


Opgave 6.R: Trackingdataanalyse og konstruktion af visualiseringer med "shadow-trekanter" og freeze-frames.


Opgave 7.R: Juridiske og etiske overvejelser omkring sportsdata, ophavsret og fair adgang.



⚽ Dataanalyse og Metoder
xG-model (Expected Goals)
Bruger skuddata fra Superligaen 2023/24.


Feature engineering på skudafstand, skudvinkel og kropsdel.


Modellerne inkluderer: logistisk regression, Random Forest og Gradient Boosting.


Visualisering: ROC-kurver, heatmaps og skudplacering.


xP-model (Expected Points)
xG kombineret med kampresultater og simulationsbaseret pointsberegning.


Udregnet for Brøndby IF over hele sæsonen.


Clustering og afleveringsanalyse
K-means clustering af spillere i Superligaen.


Fokus på afleveringskarakteristik: længde, nøjagtighed og volumen.


3D-visualisering og rolleprofiler.


Tracking og shadow-trekanter
Positionsanalyse ved hjælp af trackingdata (25 fps).


Shadow-matrix og visuel vurdering af aflevering/målmuligheder.


Integration af ggsoccer og geometri i R.


Jura, GDPR og etik
Hvem ejer fodbolddata? Må data deles offentligt?


Analyse af GDPR i forbindelse med biometrisk data (puls, blodtryk).


Kant vs konsekvensetik i forhold til datafremstilling og manipulation.





