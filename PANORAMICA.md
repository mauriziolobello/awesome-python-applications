# Panoramica: Awesome Python Applications

## Cos'è questo progetto

**Awesome Python Applications** è una raccolta curata di **426 applicazioni Python open-source** suddivise per categoria tematica. L'obiettivo è offrire agli sviluppatori un catalogo di applicazioni reali e funzionanti in produzione, utili come casi di studio per imparare pattern e pratiche concrete. Il progetto è generato automaticamente da un file strutturato (`projects.yaml`) tramite lo strumento [apatite](https://github.com/mahmoud/apatite).

---

Categoria	N° app	Esempi notevoli
Internet	45	youtube-dl, Pi-Hole, Searx, Reddit
Audio	17	Beets, MusicBrainz Picard, Mopidy
Video	8	OpenShot, Flowblade, Tautulli
AI/ML	4	MLflow, DVC, Aim
Grafica	21	FreeCAD, Cura, MyPaint, Octoprint
Giochi	10	Lutris, PyChess, Unknown Horizons
Produttività	27	BorgBackup, VisiData, Ranger, nvda
Organizzazione	45	Calibre, Taiga, Paperless, beancount
Comunicazione	35	Zulip, SecureDrop, Weblate
Educazione	9	Anki, Open edX, Kolibri
Scienza	24	Sage Math, Orange, Manim
CMS	11	Wagtail, Plone, Saleor
ERP	5	Odoo, ERPNext, Tryton
Siti Statici	9	Pelican, Nikola, Lektor
Dev	187	Ansible, Sphinx, pip, Docker Compose, Sentry, Jupyter
Misc	13	Home Assistant, qtile, Guake

---

## Categorie e applicazioni principali

### 🌐 Internet *(45 applicazioni)*

Applicazioni per la navigazione, archiviazione e gestione di contenuti web.

| Applicazione | Descrizione |
|---|---|
| **ArchiveBox** | Archivio web self-hosted: salva localmente pagine HTML, PDF, video e repository git da Pocket, browser, ecc. |
| **Deluge** | Client BitTorrent leggero e multipiattaforma. |
| **httpie** | Client HTTP da riga di comando con supporto JSON e syntax highlighting. |
| **Pi-Hole** | Blocca pubblicità e tracker a livello di rete tramite DNS sinkhole. |
| **youtube-dl** | Scarica video e audio da YouTube e centinaia di altri siti. |
| **Searx** | Metastrumento di ricerca self-hosted, aggrega risultati da 70+ servizi. |
| **NewsBlur** | Lettore di notizie web personale. |
| **Reddit** | Il celebre social news forum (repo archivio 2017). |
| **ZeroNet** | Siti web aperti, liberi e non censurabili basati su Bitcoin e BitTorrent. |
| **Dispatch** | Gestione degli incidenti con notifiche e task management. Usato da Netflix. |

---

### 🎵 Audio *(17 applicazioni)*

Strumenti per la gestione, riproduzione e analisi audio.

| Applicazione | Descrizione |
|---|---|
| **Beets** | Gestore di librerie musicali da CLI con rilevamento duplicati, tag e integrazione MusicBrainz. |
| **MusicBrainz Picard** | Identifica, tagga e organizza automaticamente album musicali. |
| **Mopidy** | Server musicale estensibile con plugin per numerosi servizi. |
| **GNU Radio** | Toolkit per implementare radio software-defined e sistemi di elaborazione del segnale. |
| **Funkwhale** | Ascolto e condivisione di musica in una rete decentralizzata e aperta. |
| **Friture** | Visualizza e analizza audio live in tempo reale (spettrogramma, scope, ecc.). |
| **Whipper** | Ripper di CD audio da CLI ottimizzato per l'accuratezza. |
| **Stargate DAW** | Digital Audio Workstation completo con suite di plugin strumentali ed effetti. |

---

### 🎬 Video *(8 applicazioni)*

Software per editing, streaming e gestione di contenuti video.

| Applicazione | Descrizione |
|---|---|
| **OpenShot** | Editor video multipiattaforma (Linux, macOS, Windows). |
| **Flowblade** | Editor video non lineare multitrack per Linux. |
| **Pitivi** | Editor video non lineare per Linux, basato su GStreamer. |
| **Tautulli** | Monitor web per Plex Media Server. |
| **Open Streaming Platform** | Server self-hosted per streaming e registrazione video, alternativa a Twitch/YouTube. |
| **Vidcutter** | Strumento grafico e CLI per tagliare e unire video. |

