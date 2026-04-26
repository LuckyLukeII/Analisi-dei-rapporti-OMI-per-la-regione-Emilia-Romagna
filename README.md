# Analisi dei rapporti OMI — Emilia-Romagna

Analisi dei dati immobiliari pubblici dell'Agenzia delle Entrate (primo semestre 2019 — secondo semestre 2025) per la regione Emilia-Romagna.

## Obiettivo
Esercitarsi con Pandas, NumPy e Matplotlib su dati reali, esplorando l'andamento del mercato immobiliare residenziale in Emilia-Romagna negli ultimi 7 anni.

## Dataset
Dati OMI scaricati dal portale dell'Agenzia delle Entrate, aggregati e puliti in un dataset da oltre 130.000 righe. 
Analisi limitata alle abitazioni civili in stato normale.

## Analisi principali
  1. Prezzo medio nei principali comuni dell'Emilia-Romagna;
  2. Confronto prezzi tra tutti i comuni della provincia di Ravenna;
  3. Confronto prezzi tra le zone del comune di Bologna;
  4. Andamento e differenze tra la provincia di Bologna e Ravenna.

Ad esempio questo grafico mostra le differenze tra i prezzi medi di Bologna per abitazioni civili e ville. 
<img width="1579" height="593" alt="Bologna-Ravenna" src="https://github.com/user-attachments/assets/73dcb967-61fe-497a-bf17-0f2923d172d8" />
Bologna-Ravenna Possiamo vedere come le ville e le villette hanno negli anni avuto entrambe un aumento di prezzi, ma il costo relativo tra Bologna e Ravenna è rimasto più o meno uguale, cosa non vera per le abitazioni civili, che sono cresciute di più a Bologna rispetto che a Ravenna.

## Come eseguire
  -scaricare dall'OMI i dati relativi agli anni dal 2019 al 2025
  
  -pip install pandas numpy matplotlib
  
  -Apri analisi.ipynb con VS Code o Jupyter
