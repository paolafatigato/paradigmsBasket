Guida rapida per rendere il sito visibile su Google

1) Verifica il sito su Google Search Console
- Apri https://search.google.com/search-console
- Aggiungi proprietà: `https://paolafatigato.github.io/paradigmsBasket/`
- Scegli verifica tramite "Tag HTML" oppure tramite Google Analytics (se già configurato).
- Se scegli "Tag HTML", copia il meta tag fornito e incollalo dentro la `<head>` di `index.html`.

2) Invia la sitemap
- Dopo la verifica, nella Search Console vai su "Sitemaps" e invia:
  `https://paolafatigato.github.io/paradigmsBasket/sitemap.xml`

3) Google Analytics / GA4
- Crea una proprietà GA4 in https://analytics.google.com
- Prendi il Measurement ID (es. `G-XXXXXXXXXX`) e incollalo nel blocco Analytics in `index.html`, decommentando il codice.

4) Social & condivisione
- Open Graph e Twitter Card sono già inclusi nel `index.html`. Assicurati che `icon.png` sia di buona qualità (1200x630 raccomandato) per anteprime grandi.

5) Migliorare ranking (consigli pratici)
- Scegli un titolo chiaro e una `meta description` descrittiva (già aggiunte).
- Aggiungi contenuti testuali rilevanti sulla homepage (più testo unico aiuta). Considera una sezione "About" con parole chiave legate all'apprendimento di inglese.
- Aggiungi collegamenti (backlinks) da profili social, descrizioni di progetti, forum e pagine scuola.
- Promuovi il sito: condividi su LinkedIn, Instagram, Facebook, TikTok, blog e gruppi di insegnanti.

6) Test e monitoraggio
- Esegui Lighthouse (Chrome DevTools) per performance/accessibilità/SEO.
- Controlla Search Console per errori di indicizzazione e copertura.
- Verifica i risultati della ricerca e aggiorna meta descrizioni per miglior CTR.

7) Note legali e privacy
- Se raccogli dati (es. Analytics), aggiungi una pagina `privacy.html` e linka il banner dei cookie se necessario.

Se vuoi, posso:
- Inserire direttamente il meta tag di verifica se mi fornisci il valore.
- Configurare GA4 inserendo il Measurement ID.
- Generare una immagine social di dimensione 1200x630 per l'anteprima.
