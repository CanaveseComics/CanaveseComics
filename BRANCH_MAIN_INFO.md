# Branch: main (Produzione)

Questo branch contiene la versione del sito pubblicata su Netlify
e visibile agli utenti attraverso il dominio ufficiale.

Stato attuale:
- La pagina “Coming Soon” è online tramite Netlify.
- Il dominio e il certificato HTTPS sono correttamente configurati.
- Tutto il codice viene gestito esclusivamente tramite GitHub.

Quando lo sviluppo sarà completato nella repository dedicata,
questa branch verrà aggiornata tramite *merge* dei file finali provenienti dal branch di sviluppo.

---

## Checklist produzione

- [x] Pubblicare la pagina "Coming Soon" su Netlify
- [x] Collegare dominio e certificato HTTPS
- [ ] Eseguire il merge dei file finali provenienti dalla repository di sviluppo
- [ ] Verificare il sito completo sul dominio ufficiale
- [ ] Effettuare controllo finale SEO e performance
- [ ] Effettuare backup del codice finale

---

## Nota importante sull'uso di Netlify

- Non caricare mai file manualmente su Netlify.
- Non utilizzare la funzione "upload manuale" di Netlify.
- Netlify viene utilizzato esclusivamente come piattaforma di hosting e gestione del dominio.
- Tutto il deploy avviene tramite GitHub:  
  → i file vengono aggiornati nel branch `main`  
  → Netlify rileva automaticamente le modifiche e pubblica la versione aggiornata del sito.

---

⚠️ Nota operativa:
Non modificare questa branch durante lo sviluppo.  
Tutte le attività di sviluppo avvengono nella repository dedicata (branch `dev`).
