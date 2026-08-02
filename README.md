# Avventure di Thalen

Questo repository contiene **l'ambientazione e la storia del mondo delle avventure di Dungeons & Dragons** che stiamo giocando.

Non è un progetto software: è la nostra **wiki di campagna**. Il codice presente serve unicamente a trasformare le note in un sito web consultabile (è basato su [Quartz](https://quartz.jzhao.xyz), che pubblica un vault [Obsidian](https://obsidian.md) come sito statico).

## Di cosa si tratta

Le avventure si svolgono nel continente di **Thalen**, un mondo segnato da forti contrasti geografici e, soprattutto, dalle conseguenze di una misteriosa **Piaga** che cinquant'anni fa ha portato alla scomparsa dei draghi, indebolendo e alterando la magia stessa.

Qui raccogliamo tutto ciò che il gruppo scopre e costruisce sessione dopo sessione: luoghi, popoli, eventi storici, leggende, misteri irrisolti e il resoconto delle avventure vissute.

## Struttura dei contenuti

Tutto il materiale della campagna si trova nella cartella `content/`:

- `content/index.md` — pagina iniziale della wiki, con la panoramica del continente e gli indici principali.
- `content/Ambientazione/Luoghi/` — regioni, città, porti, foreste, montagne e luoghi sacri di Thalen.
- `content/Ambientazione/Lore/` — storia e conoscenze del mondo (ad esempio *The Plague*, la grande piaga).
- `content/Campagna/Sessioni/` — i diari di sessione, in ordine cronologico (`Sessione 001 (data)`, `Sessione 002 (data)`, ...).

Le note sono normali file Markdown e usano i collegamenti in stile Obsidian (`[[Nome Nota|testo visualizzato]]`) per intrecciare luoghi, eventi e personaggi tra loro.

## Consultare la wiki

La wiki è consultabile online all'indirizzo: <https://menecats.github.io/adventures-of-thalen/>

## Configurazione del sito

- `quartz.config.ts` — titolo, tema, analytics e opzioni di generazione.
- `quartz.layout.ts` — disposizione degli elementi delle pagine.
- `public/` — output generato del sito (non va modificato a mano).

## Crediti

Il generatore del sito è **Quartz** di jackyzha0, distribuito con licenza MIT. I contenuti dell'ambientazione sono opera del nostro tavolo di gioco.

Repository originale di Quartz: <https://github.com/jackyzha0/quartz>
