# Guida Analisi Pubblicitaria - Ad Analysis Framework

Questo framework e' il cuore dell'analisi funnel hacker. Applicalo a OGNI singola ad raccolta per estrarre intelligence azionabile.

---

## 1. Scheda Analisi Singola Ad

Per ogni ad, compila questa scheda:

```
=== SCHEDA AD #[numero] ===

DATI BASE:
- Advertiser: [nome pagina]
- Piattaforma: Facebook / Instagram / entrambe
- Formato: Immagine singola / Carousel / Video / Story / Reel
- Data primo avvistamento: [data o "attiva da X giorni"]
- Status: Attiva / Inattiva
- URL Landing Page: [link]

TESTO COMPLETO AD:
[copia integrale del testo]

ANALISI HOOK (primi 125 caratteri / primi 3 secondi video):
- Tipo hook: Curiosita / Risultato / Contrasto / Autorita / Urgenza / Domanda
- Testo hook: [i primi 125 caratteri visibili senza "leggi altro"]
- Score (1-10): [valutazione efficacia]
- Perche' funziona/non funziona: [spiegazione]

FRAMEWORK DI COPY:
- Modello utilizzato: AIDA / PAS / BAB / QUEST / HSO / Altro
- Breakdown:
  - Attenzione/Problema: [quale parte]
  - Interesse/Agitazione: [quale parte]
  - Desiderio/Soluzione: [quale parte]
  - Azione: [quale parte]

CTA (Call to Action):
- Testo CTA: [es: "Scopri di piu'", "Prenota ora", "Scarica gratis"]
- Tipo CTA: Soft (info) / Medium (lead magnet) / Hard (acquisto)
- Destinazione: Landing page / Form / Messenger / WhatsApp / Shop

OFFER ANALYSIS:
- Cosa viene offerto: [descrizione]
- Prezzo/Gratuita': [prezzo o "gratuito"]
- Posizionamento valore: [come viene presentato il valore]
- Garanzia: Si/No - [tipo]
- Scarsita'/Urgenza: Si/No - [tipo]
- Bonus: Si/No - [descrizione]

AUDIENCE SIGNALS:
- Target probabile: [chi e' il target]
- Pain points citati: [elenco]
- Desideri citati: [elenco]
- Linguaggio usato: Formale / Informale / Tecnico / Emotivo
- Livello di awareness: Unaware / Problem-aware / Solution-aware / Product-aware

PERFORMANCE INDICATORS:
- Durata online: [giorni/settimane]
- Multiple varianti: Si/No
- Engagement visibile: Alto/Medio/Basso
- Probabilita' di performance: Alta/Media/Bassa
- Motivazione: [perche' pensi che performi o meno]

PUNTI DI FORZA:
1. [punto 1]
2. [punto 2]
3. [punto 3]

PUNTI DI DEBOLEZZA:
1. [punto 1]
2. [punto 2]

LEZIONI ESTRAIBILI:
- [cosa possiamo rubare/adattare per il nostro cliente]
```

---

## 2. Come Convertire le Ads in Testo

### Da Meta Ad Library (Browser)
1. Naviga su `facebook.com/ads/library`
2. Cerca per advertiser o keyword
3. Per ogni ad:
   - Usa `get_page_text` per estrarre il testo
   - Se il testo e' troncato, clicca "See more" / "Vedi altro" prima di estrarre
   - Per le ads video: annota la trascrizione del parlato se possibile
   - Per i carousel: estrai il testo di OGNI slide

### Da Screenshot / Immagini
Se l'utente fornisce screenshot:
1. Leggi l'immagine con il tool Read (Claude e' multimodale)
2. Trascrivi tutto il testo visibile
3. Annota elementi visivi rilevanti (colori, layout, persone, prodotto)

### Da Copia-Incolla
Se l'utente incolla il testo:
1. Pulisci la formattazione
2. Identifica le sezioni (hook, body, CTA)
3. Procedi con l'analisi

---

## 3. Analisi Landing Page

Per ogni landing page collegata alle ads:

