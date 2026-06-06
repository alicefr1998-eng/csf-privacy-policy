# Informativa sulla Privacy — Che si fa?

**Ultimo aggiornamento:** 6 giugno 2026
**Versione applicazione:** 1.0.0

---

## In breve

- **Che si fa?** è un'app gratuita che ti mostra eventi e luoghi del Levante ligure (Tigullio, Golfo Paradiso, Val Graveglia, Val d'Aveto, ecc.). La usi **in forma anonima, senza registrazione e senza account**.
- **Non ti chiediamo nome, email o numero di telefono.**
- I tuoi **eventi salvati, preferiti e impostazioni restano sul tuo dispositivo** e non vengono caricati su nessun server.
- Usiamo strumenti di **diagnostica dei crash** (per tenere l'app stabile) e, **solo con il tuo consenso**, strumenti di **statistica d'uso anonima** (per capire cosa funziona). Puoi cambiare idea quando vuoi dalle impostazioni.
- La **posizione** viene richiesta solo quando tocchi una funzione che la usa (es. "eventi vicino a me" o la mappa), è elaborata **sul tuo dispositivo** e **non viene inviata né salvata** sui nostri server.
- **Non vendiamo i tuoi dati** e **non facciamo pubblicità né tracciamento tra app diverse.**

La versione completa qui sotto spiega tutto in dettaglio, come richiesto dal Regolamento (UE) 2016/679 (GDPR).

---

## 1. Titolare del trattamento

Il Titolare del trattamento dei dati personali è:

- **Alice Frugone**
- Email di contatto per la privacy: **chesifa.app@gmail.com**

Per qualsiasi richiesta relativa ai tuoi dati personali o all'esercizio dei tuoi diritti puoi scrivere all'indirizzo email sopra indicato.

Non è stato nominato un Responsabile della Protezione dei Dati (DPO), in quanto non ricorrono i presupposti di obbligatorietà previsti dall'art. 37 del GDPR.

---

## 2. A chi si rivolge questa informativa

Questa informativa descrive come tratti­amo i dati di chi utilizza l'applicazione mobile **Che si fa?** ("l'App") su iOS, Android e web. L'App è un aggregatore di contenuti in **sola lettura**: gli eventi e i luoghi sono inseriti da un sistema esterno e tu li consulti, senza poterli modificare.

L'App è pensata per residenti, turisti e appassionati di outdoor. **Non è destinata a minori di 13 anni** (vedi § 12).

---

## 3. Quali dati trattiamo, perché e con quale base giuridica

Trattiamo **solo i dati strettamente necessari** al funzionamento dell'App. Non raccogliamo dati identificativi diretti (nome, cognome, email, telefono). La tabella seguente riassume i trattamenti; i paragrafi successivi li approfondiscono.

| # | Dati trattati | Finalità | Base giuridica (art. 6 GDPR) | Dove restano | Conservazione |
|---|---|---|---|---|---|
| A | **Identificativo anonimo del dispositivo** (`device_id`: codice casuale UUID generato sul dispositivo) | Distinguere le installazioni per diagnostica e statistiche, senza identificarti | Diagnostica: legittimo interesse (f) · Statistiche: consenso (a) | Sul dispositivo; condiviso con Sentry e (solo con consenso) PostHog | Finché non disinstalli l'App o cancelli i dati |
| B | **Dati di diagnostica e crash** (modello dispositivo, sistema operativo, versione App, schermata/percorso, log tecnico dell'errore, dati di performance) | Individuare e correggere errori e crash, mantenere l'App sicura e stabile | Legittimo interesse (f) | Server Sentry (UE) | Fino a ~90 giorni |
| C | **Statistiche di utilizzo anonime** (schermate visitate, azioni nell'App, tipo di dispositivo) | Capire come viene usata l'App e migliorarla | **Consenso (a)** | Server PostHog (UE) | Max 12 mesi, poi aggregate/cancellate |
| D | **Posizione geografica** (coordinate GPS) | Mostrarti eventi e luoghi vicini, ordinare i risultati per distanza | Consenso, tramite permesso del sistema operativo (a) | **Solo sul tuo dispositivo**, in memoria temporanea | Non conservata: scartata alla chiusura |
| E | **Calendario del dispositivo** (scrittura di un evento) | Aggiungere al tuo calendario un evento che hai scelto | Consenso, tramite permesso del sistema operativo (a) | **Solo sul tuo dispositivo** | Gestita dal tuo calendario |
| F | **Preferiti, eventi salvati e impostazioni** | Far funzionare le tue liste e preferenze | Esecuzione del servizio (b) / legittimo interesse (f) | **Solo sul tuo dispositivo** (archivio locale) | Finché non li elimini o disinstalli l'App |
| G | **Dati tecnici di connessione** (indirizzo IP, dati della richiesta) verso i fornitori che erogano contenuti, immagini, mappe e aggiornamenti | Consegnarti i contenuti e far funzionare l'App | Legittimo interesse / necessità tecnica (f) | Server dei fornitori (vedi § 6) | Secondo i log dei rispettivi fornitori |

**Note importanti:**

- Il `device_id` (riga A) è un codice casuale generato sul tuo dispositivo: **non contiene il tuo nome, non è collegato alla tua identità reale** e non permette di risalire a te. Serve solo a non contare due volte la stessa installazione.
- Le **statistiche d'uso (riga C)** sono attive **solo se dai il consenso**. Senza consenso, l'App funziona normalmente e non inviamo dati statistici.
- La **posizione (riga D)** e il **calendario (riga E)** sono elaborati **solo sul tuo dispositivo**: **non li riceviamo, non li trasmettiamo e non li conserviamo** sui nostri server.

### Natura del conferimento

Fornire questi dati è **facoltativo**. Puoi usare l'App rifiutando il consenso alle statistiche e negando i permessi di posizione e calendario: alcune funzioni (es. "eventi vicino a me", "aggiungi al calendario") non saranno disponibili, ma il resto dell'App continuerà a funzionare.

---

## 4. Permessi del dispositivo

L'App chiede alcuni permessi **solo nel momento in cui servono** (approccio "just-in-time"), mai all'avvio:

- **Posizione (mentre usi l'App):** richiesta quando tocchi "eventi vicino a me" o apri la mappa. La usiamo **solo in primo piano**, mentre l'App è aperta: **non tracciamo i tuoi spostamenti in background**. La posizione è usata sul dispositivo per calcolare le distanze e non viene inviata a noi.
- **Calendario:** richiesto solo quando scegli "Aggiungi al calendario" su un evento. Serve a scrivere quell'evento nel tuo calendario. **Non leggiamo** gli altri appuntamenti del tuo calendario.

Puoi **concedere o revocare** ogni permesso in qualsiasi momento dalle impostazioni del sistema operativo del dispositivo (iOS: Impostazioni › Privacy e sicurezza; Android: Impostazioni › App › Che si fa? › Autorizzazioni).

---

## 5. Statistiche, consenso e tecnologie di tracciamento

Per migliorare l'App utilizziamo **PostHog**, uno strumento di analisi statistica del prodotto, configurato per **non** registrare automaticamente i tuoi tocchi sullo schermo e per **non** raccogliere il tuo indirizzo IP (regione UE).

In conformità alla Direttiva ePrivacy (2002/58/CE) e alle linee guida del **Garante per la protezione dei dati personali**, queste statistiche — poiché si basano su un identificatore del dispositivo — vengono attivate **solo dopo che hai espresso un consenso libero ed esplicito** tramite l'apposito avviso ("banner") che ti mostriamo nell'App. Fino ad allora **nessun dato statistico viene raccolto**.

Puoi **revocare il consenso in qualsiasi momento** dalla sezione Impostazioni/Profilo dell'App: da quel momento smetteremo di raccogliere statistiche d'uso. La revoca non pregiudica la liceità del trattamento basato sul consenso prestato prima della revoca.

Lo strumento di **diagnostica dei crash (Sentry)** opera invece sulla base del **legittimo interesse** a mantenere l'App sicura, stabile e priva di errori: raccoglie informazioni tecniche sull'eventuale errore, non contenuti personali. Puoi opporti a questo trattamento (vedi § 9).

**Non utilizziamo l'App per pubblicità, profilazione a fini di marketing o tracciamento delle tue attività su altre app o siti** (nessun "tracking" ai sensi delle regole Apple App Tracking Transparency).

---

## 6. Destinatari dei dati (responsabili e fornitori)

Non vendiamo né cediamo i tuoi dati. Per erogare il servizio ci avvaliamo di fornitori tecnologici che agiscono come **responsabili del trattamento** (art. 28 GDPR) o, per i log tecnici, come autonomi titolari. I principali sono:

| Fornitore | Ruolo nel servizio | Dati trattati | Regione dati | Informativa |
|---|---|---|---|---|
| **Sentry** (Functional Software, Inc.) | Diagnostica crash ed errori | Dati tecnici di errore, `device_id` | UE (Germania) | https://sentry.io/privacy/ |
| **PostHog** (PostHog, Inc.) | Statistiche d'uso (solo con consenso) | Eventi d'uso anonimi, `device_id` | UE (Francoforte) | https://posthog.com/privacy |
| **Supabase** (Supabase, Inc.) | Database e archivio immagini dei contenuti (sola lettura) | Dati tecnici di connessione (IP) | EU (West EU — Irlanda) | https://supabase.com/privacy |
| **Expo / EAS** (650 Industries, Inc.) | Distribuzione aggiornamenti dell'App (OTA) | Dati tecnici di connessione (IP, info dispositivo) | USA | https://expo.dev/privacy |
| **Apple** (Apple Inc.) | Mappa su iOS (Apple Maps) e distribuzione tramite App Store | Dati tecnici della mappa, dati di download | Globale | https://www.apple.com/legal/privacy/ |
| **OpenStreetMap Foundation** | Tasselli mappa su Android (tile OSM) | Dati tecnici di connessione (IP) | UE/UK | https://wiki.osmfoundation.org/wiki/Privacy_Policy |
| **Google** (Google LLC) | Distribuzione tramite Google Play | Dati di download e installazione | Globale | https://policies.google.com/privacy |

Con i fornitori che agiscono come responsabili abbiamo in essere (o sottoscriviamo) un **accordo sul trattamento dei dati (DPA)** ai sensi dell'art. 28 GDPR.

---

## 7. Trasferimenti di dati fuori dall'Unione Europea

I dati di diagnostica (**Sentry**) e di statistica (**PostHog**) sono ospitati su **server situati nell'Unione Europea**.

Alcuni fornitori (es. **Expo**, **Apple**, **Google** e gli stessi Sentry/PostHog in quanto società statunitensi) possono trovarsi negli Stati Uniti o accedervi. In tali casi il trasferimento avviene nel rispetto del Capo V del GDPR, mediante **Clausole Contrattuali Standard** approvate dalla Commissione Europea e/o adesione al **Data Privacy Framework UE-USA**, oltre a misure supplementari adeguate. Puoi richiederci copia delle garanzie applicate scrivendo all'indirizzo del § 1.

---

## 8. Conservazione dei dati

- **Dati locali sul dispositivo** (preferiti, impostazioni, `device_id`): conservati finché non li elimini dall'App o disinstalli l'applicazione.
- **Diagnostica crash (Sentry):** conservata per un periodo limitato, di norma circa **90 giorni**.
- **Statistiche d'uso (PostHog):** conservate per il tempo necessario alle finalità statistiche e comunque non oltre **12 mesi**, dopodiché sono aggregate o cancellate.
- **Posizione e calendario:** non conservati da noi (vedi § 3).

Al termine dei periodi indicati i dati sono cancellati o resi anonimi in modo irreversibile.

---

## 9. I tuoi diritti

In qualità di interessato hai il diritto, nei limiti previsti dagli artt. 15-22 del GDPR, di:

- **accedere** ai tuoi dati e ottenerne copia;
- chiederne la **rettifica** o la **cancellazione** ("diritto all'oblio");
- chiedere la **limitazione** del trattamento;
- **opporti** al trattamento fondato sul legittimo interesse (es. diagnostica);
- ottenere la **portabilità** dei dati trattati sulla base del consenso o del contratto;
- **revocare il consenso** in qualsiasi momento (per le statistiche, direttamente dalle impostazioni dell'App), senza pregiudicare la liceità del trattamento precedente.

**Come esercitarli.** La maggior parte dei dati resta sul tuo dispositivo: puoi eliminarli in autonomia cancellando i preferiti, disattivando le statistiche o disinstallando l'App. Per i dati lato server (diagnostica/statistiche) puoi scriverci all'indirizzo del § 1. Poiché ti identifichiamo solo tramite un codice anonimo (`device_id`), per darti seguito potremmo chiederti di comunicarci tale codice, reperibile nella sezione Profilo dell'App: senza di esso potremmo non essere in grado di individuare i dati che ti riguardano (art. 11 GDPR).

**Reclamo all'Autorità di controllo.** Se ritieni che il trattamento violi il GDPR, hai il diritto di proporre reclamo al **Garante per la protezione dei dati personali** (Piazza Venezia 11, 00187 Roma — www.garante.it — garante@gpdp.it), oppure all'autorità dello Stato UE in cui risiedi.

---

## 10. Sicurezza

Adottiamo misure tecniche e organizzative adeguate a proteggere i dati. In particolare, tutte le comunicazioni tra l'App e i server avvengono tramite connessioni **cifrate (HTTPS/TLS)**. I dati che restano sul dispositivo sono protetti dai meccanismi di sicurezza del sistema operativo.

---

## 11. Processi decisionali automatizzati

**Non** effettuiamo alcun processo decisionale automatizzato, né profilazione che produca effetti giuridici o significativi nei tuoi confronti (art. 22 GDPR).

---

## 12. Minori

L'App **non è destinata a minori di 13 anni** (età del consenso digitale in Italia ai sensi dell'art. 2-quinquies del Codice Privacy). Non raccogliamo consapevolmente dati di minori di 13 anni. Se sei un genitore o tutore e ritieni che un minore ci abbia fornito dati, contattaci all'indirizzo del § 1 e provvederemo a cancellarli.

---

## 13. Distribuzione tramite gli store

L'App è distribuita tramite **Apple App Store** e **Google Play**. Il download, l'installazione e gli eventuali pagamenti sono gestiti da Apple e Google secondo le loro rispettive informative sulla privacy, su cui non abbiamo controllo.

---

## 14. Modifiche a questa informativa

Potremmo aggiornare questa informativa per riflettere modifiche all'App o agli obblighi di legge. La versione aggiornata sarà sempre disponibile a **https://alicefr1998-eng.github.io/csf-privacy-policy/** e, in caso di modifiche rilevanti, te ne daremo avviso all'interno dell'App. La data in cima al documento indica l'ultimo aggiornamento.

---

## 15. Contatti

Per qualsiasi domanda su questa informativa o sul trattamento dei tuoi dati:

- **Email:** chesifa.app@gmail.com
- **Titolare:** Alice Frugone, Italia

---

*Documento redatto in conformità al Regolamento (UE) 2016/679 (GDPR), al D.lgs. 196/2003 (Codice Privacy) come modificato dal D.lgs. 101/2018, e alla Direttiva 2002/58/CE (ePrivacy).*
