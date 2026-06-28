# AGENTS.md

## Progetto

Questo repository contiene la landing statica per promuovere Due Time durante un evento, tramite un concorso a premi legato al punteggio di un mini-gioco interno all'app.

Il concorso e sponsorizzato da Cutowl. La pagina deve valorizzare anche Cutowl come sponsor, mantenendo coerenza con il sito https://www.cutowl.com/.

Leggere sempre `docs/project-brief.md` e `docs/approval-workflow.md` prima di progettare o modificare la landing.

## Obiettivo della pagina

La pagina deve convincere una persona presente all'evento a:

1. capire subito che c'e una gara;
2. scaricare/provare Due Time;
3. giocare;
4. puntare alla top 3 della classifica.

## Riferimenti visivi e funzionali

Usare come riferimenti:

- Landing promo gara: https://due-time-gara.netlify.app/gara.html
- Landing ufficiale Due Time: https://www.cutowl.com/due-time-landing/index.html
- Classifica: https://splendid-longma-5b2da5.netlify.app/
- Sito Cutowl: https://www.cutowl.com/

La nuova landing deve essere piu engaging della promo gara attuale, ma restare coerente con il brand della landing ufficiale.

## Direzione UX

- Mobile-first.
- Hero immediata, con CTA e QR sopra la piega quando possibile.
- Struttura breve: hero, come funziona, premi, classifica, CTA finale.
- La competizione deve essere evidente: podio, punteggio, top 3, classifica.
- Evitare sezioni marketing generiche: questa e una pagina evento/concorso, non una homepage prodotto.

## Direzione visuale

- Mondo Due Time: cielo, prato, nuvole, pecore, tono morbido.
- Aggiungere energia da gara: podio, medaglie, badge, punteggi, stelle, movimento.
- Presenza Cutowl: logo e stile editoriale/sponsor riconoscibile, senza oscurare Due Time.
- Palette coerente con Due Time: verde, azzurro cielo, bianco, accenti giallo/oro per premi.
- Non creare una pagina scura o aggressiva.
- Non usare layout da SaaS corporate.
- Limitare molto le emoji: usare asset, icone e illustrazioni al loro posto.

## Copy

- Lingua: italiano.
- Tono: giocoso, chiaro, da evento live.
- Frasi corte.
- CTA esplicite.
- Evitare spiegazioni lunghe e testi tecnici.

## Asset

- Salvare asset locali in `assets/`.
- Preferire asset coerenti con la landing ufficiale se disponibili.
- Per nuovi asset bitmap, usare generazione immagini solo quando serve un visual ricco o originale.
- Non lasciare asset usati dalla pagina fuori dal repository/progetto locale.

## Implementazione

- Usare Astro come framework del progetto.
- Il deploy finale e previsto su Cloudflare.
- Preferire pagine Astro semplici, componenti piccoli e CSS scoped/global ben organizzato.
- File/cartelle attese in un progetto Astro:
  - `src/pages/index.astro`
  - `src/components/` se servono componenti riusabili
  - `src/styles/` se serve CSS condiviso
  - `public/assets/` per asset statici serviti direttamente
- Mantenere il codice semplice e deployabile su Cloudflare.
- Configurare Astro in modo statico quando possibile; usare adapter Cloudflare solo se richiesto dal tipo di deploy scelto.
- Usare dimensioni responsive stabili per evitare salti di layout.
- Verificare mobile e desktop prima di considerare la pagina pronta.
- Prima del rilascio eseguire build locale Astro.

## Workflow di approvazione

Seguire il workflow in `docs/approval-workflow.md`.

Non partire direttamente con codice o asset definitivi prima di aver ricevuto approvazione su:

1. direzione creativa;
2. copy principale;
3. wireframe rapido.

## Link da confermare prima del rilascio

- Link installazione app/TestFlight.
- Link classifica live.
- Link eventuale regolamento.
- Premi reali e testi definitivi.
