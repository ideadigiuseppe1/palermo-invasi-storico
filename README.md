# Analisi dei Volumi degli Invasi Idrici di Palermo (2022-2026)

Questo repository raccoglie e standardizza i dati storici relativi ai volumi d'acqua invasati nelle dighe che alimentano la città di Palermo e la sua provincia. L'obiettivo è rendere queste informazioni accessibili, trasparenti e facilmente utilizzabili per analisi scientifiche, giornalismo investigativo e applicazioni di pubblica utilità.

## 📌 Informazioni sui Dati
* **Contesto:** Monitoraggio delle risorse idriche e dello stato di riempimento dei bacini.
* **Unità di Misura:** Milioni di metri cubi ($Mm^3$).
* **Copertura Temporale:** Dal 2022 al 2026.
* **Licenza:** Open Data. I dati sono liberi, aperti e riutilizzabili da chiunque.

## 🏢 Fonti Originali
I dati grezzi sono raccolti e pubblicati ufficialmente dall'**Autorità di Bacino del Distretto Idrografico della Sicilia**. Di seguito i link istituzionali alle fonti anno per anno:

* [Invasi 2022](https://www.regione.sicilia.it/istituzioni/regione/strutture-regionali/presidenza-regione/autorita-bacino-distretto-idrografico-sicilia/volumi-invasi-anno-2022)
* [Invasi 2023](https://www.regione.sicilia.it/istituzioni/regione/strutture-regionali/presidenza-regione/autorita-bacino-distretto-idrografico-sicilia/volumi-invasi-anno-2023)
* [Invasi 2024](https://www.regione.sicilia.it/istituzioni/regione/strutture-regionali/presidenza-regione/autorita-bacino-distretto-idrografico-sicilia/volumi-invasi-anno-2024)
* [Invasi 2025](https://www.regione.sicilia.it/istituzioni/regione/strutture-regionali/presidenza-regione/autorita-bacino-distretto-idrografico-sicilia/volumi-invasi-anno-2025)
* [Invasi 2026](https://www.regione.sicilia.it/istituzioni/regione/strutture-regionali/presidenza-regione/autorita-bacino-distretto-idrografico-sicilia/volumi-invasi-anno-2026)

---

## 💡 Idee di Progetto e Casi d'Uso
Questi dati si prestano a molteplici sviluppi. Chiunque è invitato a usarli per creare:

### 1. Dashboard Interattive per i Cittadini
Sviluppare applicazioni web (es. Streamlit, Shiny, PowerBI) che traducano tabelle complesse in grafici semplici. Aiutare la cittadinanza a visualizzare in tempo reale lo stato dell'emergenza idrica a Palermo.

### 2. Monitoraggio dei Trend della Siccità
Analizzare l'andamento storico stagionale per calcolare la velocità di svuotamento dei bacini nei mesi estivi e i tassi di recupero invernali anno su anno.

### 3. Correlazione con Dati Pluviometrici (Incrocio Dati)
Incrociare i volumi degli invasi con i dati delle precipitazioni piovane nelle zone geografiche dei bacini. Questo permette di evidenziare anomalie matematiche: se piove molto ma l'invaso non si riempie, potrebbero esserci problemi strutturali o dispersioni.

### 4. Giornalismo Investigativo e Trasparenza (Anti-corruzione)
Verificare eventuali anomalie di gestione, malfunzionamenti tecnici o speculazioni (es. dinamiche legate a mercati paralleli dell'acqua o infiltrazioni mafiose nella gestione delle autobotti e delle condotte). I dati pubblici sono il primo strumento di controllo sociale contro i monopoli e la cattiva gestione della cosa pubblica.

### 5. Algoritmi Predittivi per il Razionamento
Utilizzare modelli di intelligenza artificiale e serie temporali (Machine Learning) per stimare l'autonomia residua d'acqua della città, permettendo di pianificare i razionamenti in modo predittivo e meno emergenziale.

### 6. Studio delle Perdite di Rete e Connessioni
Incrociare i volumi prelevati dalle dighe con i volumi effettivamente fatturati o distribuiti dall'azienda municipalizzata (AMAP), calcolando la percentuale esatta di acqua dispersa lungo la rete idrica urbana.

---

## 🤝 Come Contribuire
Se hai ripulito i dati, creato uno script di analisi o sviluppato una visualizzazione:
1. Apri una **Issue** per segnalare anomalie o proporre idee.
2. Invia una **Pull Request** per aggiungere i tuoi script (Python, R, SQL) o i dati convertiti in formato `.csv`.

---
Sono state categoricamente escluse le stazioni di Castelbuono, Gangi, Palermo, Petralia Sottana, Polizzi Generosa e Sclafani Bagni. Sebbene facciano parte della rete di monitoraggio regionale, la pioggia registrata in queste località defluisce in bacini idrografici differenti e non contribuisce all'apporto idrico degli invasi oggetto dello studio (Garcia, Piana degli Albanesi, Poma, Prizzi, Rosamarina, Scanzano).

