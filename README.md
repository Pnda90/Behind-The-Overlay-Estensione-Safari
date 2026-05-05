# Behind The Overlay — Estensione Safari

Un'estensione Safari per Mac che ti permette di **chiudere qualsiasi overlay su qualsiasi sito con un solo clic**.

Convertita dall'estensione originale per [Chrome](https://chrome.google.com/webstore/detail/behindtheoverlay/) e [Firefox](https://addons.mozilla.org/firefox/addon/behind_the_overlay/) creata da [NicolaeNMV](https://github.com/nicoleenmv/BehindTheOverlay).

## Funzionalità

- Un pulsante per chiudere qualsiasi overlay su qualsiasi sito
- Non richiede permessi speciali
- Leggerissima — si attiva solo quando clicchi il pulsante
- Supporta più overlay sulla stessa pagina
- Ripristina lo scroll della pagina quando gli overlay lo bloccano
- Scorciatoia da tastiera: `Cmd + Shift + X`

## Installazione

1. Scarica l'ultimo file `.zip` dalla sezione [Releases](https://github.com/Pnda90/Behind-The-Overlay-Estensione-Safari/releases/latest)
2. Apri l'app — una finestra ti guiderà ad abilitare l'estensione
3. Apri **Safari → Impostazioni → Avanzate** → abilita **"Mostra funzionalità per sviluppatori web"**
4. Vai in **Safari → Impostazioni → Sviluppatore** → abilita **"Consenti estensioni non firmate"**
5. Vai in **Safari → Impostazioni → Estensioni** → attiva **Behind The Overlay**

> ⚠️ Il flag "Consenti estensioni non firmate" si resetta ad ogni riavvio del Mac. Dovrai riabilitarlo ogni volta.

## Compilare dal sorgente

Richiede Xcode 12+ su macOS 11 Big Sur o versioni successive.

1. Clona questa repo
2. Apri `Behind The Overlay.xcodeproj` in Xcode
3. Seleziona **My Mac** come destinazione
4. Premi **Cmd + R** per compilare ed eseguire

## Autore

Porting per Safari realizzato da [Pnda90](https://github.com/Pnda90).

## Licenza

Questo progetto è distribuito sotto licenza **GPL-3.0**, in conformità con l'estensione originale.

> In sintesi: puoi usare, modificare e ridistribuire questo codice liberamente, ma qualsiasi versione derivata deve mantenere la stessa licenza GPL-3.0 e rendere disponibile il codice sorgente.

Consulta il file [LICENSE](./LICENSE) per il testo completo della licenza.

## Crediti

Estensione originale di [NicolaeNMV](https://github.com/nicoleenmv/BehindTheOverlay) — licenza [GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.en.html).
