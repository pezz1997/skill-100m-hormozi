# REPARTO OPERATIONS — SOP ONBOARDING & DIANA SETUP
## Framework: Delivery Excellence + Zero Churn

---

## TIMELINE ONBOARDING STANDARD

| Fase | Timing | Owner | Status |
|---|---|---|---|
| Firma contratto + pagamento | Giorno 0 | Sales | [ ] |
| Email benvenuto + questionario | Giorno 0 (entro 2h) | Ops | [ ] |
| Call onboarding | Giorno 1-2 | Ops | [ ] |
| Raccolta accessi | Giorno 1-2 | Ops | [ ] |
| Setup DIANA | Giorno 2-4 | Tech | [ ] |
| Test sistema | Giorno 4-5 | Tech + Cliente | [ ] |
| Lancio ufficiale | Giorno 5-7 | Ops | [ ] |
| Check primo lead | Giorno 7-10 | CS | [ ] |
| Report primo mese | Giorno 30 | CS | [ ] |

---

## EMAIL DI BENVENUTO — TEMPLATE

**Oggetto:** "Benvenuto in Pezz! Ecco i tuoi prossimi 3 passi 🎯"

"Ciao [Nome],

benvenuto nella famiglia Pezz Marketing Solutions!
Sono entusiasta di iniziare questo percorso insieme.

Nei prossimi giorni succederanno queste cose:
1. Entro 24h ti invio il link per la call di onboarding (30 min)
2. Ti chiederò accesso a [lista accessi necessari]
3. Entro 5 giorni lavorativi il tuo sistema sarà attivo e testato

Intanto ti chiedo una sola cosa: compila questo questionario [link Google Form].
Ci vogliono 10 minuti e mi aiuta a personalizzare tutto al tuo business.

Non esitare a scrivermi per qualsiasi cosa. Sono qui.

[Nome]
Pezz Marketing Solutions | WhatsApp: [numero]"

---

## QUESTIONARIO PRE-ONBOARDING (Google Form)

1. Nome dell'agenzia / business
2. Sito web (se presente)
3. Pagina Facebook / Instagram (URL)
4. Accesso Business Manager Facebook già disponibile? (sì/no)
5. Budget mensile ads indicativo
6. Principale zona geografica target
7. Tipo di immobili trattati (residenziale/commerciale/entrambi)
8. Quanti lead ricevi mediamente al mese adesso?
9. Come li gestisci attualmente (CRM, fogli Excel, altro)?
10. Qual è il tuo obiettivo principale nei prossimi 90 giorni?
11. Hai un sito con pixel Facebook installato? (sì/no/non so)
12. Hai già una lista clienti/contatti da importare? (sì/no)

---

## SOP CALL DI ONBOARDING (30 min)

**[00:00-05:00] Review questionario**
- Conferma informazioni raccolta nel questionario
- Chiarisce eventuali domande/dubbi del cliente
- Identifica esigenze specifiche non emerse dal form

**[05:00-15:00] Raccolta accessi**
- Business Manager Facebook: admin access
- Ad Account: admin access
- Pagina Facebook: admin o editor
- Instagram: collegamento a Facebook
- Sito web: accesso per installare/verificare pixel
- Lista contatti: formato accettato (CSV, Google Sheet)

**[15:00-25:00] Setup DIANA live**
- Mostra la dashboard al cliente (screen sharing)
- Configura branding (logo, colori, nome agenzia)
- Review pipeline stage insieme
- Mostra prima email follow-up personalizzata
- Test invio email (live con cliente)

**[25:00-30:00] Next steps e aspettative**
- Conferma timeline (5 giorni per lancio completo)
- Spiega come leggere il report settimanale
- Canale di comunicazione preferito (WhatsApp / email)
- Prossimo contatto: call lancio in 5 giorni

---

## DIANA — SETUP TECNICO COMPLETO

### PIPELINE IMMOBILIARE — 8 STAGE

```
1. Lead Nuovo         → Contatto appena arrivato, da qualificare
2. Contattato         → Primo tentativo risposta effettuato
3. Risposto           → Cliente ha risposto, in qualificazione
4. Appuntamento Fixed → Appuntamento confermato
5. Appuntamento Fatto → Visitato immobile o call avvenuta
6. Trattativa Aperta  → Interesse confermato, negoziazione
7. Offerta Inviata    → Proposta economica sul tavolo
8. Chiuso Vinto       → Mandato firmato o acquisto completato
   Chiuso Perso       → Non interessato / competitor / altro
   Nurturing          → Non pronto ora, da seguire nel tempo
```

