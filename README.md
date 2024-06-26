- Possibilità di scambiare i biglietti (vendere - comprare) per eventi con utenti impossibilitati ad andarci - (utente)
- Visualizzare eventi e cercarli per categoria - (utente)
- Visualizzare eventi passati a cui si ha partecipato - (utente)
- Account e Login - (sistema)
- Personalizzazione Account - (utente)
- Visualizzazione Date, Orari e Luogo (mappa) eventi - (utente)
- Tipologia di eventi preferita preferiti - (utente - sistema)
- Eventi di cui si è in possesso del biglietto sono segnati nel calendario - (utente)

Requisiti:
- connessione a internet
- carta di credito

![Casi d'uso](https://yuml.me/diagram/usecase/[Customer]-(Login),[Logged%20Customer]-(Show%20past%20Event%20where%20Customer%20participated),[Customer]-(Sign%20In),(Sign%20In)%3E(Add%20Card),(Sign%20In)%3E(Verify%20Email),(Sign%20In)%3C(Favourite%20Type%20of%20Event),(Login)%3C(Reset%20Password),[Logged%20Customer]-(Buy%20Ticket),[Logged%20Customer]-(Logout),[Logged%20Customer]-(Change%20Personal%20Information),[Logged%20Customer]-(Research%20Ticket),[Logged%20Customer]-(View%20Ticket),[Logged%20Customer]-(Sell%20Ticket),(Buy%20Ticket)%3C(Add%20Event%20to%20the%20Calendar),(Logout)%3C(Delete%20Account),[Customer]%5E[Logged%20Customer],(Buy%20Ticket)%3E[Bank])

![WBS](Work_Breakdown_Structure.png)

Value Proposition: 
La Tua Sicurezza nell'Acquisto e Scambio di Biglietti

In un mondo in cui gli eventi sono esperienze irripetibili, garantiamo un'esperienza di scambio di biglietti sicura e conveniente. Offriamo un ambiente dedicato al tuo divertimento, assicurandoti la massima sicurezza e risparmiando denaro nel processo.

Sicurezza al Primo Posto:
La tua sicurezza è la nostra priorità. Questa piattaforma implementa rigorosi protocolli di sicurezza per garantire transazioni senza intoppi e proteggere i tuoi dati personali. Puoi scambiare i tuoi biglietti con la tranquillità che solo una piattaforma sicura può offrire.

Prezzi Accessibili:
Il divertimento non dovrebbe costare una fortuna. Ti offriamo la possibilità di acquistare e scambiare biglietti a un prezzo di rivendita inferiore a quello del primo acquisto. Rendiamo gli eventi accessibili a tutti, garantendo che la tua passione non debba pesare troppo sul tuo portafoglio.

Facilità d'Uso:
Abbiamo semplificato il processo di scambio di biglietti, offrendoti un'interfaccia utente intuitiva e transazioni senza complicazioni. Basta pochi clic per vivere l'evento dei tuoi sogni o liberare quei biglietti extra che hai a disposizione.

Il tuo divertimento è al sicuro, accessibile e a portata di mano. Scambia biglietti con fiducia, risparmia denaro e goditi ogni momento senza preoccupazioni. La tua esperienza con noi è tanto memorabile quanto l'evento stesso.

User Stories

User Story: Scambio di Biglietti
Come utente, voglio poter vendere i miei biglietti per eventi a persone che sono interessate ma impossibilitate ad andarci, così da poter recuperare parte del costo del biglietto.

User Story: Visualizzazione Eventi per Categoria
Come utente, desidero poter visualizzare gli eventi disponibili e cercarli per categoria, in modo da trovare facilmente quelli di mio interesse.

User Story: Visualizzazione Eventi Passati
Come utente, voglio poter vedere una lista degli eventi passati a cui ho partecipato, così da poter rivivere quei momenti e rivedere le informazioni correlate.

User Story: Account e Login
Come sistema, voglio garantire un sistema di account e login sicuro per gli utenti, in modo da proteggere le loro informazioni personali.

User Story: Personalizzazione Account
Come utente, voglio poter personalizzare il mio account con informazioni aggiuntive e preferenze personali, migliorando così l'esperienza personalizzata sulla piattaforma.

User Story: Visualizzazione Date, Orari e Luogo degli Eventi
Come utente, desidero poter visualizzare chiaramente le date, gli orari e i luoghi degli eventi, e avere accesso a una mappa per facilitare la pianificazione della partecipazione.

User Story: Tipologia di Eventi Preferita
Come utente, voglio poter selezionare le tipologie di eventi preferite, in modo che la piattaforma possa suggerire automaticamente eventi che potrebbero interessarmi.

User Story: Segnalazione Eventi nel Calendario
Come utente, desidero che gli eventi di cui ho in possesso il biglietto vengano automaticamente segnati nel mio calendario, facilitando così la gestione delle partecipazioni.

Multitenancy
Il mio progetto è già predisposto alla multitenancy, in quanto ogni persona/azienda che vuole mettere in vendita un biglietto può configurare la mia webapp per le sue esigenze specifiche