---

### 🤖 AI/ML *(4 applicazioni)*

Piattaforme per esperimenti di machine learning e gestione dati.

| Applicazione | Descrizione |
|---|---|
| **MLflow** | Workflow end-to-end per ML: tracking, packaging e deploy. Sviluppato da Databricks. |
| **DVC** | Controllo di versione per i dati usati in progetti ML. |
| **Aim** | Tracker self-hosted per esperimenti ML, gestisce decine di migliaia di run. |
| **Polyaxon** | Piattaforma web per gestione esperimenti ML su Kubernetes (TensorFlow, PyTorch, Keras). |

---

### 🎨 Grafica *(21 applicazioni)*

Applicazioni per grafica 2D/3D, OCR, gestione immagini e stampa 3D.

| Applicazione | Descrizione |
|---|---|
| **FreeCAD** | Modellatore 3D parametrico CAD generico con supporto BIM e FEM. |
| **Cura** | Software desktop per preparazione e controllo della stampa 3D. |
| **Meshroom** | Pipeline fotogrammetrica per creare modelli 3D da fotografie. |
| **MyPaint** | Editor raster per pittori digitali, focalizzato sulla pittura. |
| **MakeHuman** | Software 3D per prototipare umanoidi foto-realistici. |
| **Photonix** | Gestione foto web con riconoscimento oggetti, consapevolezza spaziale e analisi colori. |
| **Thumbor** | Servizio di thumbnail fotografiche con ritaglio intelligente. |
| **Octoprint** | Controller web per stampanti 3D consumer. |

---

### 🎮 Giochi *(10 applicazioni)*

Client di gioco, launcher e strumenti legati al gaming.

| Applicazione | Descrizione |
|---|---|
| **Lutris** | Piattaforma gaming per GNU/Linux con interfaccia unificata. |
| **PyChess** | Client di scacchi avanzato per partite casuali e competitive. |
| **Unknown Horizons** | Gioco di strategia in tempo reale con economia e city building (simile ad Age of Empires). |
| **PySolFC** | Raccolta di solitaire e giochi di carte, altamente portabile. |
| **Frets on Fire X** | Gioco musicale ritmico altamente personalizzabile (chitarra, basso, batteria, voce). |

---

### ⚡ Produttività *(27 applicazioni)*

Strumenti per automazione, backup, gestione file e visualizzazione dati.

| Applicazione | Descrizione |
|---|---|
| **BorgBackup** | Sistema di backup con deduplicazione e cifratura opzionale. |
| **Ranger** | File manager TUI ispirato a vim. |
| **VisiData** | Multitool interattivo da terminale per esplorare e analizzare dataset. |
| **Superset** | Esplorazione dati, visualizzazione e business intelligence web. |
| **Redash** | Visualizzazione dati e dashboard per business intelligence. |
| **OCRmyPDF** | Aggiunge un layer OCR ai PDF scansionati per abilitare ricerca e selezione testo. |
| **Glances** | Alternativa a top/htop cross-platform con panoramica delle risorse di sistema. |
| **Plover** | Servizio di background per la traduzione automatica della stenografia. |
| **nvda** | Screen reader potente per Windows (Non-Visual Desktop Access). |

---

### 🗂️ Organizzazione *(45 applicazioni)*

Applicazioni per la gestione di documenti, libri, eventi, finanza e dati personali.

| Applicazione | Descrizione |
|---|---|
| **Calibre** | Gestore di ebook per visualizzazione, conversione e catalogazione. |
| **Paperless** | Scansiona, indicizza e archivia documenti cartacei con OCR e ricerca. |
| **Mayan** | Sistema di gestione documentale web con workflow, RBAC e REST API. |
| **beancount** | Contabilità in partita doppia con linguaggio plain text. |
| **Taiga** | App web per gestione progetti con metodologie agili. |
| **Mealie** | Server self-hosted per gestione ricette con UI ricca e backup automatici. |
| **Indico** | Gestione eventi del CERN (convegni, registrazioni, call for papers). |
| **Gramps** | Software di genealogia per hobbysti e genealogisti professionisti. |
| **CherryTree** | Blocco note gerarchico wiki-like con testo ricco e syntax highlighting. |

