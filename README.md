📊 Stock Price Prediction con Sentiment Analysis

Questo progetto è stato sviluppato nell’ambito del Master in Data Science, Big Data & Artificial Intelligence per la Finanza (2023)- 24 Ore Buisness School.
L’obiettivo è prevedere i prezzi azionari combinando dati storici di mercato con la sentiment analysis dei tweet.

👥 Team
Michela Minniti
Chiara Boris
Nicola Savastio

🎯 Obiettivo
Analizzare la correlazione tra tweet e prezzi di borsa.
Costruire un modello predittivo che utilizzi sia dati di mercato che indicatori di sentiment.
Testare diversi algoritmi di Machine Learning.

🛠️ Metodologia
Raccolta e pulizia dati
Stock data: 2012–2017
Tweet data: 2014–2016
Pre-processing testo (slang, emoji, caratteri speciali, ecc.)
Sentiment Analysis
Classificazione dei tweet come positivo, neutrale o negativo.
Feature Engineering
Creazione variabili a partire dai tweet e dai prezzi storici.
Modellazione
Algoritmo scelto: Regressione Lineare
Train/Test split (80/20)
Metriche di valutazione: MSE, MAE
Visualizzazione
Confronto tra prezzi reali e predizioni.

📈 Risultati
Il modello mostra una buona capacità di adattamento con MSE basso.
Si osserva correlazione tra andamento dei prezzi e sentiment (positivo/negativo).
Le performance sono migliori in scenari con bassa volatilità.

💡 Possibili sviluppi
Replicare il modello su altri stock.
Testare algoritmi più complessi (XGBoost, Reti Neurali).
Migliorare la gestione dei tweet mancanti (es. imputazione media, clustering).
Estendere l’analisi a periodi temporali differenti.
