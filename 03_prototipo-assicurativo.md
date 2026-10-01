---
id: prototipo
ordine: 3
tag: Assicurativo, vendita digitale, prototipazione con AI
titolo: "Dal kick-off al prototipo navigabile in pochi giorni, con Claude"
---

<!--
COME USARE QUESTO FILE
- Modifica liberamente testi, titoli ed elenchi.
- I commenti BLOCCO indicano quale componente grafico usa il blocco sotto
  (insight = riquadri affiancati, metodi = elenco con titoletti, decisione = immagine + callout numerati,
  esiti = tre riquadri in testata, due colonne = confronto affiancato).
- [IMMAGINE: ...] = segnaposto immagine. [DA CONFERMARE] = dato mancante.
- Nessun nome del cliente: solo l'ambito.
-->

# Card in homepage

**Tag:** Assicurativo, vendita digitale, prototipazione con AI

**Titolo:** Dal kick-off al prototipo navigabile in pochi giorni, con Claude

**Testo:** Per una compagnia assicurativa ho trasformato documentazione frammentaria in un prototipo navigabile del flusso di vendita, su mobile e desktop. Claude ha dato la velocità, io ho tenuto la regia di ogni scelta.

<!-- blocco: risultati -->
- **Giorni** — non settimane, dal kick-off alla versione da presentare
- **6 → 4** — passi nel percorso, dopo le iterazioni

[IMMAGINE: prototipo, versione mobile e desktop affiancate]

---

# Testata del case study

**Sommario:** Una compagnia assicurativa doveva presentare ai propri stakeholder un nuovo portale di vendita digitale, con un flusso definito in emergenza e una scadenza ravvicinata. Con Claude ho trasformato tre fonti frammentarie in una base di lavoro strutturata e poi in un prototipo navigabile, iterato più volte in pochi giorni. Con un approccio tradizionale in Figma sarebbero servite settimane. La velocità l'ha data lo strumento; la qualità è venuta dalla regia: ogni scelta di semplificazione, accorpamento e gerarchia l'ho decisa, motivata e verificata io.

<!-- blocco: esiti -->
### Giorni, non settimane
Dal kick-off alla versione da presentare, con più cicli di revisione.

### Da 19 schermate a 4 passi
Un percorso più corto e leggibile, deciso un'iterazione alla volta.

### Incertezza dichiarata
Il prototipo arriva con la lista di cosa è vincolo e cosa è ipotesi.

<!-- blocco: scheda -->
- **Ruolo:** UX Designer, regia del prototipo
- **Team:** PMO, Head of UX, referenti business e IT del cliente
- **Strumenti:** Claude, Claude Design
- **Periodo:** Settembre 2026

[IMMAGINE: il prototipo su mobile (390 px) e desktop (1440 px)]

---

## Contesto

Una compagnia assicurativa danni voleva vendere online polizze di RC professionale sanitaria agli iscritti di associazioni professionali, passando da intermediari minori senza un'infrastruttura digitale propria. Fino a quel momento l'adesione era quasi del tutto manuale: le associazioni inviavano gli elenchi degli iscritti e cliente finale e compagnia non entravano mai in contatto. Per il cliente era un vero cambio di paradigma.

Esisteva già una piattaforma, sviluppata da un fornitore forte sul sistema legacy ma debole su normativa, tracciamenti ed esperienza utente. Andava superata in fretta: il flusso di vendita era stato costruito in pochi giorni e c'era una presentazione agli stakeholder da preparare.

## Perché non Figma

I vincoli del progetto hanno deciso lo strumento prima ancora che si cominciasse a disegnare.

<!-- blocco: insight -->
### Tempo molto compresso
La settimana dopo il kick-off era l'unica utile per produrre il prototipo.

### Resa su mobile
Figma è stato scartato già in riunione proprio per la resa su smartphone: serviva un prototipo HTML navigabile, a bassa o media fedeltà.

### Dominio complesso
Privacy e consensi, adeguatezza, firma elettronica, pagamenti, accessibilità: ogni schermata doveva reggere le obiezioni di stakeholder esperti.

### Fonti imperfette
Nessun requisito formalizzato, nessun wireframe. Solo una slide di flusso con alcune incongruenze, una trascrizione automatica di qualità medio-bassa e uno screenshot del configuratore esistente.

## Il metodo in tre fasi

<!-- blocco: schema (disegnato in SVG nel sito) -->
| Momento | Contenuto | Tempo |
|---|---|---|
| Fonti grezze | slide di flusso, trascrizione, screenshot | Punto di partenza |
| Base condivisa | 18 passi, 4 fasi, discrepanze, da verificare | Poche ore |
| Prototipo v1 | 19 schermate, mobile e desktop | Una sessione |
| Iterazioni UX | 4 passi, punti aperti dichiarati | Pochi giorni |