---

### 💬 Comunicazione *(35 applicazioni)*

Piattaforme per messaggistica, email, wiki, votazioni e collaborazione.

| Applicazione | Descrizione |
|---|---|
| **Zulip** | Server di chat con supporto per conversazioni threaded. |
| **Synapse** | Server di riferimento per il protocollo di chat distribuito matrix.org. |
| **Mailman** | Il listserv originale, per gestire iscrizioni e archivi di discussione. |
| **SecureDrop** | Sistema per whistleblower per inviare documenti anonimi a organizzazioni giornalistiche. |
| **Weblate** | Strumento di localizzazione web con integrazione al controllo versione. |
| **MoinMoin** | Il wiki di Python, usato per il wiki ufficiale Python. |
| **Gajim** | Client di messaggistica istantanea cross-platform per il protocollo XMPP. |
| **GlobaLeaks** | Applicazione web per initiative di whistleblowing sicure e anonime. |
| **OnionShare** | Trasferimento file sicuro e anonimo tramite servizi Tor. |

---

### 📚 Educazione *(9 applicazioni)*

Applicazioni per e-learning, flashcard e ambienti didattici.

| Applicazione | Descrizione |
|---|---|
| **Anki** | Applicazione desktop per flashcard e memorizzazione con spaced repetition. |
| **Mnemosyne** | Programma di flashcard con ripetizione spaziata per memorizzazione efficiente. |
| **Open edX Platform** | Piattaforma per provider di educazione online (alimenta edX). |
| **Kolibri** | App web di apprendimento per comunità a basse risorse (scuole rurali, campi profughi). |
| **NBGrader** | Crea, assegna e valuta compiti in forma di notebook Jupyter. |

---

### 🔬 Scienza *(24 applicazioni)*

Strumenti per bioinformatica, matematica, fisica, analisi dati e visualizzazione scientifica.

| Applicazione | Descrizione |
|---|---|
| **Sage Math** | Sistema di algebra computerizzata cross-platform con copertura di numerose aree della matematica. |
| **Orange** | Software di data mining per analisi e visualizzazione interattiva dei dati. |
| **CellProfiler** | Esplorazione e analisi interattiva di set di immagini biologiche. |
| **Manim** | Motore di animazione per video matematici esplicativi (3blue1brown). |
| **Galaxy** | Piattaforma web per ricerca computazionale riproducibile in bioinformatica. |
| **Veusz** | Grafici scientifici 2D e 3D per pubblicazioni (PDF/SVG). |
| **CKAN** | Sistema di gestione dati usato da portali come data.gov e europeandataportal.eu |

---

### 📰 CMS *(11 applicazioni)*

Sistemi di gestione dei contenuti web.

| Applicazione | Descrizione |
|---|---|
| **Wagtail** | CMS Django flessibile focalizzato su usabilità. |
| **Django-CMS** | CMS enterprise basato su Django con versioning e supporto multi-sito. |
| **Plone** | CMS enterprise estensibile costruito su Zope. |
| **Saleor** | Storefront e-commerce modulare e ad alte performance (Django + GraphQL + React). |
| **Mezzanine** | Piattaforma CMS flessibile e consistente basata su Django. |
| **Pretix** | Software di ticketing web con supporto pagamenti e reportistica. |

---

### 🏭 ERP *(5 applicazioni)*

Sistemi di pianificazione delle risorse aziendali.

| Applicazione | Descrizione |
|---|---|
| **Odoo** | ERP e CRM web con decine di moduli e migliaia di app aggiuntive. |
| **ERPNext** | ERP web con contabilità, inventario, CRM, vendite, HR e project management. |
| **Tryton** | ERP web modulare per aziende di tutte le dimensioni. |
| **ERP5** | ERP/CRM/DMS/Big Data web con centinaia di moduli integrati. |
| **Frepple** | Pianificazione della supply chain per produzione e scheduling. |

---

### 🌐 Siti Statici *(9 applicazioni)*

Generatori di siti web statici.

| Applicazione | Descrizione |
|---|---|
| **Pelican** | Generatore di siti statici da CLI con supporto Markdown e reStructuredText. |
| **Nikola** | Generatore di siti statici con rebuild incrementale e supporto notebook Jupyter. |
| **Lektor** | Generatore di siti statici con admin console e app desktop minimale. |
| **Hyde** | Generatore di siti statici, controparte Python di Jekyll. |
| **Cactus** | Generatore di siti statici con template Django. |

