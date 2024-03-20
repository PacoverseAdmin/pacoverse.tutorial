# Comandi per le fazioni
Qua saranno presenti tutti (o comunque buona parte) dei comandi utili per giocare correttamente nelle ***factions***!
Mi raccomando, leggere attentamente tutto quanto e se si hanno dei dubbi chiedere pure. Ricordati che esiste ***/f help***!!

## Creazione/gestione fazione
- ***/f create \<nomeFazione\>***: creo una fazione con un certo nome. Alla sua creazione, la fazione *NON AVRA' NESSUN TERRITORIO*! Sarà solo per bellezza.
- ***/f invite \<nomePlayer\>***: invito un giocatore nella mia fazione. Alla sua entrata egli non potrà fare quasi nulla, poiché "recluta".
- ***/f join \<nomeFazione\>***: se sono stato invitato in una fazione, posso accettare l'invito con questo comando.
- ***/f promote \<nomePlayer\>***: promuovo il giocatore prima a "normal", poi a "moderator", poi a "co-leader" e infine a "leader". Ovviamente, ogni categoria gli permetterà di fare cose diverse. Consigliata: *moderator*.
- ***/f demote \<nomePlayer\>***: retrocedo il giocatore alla categoria precedente.
- ***/f tag \<nuovoNome\>***: cambio il nome alla fazione (non sono ammessi colori/formattazione).
- ***/f perm***: apre una GUI di gestione dei permessi per alleati, nemici, neutrali ma anche i vari ranks della tua fazione. Provare per credere.
- ***/f kick \<nomePlayer\>***: mando un player AFUERA dalla mia fazione.
- ***/f ban \<nomePlayer\>***: mando un player AFUERA dalla mia fazione, senza possibilità di reintegro.
- ***/f unban \<nomePlayer\>***: un player precedentemente AFUERATO dalla fazione, può ora essere riammesso.

## Acquisizione e ricerca del territorio
Un breve spiegone: per rendere una fazione qualcosa di più di una "targhetta prima del tuo nickname" è necessario ***claimare*** del territore (dall'inglese "to claim", "rivendicare").
Nel territorio claimato, i giocatori NON facenti parte della tua fazione non potranno costruire, usare pulsanti e redstone ecc... (a meno che tu non abbia modificato a piacimento i permessi della tua fazione, cosa più che lecita).
Ma allora siamo a posto no? Beh, ***no***. Ovviamente esistono modi per griefare la base di un giocatore. Non ve li spiego per filo e per segno qua, sennò si perde il divertimento. Tuttavia basti pensare che una TNT sparata da un
cannone, ad esempio, può entrare in base e fare danni! Ma non solo quello, nello shop (sezione "OP") sono in vendita oggetti interessanti per il griefing. Ah e le uova si possono piazzare nella fazione nemica (questo dovrebbe dire molto).
Tornando a noi:
- ***/f claim***: comando che ***costa 1000€*** e permette di impossessarsi di un chunk. Premendo ***F3 + G*** appariranno i bordi di questi fantomatici chunks (dall'inglese "chunk", "pezzo") che sono pezzi di terra da 16x16 blocchi. Eseguendo il comando li dentro, quel chunk diventerà mio! Se eseguo il comando a cazzo di cane in un chunk già claimato da qualcun'altro o da me, comunque mi verranno scalati 1000€. ***OCCHIO!***
- ***/f unclaim***: un chunk non mi interessa più? Bene, posso togliere il claim con questo comando. *Non verrà rimborsato un cazzo*. Il chunk tornerà ad essere toccabile da tutti! Occhio!
- ***/f unclaimall***: uguale al precedente, con però il simpatico effetto che VALE PER TUTTI I CHUNK CLAIMATI! Se lo si fa, si unclaima tutto! *Non verrà rimborsato un cazzo*.
- ***/f map***: importantissimo! Serve a vedere la mappa dei dintorni e le rispettive fazioni presenti. Utile per cercarle in giro.
- ***/f mapheight \<altezza\>***: regolo il numero di righe stampate in chat quando faccio */f map*.

## Relazioni tra fazioni
Esiste la possibilità di allearsi con una fazione, inimicarsela o addirittura non avere rapporti (quello che è di default). Gli alleati di base non potranno colpirsi tra loro (il tutto modificabile con */f perm*).
Vediamo come impostare queste relazioni e come gestirle:
- ***/f ally \<nomeFazione\>***: rendo quella fazione mia alleata (nome visualizzato in rosa nella */f list*). Richiede conferma dall'altra parte.
- ***/f enemy \<nomeFazione\>***: rendo quella fazione mia nemica (nome visualizzato in rosso nella */f list*).
- ***/f neutral \<nomeFazione\>***: rendo quella fazione neutrale (nome visualizzato in bianco nella */f list*).

Prestare molta attenzione! Se una fazione è tua NEMICA, non potrai utilizzare alcun tipo di comando per scappare al suo interno (come */home*, */warp* o altri). Quindi se si rimane intrappolati, auguri!
Il consiglio è infatti quello di fare ***/f enemy*** quando sai che una fazione ti sta raidando, in modo da non permettere agli altri giocatori di scappare.

## Altro
Comandi sempre factions generici:
- ***/f getvault***: ti da una chest personale (vault) piazzabile e accessibile da ogni player della fazione tramite */f vault*. Costa 5000€!
- ***/f vault***: apre il vault della fazione.