### 1. Ordinare prima di disegnare

Prima di qualsiasi schermata ho usato Claude per mettere ordine. Dalla trascrizione è nata una nota di kick-off strutturata per temi: flusso, area riservata, architettura, white label, compliance, prossimi passi. La regola che ho dato era netta: riportare solo ciò che si poteva ricostruire con ragionevole sicurezza e raccogliere tutto il resto in una sezione "da verificare".

Incrociando nota e slide, Claude ha ricostruito il flusso di vendita in 18 passi e 4 fasi, con una tabella "chi fa cosa" tra piattaforma e sistema legacy e una lista di discrepanze tra le fonti: l'ordine di pagamento, emissione e firma, il momento dell'invio dei documenti precontrattuali, un ramo di errore della firma etichettato come errore di pagamento.

Un lavoro che di solito richiede giorni di riascolto e riscrittura si è chiuso in poche ore. Soprattutto, ne è uscita una mappa esplicita dell'incertezza: sapevo fin dall'inizio quali scelte del prototipo sarebbero state mie e quali erano vincoli del cliente.

### 2. Partire larghi

Ho creato il prototipo come canvas di Claude Design, così da modificarlo direttamente nella conversazione. Prima di generarlo ho fissato due confini: seguire l'ordine della slide per firma, pagamento ed emissione, tenendo la discrepanza tra i punti aperti, e limitarmi al flusso di vendita, escludendo area riservata e back office.

La prima versione contava 19 schermate, in parallelo su mobile e desktop. Era volutamente un punto di partenza, non un risultato.

### 3. Tagliare, accorpare, riordinare

Da lì il lavoro è diventato un dialogo serrato: osservavo il prototipo, decidevo cosa cambiare e perché, e Claude applicava la modifica su entrambe le versioni. In pochi cicli il flusso è passato da 19 schermate e 6 passi di avanzamento a un percorso in 4 passi: I tuoi dati, Preventivo, Proposta e firma, Pagamento.

## La regia UX: dove si fa la differenza

Claude genera schermate plausibili molto in fretta. Plausibile però non vuol dire giusto: il valore del prototipo sta nelle decisioni prese a ogni giro. Queste sono le principali.

<!-- blocco: decisione -->
### Un funnel senza vie d'uscita e con meno attrito
[IMMAGINE: login e dati precompilati]
1. Ho tolto dall'header i link ad assistenza, FAQ e documenti informativi: ogni uscita dal flusso è un potenziale cliente perso.
2. Ho ridotto i consensi da un paragrafo con due link, due caselle e una doppia scelta marketing a tre sole caselle, senza perdere quelli necessari.
3. Ho fatto lavorare di più il login: con le credenziali dell'associazione i dati arrivano precompilati e quelli certificati sono bloccati. La verifica di appartenenza diventa implicita e la schermata di eleggibilità sparisce.

<!-- blocco: decisione -->
### Una sola schermata per decidere
[IMMAGINE: Riepilogo e accettazione]
1. Ho accorpato conferma, proposta e documenti precontrattuali in "Riepilogo e accettazione": il cliente vede tutto ciò che accetta nel punto in cui lo accetta.
2. Ho spostato modalità di pagamento e decorrenza in una sezione a sé, perché sono attributi del contratto e non della garanzia, con un avviso dedicato se la decorrenza è retrodatata.

<!-- blocco: decisione -->
### Una quotazione che rispecchia il prodotto vero
[IMMAGINE: quotazione a pacchetti]
1. Garanzia base non rimovibile, massimali e retroattività a scelta, garanzie facoltative da aggiungere: la struttura nasce dallo screenshot del configuratore reale, non da un'ipotesi generica.
2. Email e cartaceo sono canali indipendenti, con l'email preselezionata: il cliente può volere i documenti su entrambi.

<!-- blocco: decisione (due immagini verticali affiancate) -->
### Accessibilità e gerarchia visiva
[IMMAGINE: aiuto sempre visibile] [IMMAGINE: stato selezionato e CTA]
1. Accanto al campo "Attività svolta" c'è un testo di supporto sempre visibile, al posto di un tooltip in hover che era stato segnalato come critico per l'accessibilità.
2. Le opzioni selezionate hanno bordo e sfondo leggero, distinte dai pulsanti principali: una scelta non deve sembrare un'azione.

## La provenienza come disciplina

