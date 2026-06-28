# Prima versione Astro

## Stato

La prima versione Astro della landing e stata implementata.

## File principali

- `src/pages/index.astro`
- `src/styles/global.css`
- `astro.config.mjs`
- `package.json`
- `tsconfig.json`

## Build

La build locale Astro e passata correttamente:

```bash
npm run build
```

Output:

- `dist/`

## Preview locale

La preview build e stata avviata con:

```bash
npm run preview -- --host 127.0.0.1
```

URL usato in locale:

```text
http://127.0.0.1:4322/
```

## Asset definitivi inseriti

- QR code definitivo: `public/assets/qr-due-time.png`

## Placeholder ancora presenti

- Link definitivo per installazione/partecipa.
- Premi reali.
- Nomi e punteggi reali nella preview classifica.
- Eventuale regolamento.

## Prossimo step di approvazione

Review visiva della pagina Astro in locale.
