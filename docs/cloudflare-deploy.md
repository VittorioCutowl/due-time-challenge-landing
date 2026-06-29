# Cloudflare deploy

## Stato

Il progetto e pronto per Cloudflare Pages, ma il deploy non e stato completato perche Wrangler non risulta autenticato in questa sessione.

Errore rilevato:

```text
You are not authenticated. Please run `wrangler login`.
```

In ambiente non interattivo Wrangler richiede:

```text
CLOUDFLARE_API_TOKEN
```

## Configurazione progetto

- Framework: Astro
- Output: static
- Build command: `npm run build`
- Output directory: `dist`
- Project name: `due-time-challenge-landing`

## File aggiunti

- `wrangler.toml`
- script `npm run deploy`

## Deploy da CLI

Dopo login Cloudflare:

```bash
npx wrangler login
npm run deploy
```

Oppure con token:

```bash
CLOUDFLARE_API_TOKEN=<token> npm run deploy
```

## Deploy da dashboard Cloudflare Pages

1. Cloudflare Dashboard > Workers & Pages > Create > Pages.
2. Connect to Git.
3. Selezionare `VittorioCutowl/due-time-challenge-landing`.
4. Impostare:
   - Build command: `npm run build`
   - Build output directory: `dist`
   - Framework preset: Astro
5. Deploy.
