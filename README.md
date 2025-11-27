# **TesiMagistrale-AnalisiStatistica-Automotive**

Questo repository contiene il materiale sviluppato per la tesi magistrale:

“Analisi sperimentale delle relazioni tra fattori gestionali e indicatori di performance in un’azienda manifatturiera del settore automotive.”

L’obiettivo del lavoro è valutare, attraverso tecniche statistiche descrittive e inferenziali, se esistano relazioni significative tra alcune metriche organizzative/gestionali e i principali KPI aziendali (qualità, sicurezza, persone, costi e delivery).

Il dataset utilizzato è completamente sintetico, generato tramite Kernel Density Estimation (KDE) a partire da dati reali ma non sensibili, nel pieno rispetto delle policy aziendali.

📂 Contenuto del repository

Dataset sintetico: generato a partire da valori realistici ma non sensibili, tramite Kernel Density Estimation (KDE) e fitting statistico.
La procedura consente di riprodurre le distribuzioni originali mantenendo coerenza temporale e struttura delle variabili, senza includere dati riservati.

Notebook di analisi: illustra le principali fasi del lavoro:

- Anonimizzazione delle entità e delle metriche;

- Calcolo di statistiche descrittive (media, varianza, distribuzioni);

- Generazione del dataset sintetico tramite KDE;

- Analisi statistica (correlazioni, regressioni, test robusti).

🔁 Come replicare l’analisi

1. Clonare o scaricare il repository: 
git clone https://github.com/mirco2001/TesiMagistrale-AnalisiStatistica-Automotive.git
cd TesiMagistrale-AnalisiStatistica-Automotive

2. Installare le dipendenze
Assicurarsi di avere Python ≥ 3.9 installato, poi eseguire: pip install -r requirements.txt

3. Caricare il dataset sintetico e avviare le successive celle
Nel notebook principale è sufficiente eseguire la cella che permette l'import del dataset.

4. Riproduzione completa dei risultati
Eseguendo l’intero notebook è possibile ricostruire tutte le analisi e le figure incluse nella tesi, garantendo completa replicabilità del lavoro.

⚙️ Note metodologiche

Il dataset originale non è incluso per ragioni di policy aziendale.
Tutte le analisi riportate nella tesi sono state condotte utilizzando esclusivamente il dataset sintetico
