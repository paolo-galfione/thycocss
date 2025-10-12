# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Progetto: Tycho CSS

Questo progetto ha due obiettivi didattici:

### 1. Imparare Claude Code
Sviluppare un piano didattico per esplorare tutte le funzionalità di Claude Code.

### 2. Creare un foglio di stile semantico
Sviluppare un framework CSS minimale e semantico che formatta elementi HTML standard.

## Regole Operative CRITICHE

**IMPORTANTE**: Quando lavori in questo repository, DEVI seguire queste regole:

1. **UN SOLO TASK ALLA VOLTA** - Ogni task deve essere piccolo e verificabile
2. **CHIEDI CONFERMA** prima di procedere al task successivo
3. **NON ANTICIPARE** lavori futuri
4. **SPIEGA BREVEMENTE** cosa stai per fare prima di farlo

## Linee Guida per i Commit

**Formato commit**:
- Titolo sintetico e descrittivo
- Massimo 2-3 punti elenco essenziali
- **NON** includere riferimenti a Claude Code
- **NON** includere footer con Co-Authored-By o link

**Esempio**:
```
Ridotto contenuto blog e aggiunti form/tabella commenti

- Ridotto lunghezza articolo mantenendo tutti i tag HTML h1-h6
- Aggiunto form commenti con email e textarea
- Aggiunta tabella commenti utenti
```

## Obiettivi del Framework CSS

1. Foglio di stile semantico minimale per elementi HTML standard
2. Sviluppo incrementale partendo dal reset CSS
3. Design system con variabili CSS ispirato a **Practical UI di Adham Dannaway** e ai principi di Tailwind CSS
4. Formattazione elementi tipografici per contenuti testuali/divulgativi
5. Stili avanzati per tabelle, form e schede con naming convention simili a Tailwind CSS

## Ambiente di Sviluppo

- **DevContainer**: Node.js 20 (Bullseye)
- **Live Server**: Porta 5500 per anteprima HTML/CSS
- **ESLint**: Per qualità del codice

## Struttura Prevista

Il progetto includerà:
- `index.html` - Pagina demo/documentazione
- `thyco.css` (o file CSS principale) - Framework CSS semantico
