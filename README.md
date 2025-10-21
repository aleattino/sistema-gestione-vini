# Wine management system (SGE) - analisi e applicazione web

## Obiettivo del progetto

Questo progetto è un **Sistema di gestione elementi (SGE)** applicato al settore vinicolo, con un focus specifico sull'analisi e la catalogazione dei vini.

L'obiettivo principale è duplice:
1.  **Analisi dati:** Sviluppare un'infrastruttura Python per l'analisi e l'estrazione di statistiche sul database dei vini.
2.  **Implementazione applicativa:** Trasformare l'analisi in un'applicazione web interattiva per la consultazione e la ricerca avanzata, dimostrando la capacità di portare un progetto *end-to-end* (dall'analisi al prodotto).

---

## Risultato finale: applicazione web interattiva

L'intero sistema di gestione e i dati analizzati sono stati concretizzati in una **Applicazione web (frontend)** sviluppata in **React**.

**Visualizza l'applicazione live qui:**
[https://aleattino.github.io/gestione-vini-v2/](https://aleattino.github.io/gestione-vini-v2/)

---

## Tecnologie e competenze

Questo progetto dimostra competenze in:

| Area | Strumenti e tecnologie | Competenze dimostrate |
| :--- | :--- | :--- |
| **Data analysis** | Python (Jupyter Notebook, Programmazione Orientata agli Oggetti) | Programmazione strutturata (OOP), logica di ricerca e filtraggio dati. |
| **Data cleaning** | Gestione dell'input file CSV, validazione dei dati. | Robustezza del codice e preparazione dei dati per l'uso applicativo. |
| **Frontend/Web** | React, JavaScript, HTML/CSS (nel repository `gestione-vini-v2`) | Capacità di integrare l'analisi dati in un prodotto finale interattivo. |

## Analisi e funzionalità chiave (backend python)

Il cuore del sistema risiede nella classe Python `SistemaGestioneVini`, che gestisce il database (ottenuto tramite scraping del progetto Barnivore) e implementa le seguenti funzionalità:

1.  **Ricerca avanzata:** Ricerca per nome, produttore e stato.
2.  **Ricerca incrociata:** Filtraggio combinato per nome, stato e l'etichetta Vegan Friendly.
3.  **Statistiche:**
    *   Analisi dettagliata sulla distribuzione dei vini vegani per paese.
    *   Identificazione dei produttori che si dedicano esclusivamente alla produzione di vini vegan friendly.
    *   Calcolo delle percentuali di vini vegani/non vegani per stato.
4.  **Gestione file:** Implementazione di una funzione `seleziona_file()` robusta per la compatibilità sia in ambiente locale che in Google Colab.

## Repository correlato

Il codice sorgente dell'applicazione web (frontend) che utilizza i dati gestiti da questo sistema è disponibile qui:
*   [aleattino/gestione-vini-v2](https://github.com/aleattino/gestione-vini-v2)

## Struttura del repository

*   `barnivore_new.csv`: Dataset utilizzato per l'analisi.
*   `gestione_vini.ipynb`: Il notebook Jupyter che contiene il codice Python completo del sistema e le spiegazioni.
*   `README.md`: Questo documento.
