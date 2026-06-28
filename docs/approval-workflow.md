# Workflow di approvazione

Questo progetto procede per checkpoint approvati con Vittorio prima di passare alla fase successiva.

Regola generale: ogni checkpoint che riguarda direzione visuale, struttura, layout, UI o design deve includere una anteprima HTML locale apribile nel browser. Le approvazioni non devono basarsi solo su descrizioni testuali quando e possibile mostrare una pagina.

## 1. Direzione creativa

Definire e approvare:

- mood generale della landing;
- equilibrio Due Time / Cutowl;
- livello di gioco, competizione e sponsor;
- stile visuale;
- uso di asset reali invece di emoji.

Output atteso: una proposta sintetica di direzione creativa da approvare o correggere. Se la direzione contiene scelte visive rilevanti, accompagnarla con una mini anteprima HTML o moodboard HTML locale.

## 2. Copy della landing

Definire e approvare:

- headline;
- sottotitolo;
- CTA;
- testi per come partecipare;
- testi premi;
- blocco sponsor Cutowl;
- eventuale microcopy per QR, TestFlight, classifica e regolamento.

Output atteso: testi principali pronti per entrare nella pagina.

## 3. Wireframe rapido

Definire e approvare:

- ordine delle sezioni;
- contenuto del primo viewport;
- posizione di QR e CTA;
- blocco premi;
- blocco classifica;
- presenza Cutowl;
- footer.

Output atteso: struttura pagina prima dell'implementazione, sempre accompagnata da una anteprima HTML locale.

## 4. Asset

Definire e approvare:

- asset scaricati e riusati dai riferimenti;
- asset Cutowl;
- asset Due Time;
- eventuali nuovi asset da generare;
- posizione finale in `public/assets/`.

Output atteso: lista asset da usare e asset locali organizzati.

Se la selezione asset cambia in modo significativo il look della pagina, preparare una anteprima HTML locale aggiornata con gli asset reali.

## 5. Prima versione Astro

Implementare:

- progetto Astro;
- landing responsive;
- componenti e stili;
- asset locali;
- CTA e link provvisori o definitivi.

Output atteso: prima versione navigabile in locale.

## 6. Review visiva

Verificare con Vittorio:

- impatto del primo viewport;
- leggibilita mobile;
- gerarchia Due Time / Cutowl;
- chiarezza della gara;
- forza della CTA;
- presenza di classifica e premi;
- coerenza con i riferimenti.

Output atteso: lista modifiche finali.

## 7. Finalizzazione

Completare:

- link definitivi;
- QR definitivo;
- premi reali;
- eventuale regolamento;
- build Astro;
- preparazione deploy Cloudflare.

Output atteso: landing pronta per pubblicazione.
