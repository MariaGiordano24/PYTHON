# 🦠 Analisi Diffusione COVID-19

Progetto finale del modulo **Data Analysis con Python** — Epicode. 
Analisi esplorativa su casi, ricoveri e vaccinazioni COVID-19 a livello mondiale, utilizzando il dataset pubblico curato da [Our World in Data](https://github.com/owid/covid-19-data/tree/master/public/data).

---

## 📋 Descrizione del progetto

Il progetto simula una richiesta da parte di un committente che necessita di un **report su casi e vaccinazioni in diverse aree del mondo**.  
L'analisi è stata condotta interamente in Python tramite JupyterLab, utilizzando il dataset OWID aggiornato.

---

## 🔍 Analisi svolte

### 1. Esplorazione del dataset
Verifica delle dimensioni del dataset e dei relativi metadati (colonne, tipi di dato, valori nulli).

### 2. Casi per continente
- Calcolo del numero totale di casi dall'inizio della pandemia per ogni continente.
- Calcolo della percentuale di ogni continente rispetto al totale mondiale.

### 3. Analisi Italia 2022
Selezione e filtraggio dei dati relativi all'Italia nel 2022 (solo le righe con misurazioni settimanali effettive), con visualizzazione tramite grafici di:
- **Evoluzione dei casi totali** dall'inizio alla fine dell'anno.
- **Nuovi casi settimanali** nel corso del 2022.

### 4. Terapia intensiva — Italia, Germania, Francia (mag 2022 – apr 2023)
- Boxplot comparativo sul numero di pazienti in terapia intensiva (`icu_patients`) per le tre nazioni nel periodo indicato.
- Commento interpretativo sui risultati del grafico.

### 5. Pazienti ospedalizzati — Italia, Germania, Francia, Spagna (2021)
- Calcolo della somma totale dei pazienti ospedalizzati (`hosp_patients`) per ciascuna nazione nel corso del 2021.
- Analisi e commento sulla gestione degli eventuali valori nulli presenti.

---

## 🛠️ Tecnologie utilizzate

| Strumento | Utilizzo |
|---|---|
| Python  | Linguaggio principale |
| Pandas | Manipolazione e analisi dei dati |
| Matplotlib / Seaborn | Visualizzazione grafica |
| JupyterLab | Ambiente di sviluppo |

---

## 📊 Dataset

- **Fonte:** [Our World in Data — COVID-19 Dataset](https://github.com/owid/covid-19-data/tree/master/public/data)
- **Formato:** CSV

---

## 📁 Note

Nella repository sono presenti anche altri esercizi svolti durante il modulo, utilizzati come pratica per consolidare le competenze di analisi dati.

---

## 👤 Autore
Maria Giordano