La parte meno visibile della regia, ma decisiva. Più volte ho chiesto a Claude di separare ciò che veniva dalle fonti da ciò che era dedotto o inventato. Alcuni esempi:

<!-- blocco: insight -->
### Login
Nel kick-off era un punto aperto: rappresentare solo l'accesso con le credenziali dell'associazione è stata una scelta di progetto.

### Garanzie facoltative
Venivano dal configuratore, mentre il kick-off parlava di un solo prodotto per istanza.

### Rate e decorrenza
Non erano nelle fonti e hanno aperto un possibile tema di compliance.

### Testi e attività
Elenco delle attività professionali e descrizioni delle garanzie erano ipotesi da validare.

Così il prototipo arriva al cliente con una lista chiara di punti da verificare, non con affermazioni che sembrano certe e non lo sono. Davanti a stakeholder esperti è ciò che separa una proposta credibile da una bella demo.

## Chi ha fatto cosa

<!-- blocco: due colonne -->
### Claude
- Ha riordinato una trascrizione rumorosa in una nota strutturata.
- Ha ricostruito il flusso e segnalato le incongruenze tra le fonti.
- Ha generato 19 schermate su due breakpoint in una sessione.
- Ha applicato ogni modifica in parallelo su mobile e desktop.
- Ha popolato il prototipo con dati e testi realistici.
- Ha tradotto uno screenshot in una quotazione funzionante.

### Io
- Ho stabilito cosa contava e cosa restava incerto.
- Ho deciso come risolvere le incongruenze, o se lasciarle aperte.
- Ho definito perimetro, priorità e percorso da rappresentare.
- Ho tagliato, accorpato e riordinato schermate e contenuti.
- Ho preteso trasparenza su cosa fosse inventato.
- Ho scelto gerarchie, stati visivi e trattamento dell'aiuto alla compilazione.

## Perché è stato così veloce

<!-- blocco: metodi -->
### Nessuna costruzione manuale
Niente libreria di componenti, varianti e collegamenti da creare prima di vedere il primo flusso.

### Due breakpoint al prezzo di uno
Ogni modifica descritta a parole veniva applicata insieme su mobile e desktop.

### Contenuti realistici da subito
Dati, massimali, testi delle garanzie e messaggi di errore coerenti, senza lorem ipsum da sostituire.

### Navigabile su smartphone
HTML reale, senza il problema di resa per cui Figma era stato scartato.

### Documentazione e prototipo insieme
I vincoli emersi nell'analisi erano a portata di mano durante la progettazione.

### Iterazioni in minuti
Accorpare tre schermate richiedeva una richiesta ben formulata, non mezza giornata di lavoro.

Il tempo risparmiato non l'ho tolto al progetto: l'ho reinvestito in più cicli di revisione e in più ragionamento sulle scelte.

## Limiti e attenzioni

- **La velocità amplifica gli errori quanto le idee.** Una scelta sbagliata si propaga in tutte le schermate in pochi secondi: serve un occhio critico a ogni giro.
- **Il plausibile non è il vero.** Claude riempie i vuoti con contenuti credibili; senza una richiesta esplicita di trasparenza, ipotesi e fatti si confondono.
- **Semplificare può toccare vincoli reali.** Togliere la schermata di adeguatezza ha alleggerito il flusso, ma il kick-off la prevedeva: l'ho segnalata come da confermare, non come acquisita.
- **Non sostituisce le verifiche specialistiche.** Compliance, privacy, accessibilità e normativa vanno validate con il cliente e con i team legali.
- **È un prototipo, non un progetto esecutivo.** Serve a decidere e ad allineare; lo sviluppo richiede il consueto lavoro di specifica.

## Il mio ruolo

- Ho fissato perimetro e priorità del prototipo prima di generarlo.
- Ho deciso come trattare le incongruenze tra le fonti.
- Ho guidato ogni iterazione, dalla struttura del flusso alla gerarchia visiva.
- Ho mantenuto la lista dei punti da verificare da portare al cliente.

### Cosa mi porto a casa

<!-- blocco: metodi -->
#### Ordinare prima di disegnare
Una base strutturata, con l'incertezza dichiarata, rende ogni iterazione più veloce e più solida.

#### Partire larghi e tagliare
Una prima versione completa e poi asciugata funziona meglio del flusso perfetto al primo colpo.

#### Chiedere sempre da dove viene un contenuto
È la domanda che tiene il prototipo onesto e pronto alle obiezioni.

#### Non disegno meno: decido di più
Lo strumento sposta il lavoro dall'esecuzione alla regia, ed è lì che si gioca la qualità.
