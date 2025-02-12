# StockPredictor

## Introduzione

StockPredictor è un progetto di previsione dell'andamento degli stock tramite modello LSTM. Questo notebook contiene il codice necessario allo sviluppo del progetto commentato passo passo.

La documentazione è disponibile in questo repository, nella cartella "documentation".

## Manipolazione dei Dati

Il progetto include la raccolta, la preprocessazione e la normalizzazione dei dati per prepararli al modello LSTM.

## Definizione del Modello

Il progetto definisce e addestra un modello LSTM per prevedere i prezzi delle azioni.

## Valutazione del Modello

Il progetto valuta le prestazioni del modello utilizzando varie metriche e visualizzazioni.

## Utilizzo del Modello

Il progetto include funzioni per prevedere l'andamento degli stock per qualsiasi azione data in input.

## Installazione
Il progetto non offre un modello preaddestrato, sarà necessario addestrarlo prima di utilizzarlo.
Prima di procedere con l'istallazione, assicurati di avere **python ver >= 3.8** scaricato.

Per replicare questo progetto, segui questi passaggi:

1. Clona il repository:
    ```sh
    git clone https://github.com/Ritopla/StockPredictor.git
    cd StockPredictor
    ```

2. Crea un ambiente virtuale e attivalo:
    ```sh
    python -m venv venv
    source venv/bin/activate  # Su Windows, usa `venv\Scripts\activate`
    ```

3. Installa le dipendenze necessarie:
    ```sh
    pip install -r requirements.txt
    ```

4. Esegui il Jupyter Notebook:
    ```sh
    jupyter notebook StockPredictor.ipynb
    ```

## Dipendenze

Il progetto richiede le seguenti dipendenze:
- yfinance
- pandas
- numpy
- matplotlib
- scikit-learn
- keras

Queste dipendenze sono elencate nel file `requirements.txt`.

## Utilizzo

Per utilizzare il modello per prevedere l'andamento degli stock, segui le istruzioni nel notebook [StockPredictor.ipynb](http://_vscodecontentref_/1).
