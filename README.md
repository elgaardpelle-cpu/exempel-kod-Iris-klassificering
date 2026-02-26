README

Det här projektet är ett praktiskt AI‑arbete baserat på Iris‑datasetet. Projektet består av tre delar som tillsammans visar hela arbetsprocessen i ett maskininlärningsprojekt, från datavisualisering till modellträning och utvärdering. Koden är skriven i Python och använder bibliotek som scikit‑learn, pandas och matplotlib.

Datavisualisering
I den första delen undersöks datasetet med hjälp av två grafer. Histogrammet visar fördelningen av variabeln petal length och används för att se hur arterna skiljer sig åt i längd på kronblad. Scatter ploten visar sambandet mellan sepal length och petal length och gör det möjligt att se kluster mellan arterna. Dessa visualiseringar motsvarar den del av rapporten där datans struktur analyseras innan modellen tränas.

Träning av Random Forest
I den andra delen delas datan upp i träningsdata och testdata. En Random Forest‑klassificerare tränas på träningsdatan. Modellen valdes eftersom den fungerar bra på små dataset, hanterar både linjära och icke linjära samband och inte kräver skalning av datan. Den här delen motsvarar avsnittet i rapporten där modellvalet motiveras och träningsprocessen beskrivs.

Utvärdering av modellen
Den tredje delen utvärderar modellens prestanda med noggrannhet, precision och recall. En confusion matrix används för att se vilka arter modellen blandar ihop. Feature importance visar vilka variabler som har störst betydelse för klassificeringen. Detta motsvarar den del av rapporten där modellens styrkor och svagheter analyseras.

Sammanfattning
Projektet visar hela arbetsflödet i ett AI‑projekt: först visualiseras datan, sedan tränas modellen och till sist utvärderas resultaten. Detta ger en tydlig och praktisk förståelse för hur maskininlärning fungerar i Python och hur teknisk analys kombineras med reflektion, vilket överensstämmer med texten i inlämningen.