---

### 💻 Dev *(187 applicazioni)*

La categoria più vasta, con strumenti per lo sviluppo software nelle seguenti sottocategorie:

#### SCM — Controllo versione *(18)*
Forge software, client Git/Mercurial/SVN e sistemi di issue tracking.
Esempi: **Mercurial**, **GNU Bazaar**, **Kallithea**, **Trac**, **Launchpad**, **Plane**

#### Code Review *(5)*
Strumenti per diff, merge e revisione del codice.
Esempi: **Meld**, **Review Board**, **Diffoscope**, **SQLFluff**

#### Storage *(20)*
Database, backup, sincronizzazione e file system cloud.
Esempi: **EdgeDB**, **FreeNAS**, **Datasette**, **pgcli**, **mycli**, **Seafile**, **TahoeLAFS**

#### Ops — Operazioni *(28)*
Automazione, monitoring, orchestrazione e gestione infrastruttura.
Esempi: **Ansible**, **Airflow**, **OpenStack**, **Salt Stack**, **Supervisor**, **fail2ban**, **Spinnaker**

#### Security *(30)*
Strumenti per sicurezza offensiva e difensiva, honeypot, analisi malware.
Esempi: **MITMproxy**, **sqlmap**, **Cowrie**, **GRR Rapid Response**, **OpenSnitch**, **Spiderfoot**

#### Docs *(7)*
Generatori e piattaforme di documentazione.
Esempi: **Sphinx**, **mkdocs**, **readthedocs.org**, **Kuma** (MDN)

#### Editor *(13)*
IDE, editor di testo e strumenti di formattazione codice.
Esempi: **Jupyter Notebook**, **Spyder IDE**, **Thonny**, **Black**, **mu editor**

#### Package Managers *(11)*
Gestori di pacchetti per vari linguaggi e sistemi operativi.
Esempi: **pip**, **Conda**, **Poetry**, **pipenv**, **dnf**, **Portage**

#### Package Repositories *(5)*
Hosting e mirroring di repository di pacchetti.
Esempi: **Warehouse** (PyPI), **devpi**, **Bandersnatch**

#### Build *(13)*
Sistemi di build e automazione del processo di compilazione.
Esempi: **Meson**, **SCons**, **buildbot**, **Pants**, **Snapcraft**, **PlatformIO Core**

#### Shell *(3)*
Shell alternative e linguaggi di scripting avanzati.
Esempi: **Xonsh**, **Oil**, **Ergonomica**

#### Altri progetti Dev *(37)*
Debugger, simulatori di rete, analisi, strumenti CLI e molto altro.
Esempi: **Docker Compose**, **Sentry**, **IPython**, **Cython**, **Robot Framework**, **LocalStack**, **Locust**

---

### 🎲 Misc *(13 applicazioni)*

Applicazioni varie che non rientrano nelle categorie precedenti.

| Applicazione | Descrizione |
|---|---|
| **Home Assistant** | Piattaforma di home automation che privilegia il controllo locale e la privacy. |
| **CourtListener** | Interfaccia di ricerca e API su milioni di opinioni legali e registrazioni di udienze. |
| **qtile** | Window manager tiling piccolo, flessibile e scriptabile. |
| **Guake** | Terminale drop-down per GNOME ispirato alle console dei videogiochi FPS. |
| **uMap** | App web per creare mappe personalizzate con layer OpenStreetMap. |
| **Xpra** | Server e client per display remoto cross-platform. |

---

## Struttura del repository

```
awesome-python-applications/
├── projects.yaml          # Fonte dati strutturata con tutti i progetti
├── README.md              # Lista generata automaticamente
├── CHANGELOG.md           # Applicazioni aggiunte di recente
├── BY_PLATFORM.md         # Lista ordinata per piattaforma (Linux, Windows, Mac, ecc.)
├── archive.yaml           # Progetti archiviati / non più mantenuti
├── revisit.yaml           # Progetti da rivalutare
├── templates/             # Template per la generazione dei file Markdown e Atom
└── notebooks/             # Notebook Jupyter per analisi e statistiche
```

---

*Generato il 1° aprile 2026 — basato su [mahmoud/awesome-python-applications](https://github.com/mahmoud/awesome-python-applications)*
