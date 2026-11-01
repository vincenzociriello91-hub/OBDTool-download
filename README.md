# OBDTool

**La diagnostica della tua auto sul telefono.** Inserisci un adattatore OBD-II (ELM327 e compatibili: cloni economici, OBDLink, Vgate…) nella presa OBD dell'auto e collegalo al telefono via **Bluetooth, Bluetooth LE o Wi-Fi**: OBDTool riconosce da solo il protocollo dell'auto e ti mostra codici errore e dati del motore in tempo reale.

Gratis, senza pubblicità, senza account ([informativa](PRIVACY.md)).

## Scarica e installa

1. Dal telefono apri **[l'ultima versione](https://github.com/vincenzociriello91-hub/OBDTool-download/releases/latest)** e tocca `OBDTool-X.Y.Z.apk`.
2. Apri il file scaricato. La prima volta Android chiede di consentire l'installazione da questa fonte: consentila.
3. Serve Android 10 o successivo.

**Aggiornamenti:** ogni volta che apri OBDTool o ci torni (al massimo ogni 15 minuti) controlla se c'è una versione nuova: te lo dice da solo, ti mostra le novità e, se vuoi, la installa **sopra** quella che hai. Le novità di ogni versione sono in [NOVITA.md](NOVITA.md) e nella pagina Novità dell'app.

## Come si collega

- **Bluetooth classico** (gli adattatori più diffusi): associa prima l'adattatore nelle impostazioni Bluetooth del telefono (PIN 1234 o 0000), poi in OBDTool tocca «Cerca adattatori» e sceglilo.
- **Bluetooth LE** (molti adattatori recenti, compatibili anche con iPhone): non serve associarlo, compare nella ricerca.
- **Wi-Fi**: collega il telefono alla rete Wi-Fi dell'adattatore (di solito `WiFi_OBDII`), poi in OBDTool scegli Wi-Fi e tocca Connetti (indirizzo di solito 192.168.0.10, porta 35000).

Prima di collegarti gira la chiave su ON o avvia il motore.

## Cosa fa

- **Codici errore**: legge quelli memorizzati e quelli in attesa, ti dice in italiano cosa significano (l'elenco si aggiorna da solo, senza installare niente) e a quale impianto si riferiscono (motore, telaio, carrozzeria, rete) e li cerca sul web con un tocco. Puoi anche cancellarli e spegnere la spia motore.
- **Dati in tempo reale**: giri, velocità, temperature di liquido, olio e aria, carico, acceleratore, flusso d'aria, livello del carburante, tensione della batteria. Solo quelli che la tua auto supporta.
- **Info auto**: numero di telaio (VIN), protocollo e modello dell'adattatore.
- **Universale**: tutti i protocolli OBD-II (CAN, KWP2000, ISO 9141, J1850). In Europa l'OBD è obbligatorio sulle auto a benzina dal 2001 e diesel dal 2004.
- **Rapporti anonimi, solo se vuoi**: al primo avvio OBDTool chiede se può inviare rapporti tecnici sui collegamenti per diventare compatibile con sempre più adattatori; si spengono quando vuoi nelle Impostazioni.

## Suggerimenti e problemi

Dall'app: Impostazioni › **Suggerimenti e problemi**, oppure [apri una segnalazione](https://github.com/vincenzociriello91-hub/OBDTool-download/issues/new?template=suggerimento.yml). Se un adattatore non funziona, scrivi il suo nome e il modello dell'auto.

## Informazioni

- [Informativa sulla privacy](PRIVACY.md)
- OBDTool legge solo i dati OBD standard e cancella i codici errore solo quando lo confermi. Non modifica la centralina. Usalo a motore spento o da fermo, non mentre guidi.
- © 2026 Vincenzo Ciriello. **Tutti i diritti riservati** ([LICENSE](LICENSE)). Questo repository contiene solo l'app compilata: il codice sorgente non è pubblico.
