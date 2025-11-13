# Progetto.Personale_GEP_Bollettino

## Nome:
### Bollettino Andrea

## Nome Startup:
### Bam3D

## Descrizione:
### Bam3D è una piattaforma web e mobile dedicata alla stampa 3D online, progettata per rendere questo servizio accessibile a tutti, anche a chi non ha competenze tecniche.
Attraverso un’interfaccia semplice e intuitiva, l’utente può:
 - Sfogliare un catalogo di modelli 3D pronti per la stampa;
 - Richiedere un progetto personalizzato, creato su misura da designer esperti;
 - Caricare i propri file 3D per farli stampare direttamente e riceverli a casa.
### Bam3D semplifica l’intero processo di stampa 3D, rendendolo immediato, conveniente e alla portata di chiunque

## Problema:
La stampa 3D, per chi non possiede conoscenze tecniche, è spesso complessa e costosa.
Richiede l’uso di software professionali, macchinari costosi e competenze specifiche di modellazione.
Inoltre, trovare modelli adatti o ottenere progetti personalizzati può risultare difficile e dispendioso.
Questo limita l’accesso alla stampa 3D a una piccola nicchia di esperti, escludendo molti potenziali utenti che vorrebbero sfruttarne le potenzialità in modo semplice, veloce e conveniente.

## Target:
### Il target di Bam3D comprende:
 - Privati e hobbisti che desiderano realizzare oggetti personalizzati senza acquistare una stampante;
 - Designer, studenti e maker che vogliono prototipare le proprie idee rapidamente;
 - Artigiani digitali e piccole imprese che necessitano di pezzi unici, parti di ricambio o prototipi;
 - Persone con budget limitato, che cercano soluzioni di qualità ma accessibili.
### In sintesi, Bam3D si rivolge a chiunque voglia sfruttare la stampa 3D senza barriere tecniche o economiche.

## Competitors:
<img width="1215" height="583" alt="tab" src="https://github.com/user-attachments/assets/7abfdcd0-9937-4ba2-ae3e-8d6d95b92dd4" />

 - Xometry – piattaforma globale per la stampa 3D on-demand;
 - Made in add – marketplace che confronta i prezzi
 di diversi servizi di stampa 3D;
 - ProtoLabs Network – leader internazionale nella stampa 3D personalizzata;
 - PolyD – rete di produzione digitale che include stampa 3D, CNC e altre tecnologie.
### Bam3D si distingue per la semplicità d’uso, l’approccio local-first (collaborazione con service di stampa italiani) e l’integrazione tra catalogo, richiesta su misura e upload diretto in un unico flusso.

## Requisiti Funzionali

### Registrazione e Autenticazione Utenti
- Creazione account e gestione del profilo personale.

### Catalogo Modelli 3D
- Visualizzazione di modelli 3D con categorie, descrizioni e anteprime.  
- Possibilità di scaricare o ordinare la stampa di un modello.

### 3. Upload File 3D
- L’utente può caricare i propri file per richiedere la stampa.

### 4. Richiesta di Progetto Personalizzato
- Modulo per descrivere il progetto desiderato e richiedere preventivo o contatto con un designer.

### Preventivo Automatico e Ordine Stampa
- Calcolo automatico del costo in base a materiale, dimensioni e tempi di consegna.  
- Possibilità di confermare e pagare l’ordine online.

### Tracking Ordine
- Monitoraggio dello stato dell’ordine: *in lavorazione*, *spedito*, *consegnato*.

### Gestione Amministrativa
- Pannello di controllo per gestire ordini, utenti e pagamenti.

## Requisiti Non Funzionali

### Usabilità
- Interfaccia semplice e intuitiva, adatta anche a utenti non tecnici.  
- Navigazione chiara e responsive.

### Prestazioni
- Caricamento rapido dei modelli 3D e delle anteprime.

### Sicurezza
- Protezione dei dati e dei pagamenti tramite crittografia.  
- Accesso autenticato e gestione dei permessi.

### Scalabilità
- Capacità di gestire un numero crescente di utenti e file caricati.

### Manutenibilità
- Architettura modulare per aggiornamenti e miglioramenti futuri.

## Tagline:
### Crea, carica, stampa: la 3D experience per tutti.

## Tecnologie:
 - Frontend: React / Next.js
 - Backend: Node.js con Express
 - Database: MongoDB o PostgreSQL
 - Storage file 3D: AWS S3 / Cloudinary / IPFS
 - Rendering 3D online: Three.js / Babylon.js
 - Integrazione pagamenti: Carte di credito o debito / Google e Apple Pay / PayPal
 - App mobile: Flutter o React Native
 - AI/assistente di progetto (futuro): integrazione con modelli generativi per suggerimenti di design o analisi dei file STL.

## Diagramma UML:
### link: https://yuml.me/andrebolle/bam3d.svg
<img width="778" height="699" alt="image" src="https://github.com/user-attachments/assets/df770a1b-ee49-4cf2-81c8-e8e6c8a738fd" />

