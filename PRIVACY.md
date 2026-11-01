# Informativa sulla privacy di OBDTool

Ultimo aggiornamento: 1 novembre 2026

**OBDTool non ha account, pubblicità né statistiche d'uso.** I dati della tua auto restano sul telefono.

- **Dati dell'auto**: OBDTool legge dall'adattatore OBD i dati standard (codici errore, valori del motore, numero di telaio VIN, protocollo). Li mostra solo sullo schermo: non li salva e non li invia a nessuno.
- **Bluetooth e Wi-Fi**: servono solo per parlare con l'adattatore. OBDTool cerca i dispositivi Bluetooth vicini solo quando tocchi «Cerca adattatori» e non usa la tua posizione (su Android 11 e precedenti Android chiede comunque il permesso di posizione per la ricerca Bluetooth).
- **Cerca un codice**: il pulsante «Cerca» apre il browser con una ricerca del codice errore; da lì valgono le regole del motore di ricerca.
- **Aggiornamenti**: a ogni apertura dell'app, al massimo ogni 15 minuti, OBDTool controlla su GitHub se c'è una versione nuova (la versione di Google Play riceve gli aggiornamenti da Google Play). GitHub vede l'indirizzo IP della richiesta, come per qualsiasi pagina web.
- **Permessi**: Bluetooth (cerca e collega l'adattatore), Internet e stato della rete (adattatori Wi-Fi, aggiornamenti, rapporti), posizione solo su Android 11 e precedenti (richiesta da Android per la ricerca Bluetooth), installazione di app solo nella versione scaricata da GitHub, per installare gli aggiornamenti che accetti.
- **Rapporti per migliorare OBDTool** (solo se rispondi "Sì, invia" alla domanda del primo avvio; si spengono quando vuoi in *Impostazioni › Invia rapporti anonimi*, e spegnendoli si cancellano anche quelli non ancora partiti):
  - *quando*: dopo ogni collegamento con l'adattatore e dopo una chiusura improvvisa dell'app;
  - *cosa contengono*: modello del telefono, versione di Android, processore, versione di OBDTool, un codice casuale dell'installazione (non legato a te: cambia se cancelli i dati dell'app), tipo di collegamento (Bluetooth, Bluetooth LE, Wi-Fi), modello dell'adattatore come lo dichiara l'adattatore stesso, protocollo dell'auto, numero di dati supportati, esito, fase in cui si è fermato, tempi, eventuali errori e il punto del codice in cui sono successi;
  - *cosa non contengono mai*: numero di telaio (VIN), codici errore e valori della tua auto, nomi e indirizzi dei dispositivi Bluetooth, indirizzi IP, posizione, account o numero di telefono;
  - *come viaggiano*: il rapporto viene cifrato sul telefono (AES-256-GCM con una chiave RSA a 3072 bit) prima di partire; passa da un piccolo servizio su Cloudflare, che non lo può leggere e non salva l'indirizzo IP, e finisce in un archivio privato su GitHub. Lo può aprire solo lo sviluppatore di OBDTool;
  - *quanto restano*: il tempo necessario a correggere i problemi; non vengono venduti né condivisi con nessuno;
  - l'ultimo rapporto preparato si può leggere nel telefono, in *Impostazioni › Mostra l'ultimo rapporto*.

Per domande: [apri una segnalazione](https://github.com/vincenzociriello91-hub/OBDTool-download/issues).
