# Documenti delle convenzioni e degli accordi quadro ICT della PA italiana

Copie dei **documenti pubblici ufficiali** delle convenzioni e degli accordi quadro ICT (Consip, PSN, aggregatori regionali e altri soggetti), raccolte dal progetto [Analisi della spesa ICT](https://analisi-spesa-ict.mxmap.it/convenzioni/) ([sorgente](https://github.com/mxmap-it/analisi-spesa-ict), ticket #62).

## Cosa contiene

- **Una GitHub Release per iniziativa**: tag = identificativo dell'iniziativa nel progetto (es. `consip-2928`, `cig-…`). Gli asset sono i file, con nome leggibile e univoco (prefisso sha256 corto in caso di collisione).
- **`manifest.csv` / `manifest.json`**: una riga per documento con `iniziativa`, `titolo`, `url_originale`, `sha256`, `byte`, `data_acquisizione`, `asset`, `asset_url`.

## Provenienza e integrità

- Ogni file è stato scaricato da una **pagina pubblica ufficiale** (consip.it, acquistinretepa.it, dati.consip.it, TED, piattaforme e siti istituzionali delle amministrazioni) senza autenticazione. L'URL originale è nel manifest: **la fonte autentica resta quella**.
- I file sono identici byte per byte alla copia nell'archivio content-addressed del progetto: lo sha256 nel manifest coincide con il digest dell'asset mostrato da GitHub. Verifica: `sha256sum <file>`.
- Non contiene materiali riservati o interni né documenti reperiti da fonti non ufficiali.

## Diritti

I documenti sono atti e documenti amministrativi pubblicati dalle amministrazioni e dalle centrali di committenza; restano di chi li ha prodotti. Sono ripubblicati come documenti oggetto di pubblicazione obbligatoria, riutilizzabili ai sensi dell'art. 7 del d.lgs. 33/2013 e dell'art. 52 del CAD, citando la fonte. Il manifest e i testi di questo repository sono rilasciati in CC0 1.0 (vedi `LICENSE`).

Segnalazioni (file errato, da rimuovere, aggiornato alla fonte): issue su questo repository.
