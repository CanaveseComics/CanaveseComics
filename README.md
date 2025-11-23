# Branch di produzione 

Questo branch conterrá la versione definitiva del sito pubblicata su Github Pages (www.canavesecomics.com).

Stato attuale:
- La pagina placeholder “Coming Soon” è online su Github Pages.
- Il dominio e il certificato HTTPS sono correttamente configurati.
- Tutto il codice viene pushato da un git remote della repo di sviluppo.

Quando lo sviluppo sarà completato nella repository dedicata,
questa branch verrà aggiornata tramite *merge* dei file finali provenienti dal branch di sviluppo.

---

## Checklist produzione

- [x] Pubblicare la pagina placeholder "Coming Soon" su Github Pages con il dominio ufficiale
- [x] Collegare dominio e certificato HTTPS
- [ ] Eseguire il merge dei file finali provenienti dalla repository di sviluppo
- [ ] Verificare il sito completo sul dominio ufficiale
- [ ] Effettuare controllo finale SEO e performance
- [ ] Effettuare backup del codice finale

---

## Nota importante sull'uso di Netlify

- Non caricare mai file manualmente su Netlify.
- Netlify viene utilizzato esclusivamente come piattaforma per la gestione del dominio.
- Tutto il deploy del codice frontend avviene tramite GitHub.


  
## Nota importante sull'uso di Cloudlfare 

- Cloudflare viene utilizzato unicamente come backend e per gestire il DB.
- tutto il deploy del codice backend avviene su Cloudlflare.
  

---

⚠️ Nota operativa:
Non modificare questa branch durante lo sviluppo. I test avvengono su un'altra repo di sviluppo.