### AUTOMAZIONI PRIORITARIE DA ATTIVARE

**Automazione 1 — Risposta immediata lead (0-5 min)**
Trigger: nuovo lead nel sistema
Azione: SMS + email "Ciao [Nome], grazie per il tuo interesse!
Ti ricontatto entro 30 minuti. — [Nome Agente]"
[Questa automazione salva il 40% dei lead freddi]

**Automazione 2 — Reminder agente (5 min)**
Trigger: nuovo lead + nessuna azione entro 5 min
Azione: notifica push + email interna all'agente

**Automazione 3 — Sequenza nurturing (lead non risponde)**
Trigger: lead in stage "Contattato" da 24h senza risposta
Azione: avvia sequenza email 90gg (vedi sotto)

**Automazione 4 — Reminder appuntamento**
Trigger: 24h prima dell'appuntamento
Azione: email + SMS di reminder al lead

**Automazione 5 — Post-appuntamento**
Trigger: appuntamento marcato come "Fatto"
Azione: email di follow-up con materiale + richiesta feedback

### SEQUENZA EMAIL DIANA — 90 GIORNI

| Email | Gg | Oggetto | Focus |
|---|---|---|---|
| 1 | 0 | "Ecco le informazioni che hai richiesto" | Presentazione immediata + CTA soft |
| 2 | 1 | "La soluzione che stai cercando esiste già" | Social proof + risultato caso simile |
| 3 | 3 | "La storia di [cliente case study]" | Storytelling + prima/dopo |
| 4 | 5 | "La domanda che nessuno ti fa" | Qualifying + problem awareness |
| 5 | 7 | "Hai 10 minuti per una chiamata?" | CTA diretta a prenotazione |
| 6 | 10 | "Pensieri sul mercato [città]" | Education + authority building |
| 7 | 14 | "Aggiornamento importante per te" | Urgency/news |
| 8 | 21 | "Risultato di questa settimana" | Social proof fresca |
| 9 | 30 | "Ultimo tentativo (poi ti lascio)" | Pattern interrupt + CTA finale |
| 10 | 45 | "Ciao, come stai?" | Re-engagement personale |
| 11 | 60 | "Una cosa sola" | Offerta semplificata |
| 12 | 75 | "Stavo pensando a te" | Touch personalizzato |
| 13 | 90 | "Chiudo il tuo file — dimmi tu" | Final breakup email |

### DASHBOARD KPI DIANA — METRICHE CHIAVE

**Vista giornaliera (agente):**
- Nuovi lead oggi
- Lead da contattare (non contattati entro 24h)
- Appuntamenti del giorno
- Task in scadenza

**Vista settimanale (responsabile):**
- Lead totali entrati
- Percentuale contattati entro 5 min
- Appuntamenti fissati vs lead
- Trattative aperte
- Chiusure settimana

**Vista mensile (ownership/reportistica cliente):**
- Funnel completo (lead → appuntamenti → trattative → chiusure)
- Tasso conversione per stage
- Confronto mese precedente
- CPL (se integrato con ads)

---

## SOP REPORT CLIENTE — CADENZA SETTIMANALE

**Ogni giovedì mattina invia via WhatsApp:**

"Ciao [Nome]! Report settimanale Pezz 📊

🎯 Questa settimana:
• Lead generati: [N]
• CPL medio: €[X]
• Lead qualificati: [N]
• Appuntamenti fissati: [N]

🚀 Azioni di questa settimana:
• [Azione 1 completata]
• [Azione 2 completata]

📌 Prossima settimana:
• [Azione 1 pianificata]
• [Azione 2 pianificata]

Domande? Scrivimi qui 👇"

---

## CHECKLIST QUALITY CONTROL — PRE-LANCIO

[ ] Pixel Facebook installato e verificato (test con Pixel Helper)
[ ] Evento Lead configurato e attivato correttamente
[ ] Landing page carica in < 3 secondi (test su mobile)
[ ] Form funzionante (test submission)
[ ] Lead arrivano correttamente in DIANA
[ ] Sequenza email partenza automatica dopo submission
[ ] Prima email arriva in inbox (non spam) — test con 3 email diverse
[ ] Notifica real-time all'agente funzionante
[ ] Dashboard accessibile al cliente
[ ] Accessi condivisi e password salvate in documento sicuro
[ ] Backup impostazioni DIANA eseguito
