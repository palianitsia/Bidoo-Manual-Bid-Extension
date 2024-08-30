Manifesto dell'estensione:

L'estensione si chiama "Bidoo Manual Bid Extension" e la sua versione è 1.0.
È configurata per funzionare su qualsiasi pagina del dominio it.bidoo.com.
Include permessi per interagire con le schede attive e per memorizzare dati localmente.
Popup HTML e JS:

L'interfaccia utente dell'estensione (popup.html) è molto semplice, con solo un titolo che dice "Bidoo Extension" e una breve descrizione che informa l'utente che l'estensione funziona automaticamente quando si visita una pagina d'asta su it.bidoo.com.
Il file popup.js non contiene codice aggiuntivo, il che suggerisce che non ci sono interazioni dirette richieste dall'utente tramite l'interfaccia popup.
Script di background:

Il file background.js controlla se l'utente sta visualizzando una pagina d'asta (verificando se l'URL contiene una stringa specifica).
Quando rileva che una pagina d'asta è completamente caricata, invia un messaggio per attivare le funzioni specifiche dell'estensione sulla pagina stessa.
Script di contenuto:

Il file content.js contiene le funzioni che interagiscono direttamente con la pagina d'asta.
Simula il movimento del mouse verso il pulsante di offerta e lo clicca automaticamente quando il timer dell'asta arriva a zero.
Controlla regolarmente se l'utente ha ancora crediti per fare offerte o se l'asta è terminata, interrompendo le azioni automatiche in caso negativo.
