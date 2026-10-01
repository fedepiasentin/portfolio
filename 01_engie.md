---
id: engie
ordine: 1
tag: ENGIE, energia, service design
titolo: "Da un modulo statico a un percorso guidato: l'attivazione di luce e gas"
---

<!--
COME USARE QUESTO FILE
- Modifica liberamente testi, titoli ed elenchi.
- I commenti BLOCCO indicano quale componente grafico usa il blocco sotto
  (insight = riquadri affiancati, metodi = elenco con titoletti, decisione = immagine + callout numerati).
  Se vuoi cambiare componente, cambia il commento; se non lo sai, lascialo com'è.
- [IMMAGINE: ...] = segnaposto immagine. [DA CONFERMARE] = dato mancante.
-->

# Card in homepage

**Tag:** ENGIE, energia, service design

**Titolo:** Da un modulo statico a un percorso guidato: l'attivazione di luce e gas

**Testo:** Come UX Owner ho guidato il redesign del flusso con cui i clienti attivano un'offerta online: ricerca, workshop con business e tecnologia, user flow e wireframe.

<!-- blocco: risultati -->
- **+37%** — completamento su desktop
- **+51%** — completamento su mobile

**Premio:** 2° posto, Best Website Optimization, Digital Experience Awards 2026 by Contentsquare

[IMMAGINE: nuovo flusso, step di configurazione]

---

# Testata del case study

**Sommario:** Il canale online per attivare un'offerta luce e gas era datato e poco usato, e lasciava a call center e negozi gran parte delle attivazioni. Come UX Owner ho guidato il redesign del flusso.

<!-- blocco: risultati -->
- **+37%** — completamento su desktop
- **+51%** — completamento su mobile
- **2° posto** — Best Website Optimization, Digital Experience Awards 2026 by Contentsquare

<!-- blocco: scheda -->
- **Ruolo:** UX Owner & Service Designer
- **Team:** Business, UI design, sviluppo
- **Metodi:** Usability test, survey, benchmark, workshop, UAT
- **Periodo:** [DA CONFERMARE]

[IMMAGINE: il nuovo flusso su desktop e mobile]

---

## Contesto

ENGIE è uno dei principali fornitori di energia in Italia. Il flusso online per attivare un'offerta luce e gas era un modulo statico: lungo, poco chiaro sui costi, pensato per desktop. Il canale restava marginale, mentre attivazioni e dubbi finivano su call center e negozi fisici.

L'obiettivo era trasformarlo in un percorso affidabile e orientato alla conversione, capace di gestire un sistema pieno di eccezioni senza scaricarle sul cliente.

## Cosa non funzionava

<!-- blocco: insight -->
### Troppi passaggi
Informazioni ripetute e carico cognitivo alto prima ancora di scegliere l'offerta.

### Prezzi poco trasparenti
Non capire cosa si stava pagando minava la fiducia nel momento della decisione.

### Non pensato per il mobile
E difficile da riprendere per chi tornava a completare l'attivazione più tardi.

### Casi particolari scoperti
Cambi di offerta e clienti con più utenze non avevano un percorso dedicato e abbandonavano.

## Come l'abbiamo capito

Abbiamo combinato metodi qualitativi e quantitativi, così che ogni scelta successiva avesse una prova a supporto. Ho contribuito alla fase di ricerca e al benchmark.

<!-- blocco: metodi -->
### Usability test non moderati
Per osservare dove le persone si bloccavano nel flusso esistente.

### Survey quantitativa
Per misurare fiducia, chiarezza e soddisfazione percepite.

### Benchmark comparativo
Per capire come i principali concorrenti strutturano i loro flussi.

### Valutazione euristica (Baymard)
Per individuare i problemi strutturali dell'esperienza.

## Allineare business e tecnologia

Ogni semplificazione toccava regole commerciali e vincoli tecnici, quindi servivano decisioni condivise prima di disegnare qualsiasi schermata. Con stakeholder di business, UX e tecnologia abbiamo condotto un workshop "How might we" che ha portato a tre direzioni:

