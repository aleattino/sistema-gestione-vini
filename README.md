# Wine management system (SGE) - analisi e applicazione web

## Obiettivo del progetto

Questo progetto è un **Sistema di gestione elementi (SGE)** applicato al settore vinicolo, con un focus specifico sull'analisi e la catalogazione dei vini in base alla loro etichetta **Vegan Friendly / Not Vegan Friendly**.

L'obiettivo principale è sviluppare un'infrastruttura Python per l'analisi e l'estrazione di statistiche sul database dei vini, dimostrando competenze di programmazione e manipolazione dei dati.

---

## Tecnologie e competenze

Questo progetto dimostra competenze in:

| Area | Strumenti e tecnologie | Competenze dimostrate |
| :--- | :--- | :--- |
| **Data analysis** | Python (Jupyter Notebook, Classi, Funzioni) | Programmazione orientata agli oggetti (OOP), logica di ricerca e filtraggio dati. |
| **Data cleaning** | Gestione dell'input file CSV, validazione dei dati (es. paesi validi). | Robustezza del codice e preparazione dei dati per l'uso applicativo. |

## Analisi e funzionalità chiave

Il cuore del sistema risiede nella classe Python `SistemaGestioneVini`, che gestisce il database (ottenuto tramite scraping del progetto Barnivore) e implementa le seguenti funzionalità:

1.  **Ricerca avanzata:** Ricerca per nome, produttore e stato.
2.  **Ricerca incrociata:** Filtraggio combinato per nome, stato e l'etichetta Vegan Friendly.
3.  **Statistiche:**
    *   Analisi dettagliata sulla distribuzione dei vini vegani per paese.
    *   Identificazione dei produttori che si dedicano esclusivamente alla produzione di vini vegan friendly.
    *   Calcolo delle percentuali di vini vegani/non vegani per stato.
4.  **Gestione file:** Implementazione di una funzione `seleziona_file()` robusta per la compatibilità sia in ambiente locale e cloud.

## Struttura del repository

*   `barnivore_new.csv`: Dataset utilizzato per l'analisi.
*   `gestione_vini.ipynb`: Il notebook Jupyter che contiene il codice Python completo del sistema e le spiegazioni.
*   `README.md`: Questo documento.
