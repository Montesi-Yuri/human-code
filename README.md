# human-code

Fare la spesa seguendo una lista

"Fatti mandare dalla mamma a prendere il latte"

Nel frigo si inizia a sentire l’eco, perciò è ora di fare rifornimenti!
Visto che dimentico sempre qualcosa, decido di appuntarmi tutto ciò che manca in una lista, così una volta al supermercato, girando tra gli scaffali, posso verificare di aver preso tutto e Ricky non rimane senza crocchette come l’ultima volta, povero! Devo ricordarmi di usare il coupon che scade a fine mese, per il resto dovrebbero bastarmi i contanti che ho in portafogli, sempre se non mi faccio prendere la mano con gli snack extra! 



0- Inizio

1- Controllo cosa manca nel frigo
    a. SE pieno (vado a FINE) 
    b. ALTRIMENTI vuoto (vado a punto 2)    
   
2- Scrivo una lista dei prodotti mancanti sullo smartphone
	a. SE lo smartphone è scarico (scrivo la lista su carta con una penna)
				c. SE possiedo carta e penna funzionante -> (vado al punto 3)
				d. ALTRIMENTI non possiedo carta e penna funzionante -> (vado a FINE)

	b. ALTRIMENTI lo smartphone è carico (vado a punto 3)

3- Vado al supermercato più vicino con la lista
	a. SE il supermercato è aperto (vado al punto 4)
	b. ALTRIMENTI il supermercato non è aperto (vado al supermercato più vicino in cui non sono già stato)
				c. SE il supermercato è aperto -> (vado al punto 4)
				d. ALTRIMENTI il supermercato non è aperto -> (vado al punto 3b)
								e. SE ho controllato tutti i supermercati vicino a me e nessun supermercato in cui sono già stato è aperto -> (vado a fine)

4- Prendo il carrello (ne prendo un altro se uno è pieno)
	a. SE il carrello è presente (vado al punto 5)
	b. ALTRIMENTI il carrello è assente (vado a prendere un cestino) 
				c. SE il cestino è presente (vado al punto 5)
				d. ALTRIMENTI il cestino è assente -> (vado a prendere una busta in vendita per contenere i prodotti)
								e. SE la busta è presente (vado al punto 5)
								f. SE la busta non è presente (vado a FINE)

5- Seguendo la lista recupero i prodotti uno alla volta spuntando i prodotti messi nel "contenitore" (partendo da dove ero rimasto)
    a. SE il prodotto è presente nel supermercato -> (vado al punto 6)
				c. SE il "contenitore" è pieno -> (vado al punto 4)
				d. ALTRIMENTI il "contenitore" non è pieno -> (vado al punto 6)

    b. ALTRIMENTI il prodotto non è presente nel supermercato (vado al punto 6c/d)

6- Aggiungo al "contenitore" 
    a. SE il contenitore è pieno -> ( vado al punto 4)
    b. ALTRIMENTI il contenitore non è pieno -> (vado al punto 6c/d)
                c. SE ho completato la lista (vado al punto 7)
	            d. ALTRIMENTI non ho completato la lista (vado al punto 5)

7- Compro snack extra
	a. SE gli snack sono presenti (vado al punto 8)
	b. ALTRIMENTI gli snack non sono presenti (vado al punto 8)

8- Vado alla cassa ed utilizzo il coupon

9- Pago
	a. SE mi bastano i contanti ed il coupon per pagare -> (vado a FINE)
	b. ALTRIMENTI non mi bastano i contanti ed il coupon per pagare -> (vado a riporre un oggetto (affinchè riesca a pagare il totale)) -> (vado al punto 9)
									
10- Fine
