# Due Time Challenge Landing

Landing per promuovere Due Time durante un evento, con concorso a premi basato sul punteggio del gioco Dui Saves the Flock.

Il concorso e sponsorizzato da Cutowl.

## Stato

Il progetto contiene:

- brief e workflow di approvazione in `docs/`;
- wireframe HTML approvato;
- anteprima HTML con asset reali;
- asset Due Time e Cutowl in `public/assets/`.
- prima versione Astro in `src/`.

Il prossimo step e la review visiva della versione Astro e la sostituzione dei placeholder con link, QR e premi definitivi.

## Sviluppo Astro

Installazione:

```bash
npm install
```

Dev server:

```bash
npm run dev
```

Build:

```bash
npm run build
```

Preview build:

```bash
npm run preview
```

Deploy Cloudflare Pages:

```bash
npm run deploy
```

Richiede Wrangler autenticato oppure `CLOUDFLARE_API_TOKEN`.

## Preview documentali

Con un server statico dalla root del progetto:

```bash
python3 -m http.server 4321
```

Pagine:

- `http://localhost:4321/docs/wireframe.html`
- `http://localhost:4321/docs/asset-preview.html`
