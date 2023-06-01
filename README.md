# Analisi del Dataset del Poker Hand

Il notebook fornisce informazioni sull'analisi del dataset del Poker Hand. Il dataset contiene informazioni sulle mani di poker e può essere utilizzato per l'apprendimento automatico e l'analisi statistica.

## Descrizione del Dataset
Il dataset del Poker Hand contiene un insieme di 1 milione di istanze di mani di poker generate casualmente. Ogni istanza rappresenta una mano di poker a cinque carte e contiene 10 attributi numerici (valori interi) che descrivono la mano.

Gli attributi presenti nel dataset sono i seguenti:

* S1 (Suit 1-4): rappresenta il seme della carta 1 (1: cuori, 2: quadri, 3: fiori, 4: picche)
* C1 (Rank 1-13): rappresenta il valore o il rango della carta 1 (dove 1 rappresenta l'asso e 13 rappresenta il re)
* S2 (Suit 1-4): rappresenta il seme della carta 2
* C2 (Rank 1-13): rappresenta il valore o il rango della carta 2
* S3 (Suit 1-4): rappresenta il seme della carta 3
* C3 (Rank 1-13): rappresenta il valore o il rango della carta 3
* S4 (Suit 1-4): rappresenta il seme della carta 4
* C4 (Rank 1-13): rappresenta il valore o il rango della carta 4
* S5 (Suit 1-4): rappresenta il seme della carta 5
* C5 (Rank 1-13): rappresenta il valore o il rango della carta 5
* CLASS: rappresenta la classificazione della mano di poker (0-9)

Le classi (CLASS) rappresentano le diverse combinazioni di mani di poker, come ad esempio una coppia, un tris, un full, un colore, ecc. La classe 0 rappresenta la combinazione di mano più debole, mentre la classe 9 rappresenta la combinazione di mano più forte.

## Utilizzo del Dataset
Il dataset del Poker Hand è stato utilizzato per vari scopi, tra cui:

* analisi statistica dei dati
* task di classificazione
* task di clustering


## Formato del Dataset
Il dataset è fornito in formato CSV (Comma-Separated Values). Ogni riga rappresenta un'istanza separata e i valori sono separati da virgole. Il file CSV contiene un'intestazione che descrive gli attributi.

## Riferimenti
Il dataset del Poker Hand è stato creato da Robert Cattral e può essere scaricato dal repository UCI Machine Learning [link](https://archivehttps://archive.ics.uci.edu/ml/datasets/Poker+Hand)
