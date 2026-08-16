# Aggiornamenti — GearHead Customs

Questa repository serve **solo** a far sapere all'applicazione installata
quando esce una versione nuova. Non contiene codice sorgente né segreti.

- `versione.json` — l'ultima versione pubblicata
- **Releases** — gli installer da scaricare

L'app legge `versione.json` ogni minuto. Se il numero è più alto di quello
installato, avvisa l'utente e lo invita ad aggiornare.

È pubblica per un motivo preciso: il codice sta in una repository privata,
e per leggere da lì servirebbe una chiave d'accesso dentro l'applicazione —
cioè regalarla a chiunque la installi. Qui invece c'è solo un numero.
