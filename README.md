# ResellPro — file iniziali

Questa cartella contiene una prima versione statica di ResellPro:
- `index.html`: app responsive con dashboard, inventario, calcolatore e idee.
- `manifest.json`: metadati per l'installazione come web app.
- `sw.js`: cache di base per utilizzo offline dopo il primo caricamento.

## Pubblicazione gratuita con GitHub Pages (da iPhone)
1. Accedi a https://github.com/ e crea un repository pubblico chiamato `resellpro`.
2. Carica i tre file `index.html`, `manifest.json` e `sw.js` nella cartella principale del repository.
3. Nel repository apri **Settings → Pages**.
4. In **Build and deployment**, scegli **Deploy from a branch**; branch `main`, folder `/ (root)`, poi **Save**.
5. Attendi la pubblicazione. L'indirizzo sarà simile a `https://TUONOME.github.io/resellpro/` (sostituisci TUONOME con il tuo nome utente GitHub).
6. Apri l'indirizzo in Safari sul tuo iPhone → pulsante Condividi → **Aggiungi alla schermata Home**.

## Note importanti
- Non è un'app iOS nativa e non è stata inviata all'App Store.
- I dati dell'inventario sono salvati localmente nel browser del dispositivo; non c'è sincronizzazione cloud.
- Non è collegata a Vinted e non importa annunci automaticamente.
- Il file manifest non include icone dedicate: per una PWA rifinita aggiungere icone 192x192 e 512x512.
- Prima di un uso commerciale reale, testare accuratamente e aggiornare privacy, accessibilità e sicurezza.