- percorsi decisionali più chiari e meno passaggi;
- prezzi e vantaggi visibili fin dall'inizio;
- una gestione unica delle eccezioni per i clienti già attivi.

## Quattro ingressi, un solo percorso

Ho disegnato uno user flow che porta tutti i principali scenari di attivazione dentro lo stesso percorso guidato, invece di creare un flusso separato per ogni caso.

<!-- blocco: schema (disegnato in SVG nel sito) -->
- **Ingressi:** Nuovo cliente · Cambio offerta · Simulatore bolletta · Ingresso promozionale
- **Percorso guidato a step:** Offerta → Dati → Documenti → Conferma
- **Sempre visibili:** avanzamento, riepilogo costi, pausa e ripresa

*Nota sotto lo schema:* Schema semplificato, da sostituire con lo user flow originale se pubblicabile.

## Le soluzioni

Dai flussi approvati ho realizzato wireframe a bassa fedeltà per definire struttura e logica. Una volta validati, il team UI ha sviluppato la grafica finale e un prototipo HTML cliccabile. Tre principi guida: struttura modulare, layout mobile-first con testi semplici, microcopy trasparente sui costi.

<!-- blocco: decisione -->
### Configurazione dell'offerta
[IMMAGINE: step di configurazione]
1. L'offerta che si sta attivando resta sempre in vista.
2. L'avanzamento dice in ogni momento quanto manca alla fine.
3. Il riepilogo mostra tutti i costi, con tooltip sulle voci meno chiare.

<!-- blocco: decisione -->
### Prima della sottoscrizione
[IMMAGINE: panoramica pre-sottoscrizione]
1. Ogni fase dichiara quanto tempo richiede.
2. Le scelte restano modificabili anche a configurazione conclusa.
3. La panoramica elenca durata complessiva e documenti necessari.

<!-- blocco: decisione -->
### Meno campi da compilare
[IMMAGINE: caricamento della bolletta]
1. Caricando la bolletta, dati e stima dei consumi si compilano da soli.
2. Durante la sottoscrizione il riepilogo si chiude per lasciare spazio allo step in corso.
3. La sottoscrizione si può sospendere e riprendere più tardi.

<!-- blocco: decisione (due immagini verticali affiancate) -->
### Su mobile
[IMMAGINE: step su mobile] [IMMAGINE: riepilogo in overlay]
1. L'avanzamento diventa una fisarmonica che non ruba spazio.
2. La chat si sposta in alto a destra, lontano dal pulsante per proseguire.
3. Il riepilogo dell'offerta si apre da un link in alto, in un overlay.

<!-- blocco: prima e dopo -->
### Prima e dopo: inserimento dei dati personali
[IMMAGINE: prima] [IMMAGINE: dopo]

## Validazione e risultati

Il cliente ha scelto di non fare test con utenti prima del lancio. Per non arrivare al rilascio senza verifiche, ho condotto sessioni di User Acceptance Test con stakeholder interni e sviluppatori, controllando allineamento ai requisiti e usabilità di ogni release.

<!-- blocco: risultati -->
- **+37%** — completamento su desktop
- **+51%** — completamento su mobile

Il miglioramento più forte arriva su mobile, dove il vecchio flusso era più debole. Il redesign si è classificato secondo nella categoria Best Website Optimization ai Digital Experience Awards 2026 by Contentsquare (Milano, giugno 2026).

## Il mio ruolo

- Ho definito roadmap e priorità insieme agli stakeholder.
- Ho contribuito alla ricerca e al benchmark.
- Ho guidato la progettazione UX: user flow, wireframe, logiche di interazione.
- Ho fatto da ponte tra team UI e sviluppo durante l'implementazione.
- Ho condotto gli UAT prima del rilascio.

[BOZZA: qui va una tua riflessione finale su cosa ti ha insegnato il progetto.]
