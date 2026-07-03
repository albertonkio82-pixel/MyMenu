# Il Nostro Menù — PWA

## Deploy su GitHub Pages (5 minuti)
1. Crea un repo nuovo, es. `albertospde/il-nostro-menu` (può essere privato o pubblico, non contiene dati sensibili).
2. Carica questi 5 file nella root: `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`.
3. Settings → Pages → Deploy from branch → `main` / root.
4. L'app sarà su `https://albertospde.github.io/il-nostro-menu/`.

## Installazione su smartphone
- **Android/Chrome**: apri il link → banner "Installa" in basso (già integrato nell'app) → tocca Installa.
- **iPhone/Safari**: apri il link → tasto Condividi → "Aggiungi a Home".

## Condivisione con tua moglie
Manda il link via WhatsApp (bottone "Condividi" nell'app lo fa in un tap) e fatelo installare anche a lei: stessa app, stesso menu, ognuno con le proprie spunte sul proprio telefono.

## Nota su dati condivisi in tempo reale
Ora ogni telefono tiene le proprie spunte in locale (funziona offline, zero configurazione). Se vuoi che le spunte siano **sincronizzate live tra i due telefoni** (es. lei spunta "fatto" e tu lo vedi subito), basta collegare una tabella Supabase — stesso pattern che usi per Planning Presenze. Dimmelo e te la aggiungo.