```
=== LANDING PAGE ANALYSIS ===

URL: [link]
Tipo: Opt-in / Sales Page / VSL / Webinar Registration / Product Page / Application

ABOVE THE FOLD:
- Headline: [testo esatto]
- Sub-headline: [testo]
- Hero image/video: [descrizione]
- CTA primaria: [testo e posizione]
- Elementi di trust: [badge, loghi, numeri]

STRUTTURA PAGINA:
1. [sezione 1 - es: Hero con headline e CTA]
2. [sezione 2 - es: Pain points / problema]
3. [sezione 3 - es: Soluzione / come funziona]
4. [sezione 4 - es: Benefici / features]
5. [sezione 5 - es: Social proof / testimonianze]
6. [sezione 6 - es: Pricing / offerta]
7. [sezione 7 - es: FAQ]
8. [sezione 8 - es: Final CTA]

SOCIAL PROOF:
- Testimonianze: Si/No - [numero e tipo: testo/video/screenshot]
- Numeri: [es: "500+ clienti", "4.8/5 stelle"]
- Loghi clienti/media: Si/No
- Case study: Si/No

ELEMENTI PERSUASIVI:
- Scarsita': [descrizione]
- Urgenza: [descrizione]
- Autorita': [descrizione]
- Reciprocita': [descrizione]
- Prova sociale: [descrizione]

FORM / CONVERSION POINT:
- Campi richiesti: [elenco]
- Numero di step: [1 o multi-step]
- Frizione percepita: Alta/Media/Bassa

TECH STACK (se rilevabile):
- Piattaforma: WordPress / ClickFunnels / Systeme.io / Kartra / Custom
- Page builder: Elementor / Unbounce / Leadpages / Altro
- Pixel: Facebook / Google / TikTok
- Chat: WhatsApp / Messenger / LiveChat
- CRM: [se rilevabile]

SCORE COMPLESSIVO (1-10): [valutazione]
NOTE: [osservazioni aggiuntive]
```

---

## 4. Analisi Comparativa Multi-Ad

Dopo aver analizzato tutte le singole ads, crea una tabella comparativa:

```
| # | Advertiser | Hook Type | Copy Framework | CTA Type | Funnel Stage | Performance Score |
|---|-----------|-----------|---------------|----------|-------------|------------------|
| 1 | [nome]    | [tipo]    | [framework]   | [tipo]   | [stage]     | [1-10]           |
| 2 | [nome]    | [tipo]    | [framework]   | [tipo]   | [stage]     | [1-10]           |
```

### Pattern da Identificare:
1. **Hook dominante**: Quale tipo di hook usano di piu'? Funziona?
2. **Copy framework preferito**: C'e' un pattern nel settore?
3. **CTA pattern**: Soft vs Hard - cosa prevale?
4. **Offer pattern**: Lead magnet vs offerta diretta?
5. **Audience targeting**: A chi parlano tutti? C'e' un segmento ignorato?
6. **Gap nel mercato**: Cosa NESSUNO sta facendo?

---

## 5. Scoring e Prioritizzazione

### Ad Performance Score (stimato)
Calcola un punteggio 1-10 basato su:

| Criterio | Peso | Come valutare |
|----------|------|--------------|
| Longevita' online | 25% | >30gg = 8-10, 14-30gg = 5-7, <14gg = 1-4 |
| Qualita' hook | 20% | Fermati e chiediti: "avrei scrollato via?" |
| Copy persuasiva | 15% | Usa i framework - PAS/AIDA ben eseguiti = punteggio alto |
| CTA chiara | 10% | L'utente sa esattamente cosa fare? |
| Landing page | 15% | Coerenza ad-LP, velocita', professionalita' |
| Funnel completo | 15% | C'e' un percorso chiaro dopo il click? |

### Priorita' per il Piano Operativo
- **Priorita' 1 (Replica subito)**: Score 8-10, alta replicabilita', adattabile al cliente
- **Priorita' 2 (Adatta)**: Score 6-7, buoni elementi da estrarre e migliorare
- **Priorita' 3 (Ispira)**: Score 4-5, qualche idea interessante ma non da copiare
- **Ignora**: Score <4, non rilevante

---

## 6. Template Output per il Report

Quando compili la sezione "Analisi Pubblicitaria" del piano operativo, usa questo formato:

### Per ogni ad nel report:

**Ad #[N] - [Nome Advertiser]**

**Testo completo:**
> [testo integrale dell'ad in blocco citazione]

**Analisi:**
- Hook: [tipo] - "[testo primi 125 char]"
- Framework: [AIDA/PAS/BAB/etc]
- CTA: [testo] --> [destinazione]
- Score: [N]/10
- Lezione chiave: [cosa impariamo da questa ad]

**Applicazione per [Nome Cliente]:**
- [come adattare questa strategia per il cliente]

---

## 7. Checklist Pre-Report

Prima di passare alla Fase 5 (generazione .docx), verifica:

- [ ] Almeno 5 ads analizzate con scheda completa
- [ ] Almeno 3 landing page analizzate
- [ ] Tabella comparativa compilata
- [ ] Pattern identificati e documentati
- [ ] Gap di mercato identificati
- [ ] Almeno 1 strategia "Priorita' 1" trovata
- [ ] Tutti i testi delle ads convertiti e salvati
- [ ] Score assegnati a ogni elemento
- [ ] Lezioni estraibili documentate per ciascuna ad
