# Calcolatore Bollette

App che calcola la quota di ciascun inquilino sulla base della bolletta specificata.

## Dettagli
Ecco le variabili considerate dall'applicazione:

* Costi fissi: divisi per il numero di inquilini presenti
* Costi consumo: si riferiscono al consumo effettivo escluse le tasse
* Costi aggiuntivi: i costi per pagare la bolletta (anche in questo caso divisi per numero di inquilini)

## Uso

* Specificare data di inizio e data di fine della bolletta per calcolare numero di giorni
* Specificare i costi
* Indicare il numero di inquilini e selezionare il numero di giorni in cui sono stati presenti in casa.

L'algoritmo terrà in considerazione nel calcolo, non solo il numero di giorni in cui un inquilino è stato in casa, i giorni in cui gli inquilini erano contemporaneamente presenti in casa.

## Avvertenze
L'applicazione non ha lo scopo di essere production-ready, piuttosto è un esercizio per un'app in React.

A tal proposito, l'applicazione non è mobile-friendly per il suddetto motivo.
