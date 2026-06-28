# Due Time - Landing concorso evento

## Obiettivo

Creare una landing page locale, bella ed engaging, per promuovere Due Time durante un evento dal vivo.

La landing deve presentare un concorso a premi basato sul punteggio ottenuto in un giochino interno all'app. I primi 3 classificati vincono un premio.

## Contesto

- Prodotto: Due Time, app per gestire scadenze.
- Sponsor del concorso: Cutowl.
- Evento: domani rispetto alla prima raccolta requisiti, quindi la pagina deve essere efficace, chiara e pronta per uso rapido.
- Meccanica promo: scarichi/provi l'app, giochi, fai punti, entri in classifica.
- Target: persone presenti all'evento, probabilmente da convertire velocemente tramite QR/download/TestFlight.

## Riferimenti forniti

1. Landing promo gara:
   https://due-time-gara.netlify.app/gara.html

2. Landing ufficiale Due Time:
   https://www.cutowl.com/due-time-landing/index.html

3. Pagina score/classifica:
   https://splendid-longma-5b2da5.netlify.app/

4. Sito Cutowl:
   https://www.cutowl.com/

## Lettura dei riferimenti

### Landing promo gara

Messaggio diretto:

- "La gara e aperta."
- "Salva il gregge."
- "Il miglior pastore porta a casa il premio."

Struttura rilevata:

- Hero con logo Due Time.
- Sezione premi per 1, 2 e 3 posto.
- Sezione "Tre passi per vincere": scarica, gioca, vinci.
- QR per scaricare Due Time su TestFlight / iPhone.
- Tono giocoso e immediato.

Punti da valorizzare nella nuova landing:

- Immediatezza della gara.
- Chiarezza dei premi.
- CTA molto visibile.
- Maggiore energia visuale e senso di evento live.

### Landing ufficiale Due Time

Messaggio principale:

- "Le tue scadenze, in buone zampe."
- "Fotografa un documento, Due fa il resto."

Elementi identitari:

- Cielo, prato, nuvole.
- Logo Due Time.
- Palette soft con verde, cielo, bianco.
- Font: Ubuntu e Barlow.
- Personaggi/asset legati al mondo pecore/prato.
- Mockup dell'app e sezioni prodotto.

Punti da riusare:

- Identita visiva morbida e riconoscibile.
- Tono simpatico, leggero, non aggressivo.
- Asset e atmosfera coerenti con il brand.

### Pagina score/classifica

Elementi principali:

- "Due Time - Classifica"
- "Classifica globale - Dui Saves the Flock"
- Podio per i primi 3.
- Lista punteggi con rank, nome, score, livello e stelle.
- Bottone aggiorna.

Punti da integrare concettualmente:

- La landing deve spingere a entrare in classifica.
- Il podio e i primi 3 sono centrali per il racconto del concorso.
- La classifica puo essere linkata o incorporata come richiamo visivo.

## Direzione creativa proposta

La nuova landing deve fare da ponte tra:

- brand/app ufficiale Due Time;
- energia della gara;
- dinamica competitiva della classifica.
- identita Cutowl come sponsor e garante del concorso.

Deve sembrare una pagina evento: veloce da capire, divertente, con CTA forte e visuali riconoscibili.

Lo stile deve ridurre l'uso di emoji e preferire asset reali, illustrazioni, loghi, icone e micro-grafica coerente con Due Time e Cutowl.

## Possibile struttura della landing

1. Hero evento
   - Logo Due Time.
   - Titolo forte orientato alla gara.
   - Sottotitolo che spiega in una frase: gioca, fai punti, scala la classifica, vinci.
   - CTA primaria: scarica/partecipa.
   - QR ben visibile.
   - Visuale game/podio/pecore.

2. Come funziona
   - 3 passaggi: scarica Due Time, gioca a Dui Saves the Flock, entra in classifica.

3. Premi
   - 1, 2 e 3 posto.
   - Layout da podio, più fisico e celebrativo rispetto alla pagina promo attuale.

4. Classifica live
   - Link o embed verso la score page.
   - Richiamo al fatto che la classifica si aggiorna.

5. CTA finale
   - QR + invito breve.
   - Eventuale nota TestFlight/iPhone se necessaria.

## Requisiti di tono

- Italiano.
- Energico ma non urlato.
- Giocoso, vicino al mondo Due Time.
- Frasi brevi, da evento.
- Evitare lunghi testi descrittivi.

## Requisiti tecnici iniziali

- Progetto Astro.
- Deploy previsto su Cloudflare.
- Asset locali in `public/assets/` oppure gestiti secondo le convenzioni Astro se il progetto cresce.
- Landing mobile-first, adatta a uso da telefono tramite QR.
- Deve funzionare anche come pagina su schermo/stand evento.
- Evitare dipendenze pesanti se non necessarie.
- Generare output statico quando possibile, salvo necessita specifiche Cloudflare.

## Decisioni ancora da confermare

- Nome esatto del gioco da mostrare: "Dui Saves the Flock" o altro.
- Link definitivo per scaricare/installare l'app.
- Link definitivo alla classifica.
- Premi reali o copy generico tipo "premio speciale".
- Eventuale regolamento, orario di chiusura gara e luogo/evento.
