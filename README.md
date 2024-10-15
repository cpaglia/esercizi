# esercizi
1 - Scrivi un programma che legga una sequenza di spese giornaliere per i trasporti e il pranzo per ogni giorno di una settimana lavorativa (dal lunedì al venerdì).

Quando l'utente inserisce -1 per i trasporti o 0 per il pranzo, il programma smette di leggere le spese per quel giorno e passa al giorno successivo. 
Al termine di ogni giorno visualizzare il totale delle spese sostenute distinte per trasporti e pranzo.
Al termine della settimana, il programma calcola e stampa:
    La spesa totale per i trasporti.
    La media delle spese valide per il pranzo.

2 -Scrivi un programma che calcoli l'impronta ecologica di una persona in base ai suoi consumi settimanali. L'impronta ecologica misura l'impatto che le attività umane hanno sull'ambiente, come il consumo di risorse e la produzione di emissioni di CO2.

Il programma deve chiedere all'utente di inserire i dati relativi ai consumi settimanali per tre categorie:

    Alimentazione: inserisci il numero di kg di carne consumati nella settimana. Considera validi solo i valori compresi tra 0 e 7 kg.
    Trasporti: inserisci il numero di km percorsi in auto durante la settimana. Considera validi solo i valori compresi tra 0 e 500 km.
    Energia: inserisci il numero di kWh di energia elettrica utilizzati nella settimana. Considera validi solo i valori compresi tra 0 e 100 kWh.

Il programma deve calcolare l'impronta ecologica totale della persona utilizzando le seguenti formule:

    Impatto alimentare: kg_di_carne * 50 (dove 1 kg di carne consumata genera un impatto di 50 punti).
    Impatto dei trasporti: km_auto * 0.2 (dove 1 km percorso in auto genera un impatto di 0.2 punti).
    Impatto energetico: kWh * 1.5 (dove 1 kWh di energia consumata genera un impatto di 1.5 punti).

Alla fine, il programma deve stampare:

    L'impronta ecologica totale della settimana.
    L'impronta media per ciascuna delle tre categorie.
    Un messaggio che indichi se l'impronta ecologica totale supera 500 punti, suggerendo quindi un alto impatto ambientale.

