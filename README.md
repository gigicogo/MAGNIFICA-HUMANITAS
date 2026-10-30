# 📜 MAGNIFICA-HUMANITAS — Un esperimento di vibe coding

**MAGNIFICA-HUMANITAS** è un percorso di *vibe coding* per leggere e interpretare l’enciclica *Magnifica Humanitas* di Papa Leone XIV, osservando come diversi strumenti di IA generativa trasformino lo stesso prompt in siti web navigabili.

Il progetto non vuole sostituire la lettura del documento originale: vuole mostrare come l’AI possa aiutare a organizzare contenuti complessi in un percorso esplorativo, mantenendo sempre il collegamento alla fonte ufficiale.

<img width="1698" height="751" alt="Screenshot 2026-10-30 alle 17 41 46" src="https://github.com/user-attachments/assets/3b3d0dd4-45d1-48a4-a5da-5afb4c2c7898" />



## 🎯 L’idea

Ho scritto un prompt articolato per trasformare l’enciclica in un sito web a sezioni, con:

- titoli evocativi;
- abstract sintetici;
- un filo narrativo tra le sezioni;
- query per immagini rappresentative;
- una struttura navigabile e accessibile.

Lo stesso prompt è stato poi passato a diversi strumenti di vibe coding, per confrontare come ciascun modello interpreta le istruzioni, organizza i contenuti e costruisce l’interfaccia.

## 🧭 Il filo conduttore

Il percorso segue la domanda centrale dell’enciclica:

> «Dove stiamo andando? Quale città vogliamo costruire — la torre di Babele o la nuova Gerusalemme?»

La struttura proposta si sviluppa in tre movimenti:

1. **Radici** — chi siamo e che cosa ci è stato consegnato: dignità, Vangelo e dottrina sociale.
2. **Sfide** — che cosa minaccia l’umano oggi: IA, tecnocrazia, postumanesimo e guerra.
3. **Costruzione** — come rispondere insieme: verità, lavoro, libertà, amore e pace.

## 🗂️ Struttura del sito

Il prompt definisce nove sezioni:

| Sezione | Titolo |
|---:|---|
| 0 | La Magnifica Umanità — Un’enciclica per il nostro tempo |
| 1 | Babele o Gerusalemme? La scelta del nostro tempo |
| 2 | 135 anni di pensiero vivo: dalla *Rerum Novarum* a oggi |
| 3 | L’essere umano: immagine di Dio, mai strumento |
| 4 | Il potere digitale: promesse, rischi e responsabilità |
| 5 | Transumano o pienamente umano? La risposta cristiana |
| 6 | Tre pilastri per un’era digitale a misura d’uomo |
| 7 | La civiltà dell’amore contro la cultura della potenza |
| 8 | Costruttori di comunione, non architetti di Babele |

Ogni sezione prevede un abstract sintetico, una citazione dal testo, una query per l’immagine e un collegamento narrativo con la sezione successiva.

## 🤖 Metodo di lavoro

Il metodo è quello del **vibe coding**:

1. Analizzare il documento originale.
2. Costruire un prompt strutturato con obiettivo, contesto, struttura, design e vincoli.
3. Passare lo stesso prompt a più strumenti AI.
4. Confrontare i siti generati.
5. Valutare coerenza, fedeltà alla fonte, navigabilità e qualità dell’esperienza.

Il prompt è disponibile nel repository e può essere copiato, scaricato e modificato liberamente:

📄 [prompt-magnifica-humanitas.md](prompt-magnifica-humanitas.md)

## 🌐 Risultati generati

Lo stesso prompt è stato utilizzato con diversi strumenti. Questi sono i risultati pubblicati:

| Strumento | Risultato |
|---|---|
| ChatGPT + AppDeploy | [Apri la versione generata](https://5823cb30e4d840f3b1.v2.appdeploy.ai/) |
| Claude Artifact | [Apri l’artifact](https://claude.ai/public/artifacts/cd22ab1e-2831-4864-b5f1-59928909338d) |
| Gemini | [Apri la conversazione](https://gemini.google.com/share/83cac369766a) |
| Google AI Studio | [Apri la versione generata](https://magnifica-humanitas-33404691356.europe-west2.run.app) |
| Qwen | [Apri la versione HTML](https://www.gigicogo.it/Qwen_html.html) |
| Lovable | [Apri la versione generata](https://humanitas-navigator.lovable.app/) |

Nel repository sono presenti anche alcuni file HTML generati, utili per confrontare direttamente le diverse soluzioni:

- [`Claude-magnifica-humanitas.html`](Claude-magnifica-humanitas.html)
- [`Gemini_ sito_enciclica_magnifica_humanitas.html`](Gemini_%20sito_enciclica_magnifica_humanitas.html)
- [`Qwen_html.html`](Qwen_html.html)

## 🔗 Fonte ufficiale

Il progetto rimanda sempre al documento originale pubblicato su Vatican.va:

🏛️ [Leggi *Magnifica Humanitas* su Vatican.va](https://www.vatican.va/content/leo-xiv/it/encyclicals/documents/20260515-magnifica-humanitas.html)

Il sito generato deve mantenere questo collegamento in modo visibile, per garantire trasparenza della fonte e rispetto del testo originale.

## 💻 Come usare il progetto

Puoi usare questo repository in tre modi:

- **Come esempio di vibe coding**, per vedere come uno stesso prompt produce risultati diversi.
- **Come modello di prompt**, copiando e adattando `prompt-magnifica-humanitas.md` a un altro testo lungo o complesso.
- **Come laboratorio di confronto**, analizzando come i diversi strumenti interpretano struttura, design e contenuti.

### Clonare il repository

```bash
git clone [https://github.com/gigicogo/MAGNIFICA-HUMANITAS.git](https://github.com/gigicogo/MAGNIFICA-HUMANITAS.git)
cd MAGNIFICA-HUMANITAS
```

## 🛠️ Struttura del repository

```text
MAGNIFICA-HUMANITAS/
├── prompt-magnifica-humanitas.md                        # Prompt completo e modificabile
├── Claude-magnifica-humanitas.html                      # Versione generata con Claude
├── Gemini_ sito_enciclica_magnifica_humanitas.html      # Versione generata con Gemini
├── Qwen_html.html                                       # Versione generata con Qwen
└── README.md                                            # Documentazione del progetto
```

## ⚠️ Note e limiti

Le versioni generate dagli strumenti AI sono esperimenti, non prodotti editoriali definitivi.

- Possono contenere semplificazioni, interpretazioni parziali o scelte grafiche diverse.
- Non sostituiscono la lettura diretta dell’enciclica.
- Non vanno considerate approvazioni dottrinali, teologiche o istituzionali.
- Il testo originale su Vatican.va resta la fonte di riferimento.

## 🧪 Possibili evoluzioni

- Aggiunta di una griglia di confronto tra le versioni generate.
- Valutazione sistematica di fedeltà, chiarezza, navigabilità e accessibilità.
- Versione multilingua del sito.
- Timeline interattiva della dottrina sociale della Chiesa.
- Mappa tematica dei concetti principali.
- Nuove generazioni con altri strumenti di vibe coding.

## 🤝 Contribuire

Sono benvenuti suggerimenti su nuovi strumenti da testare, miglioramenti del prompt, analisi comparative e segnalazioni di problemi nelle versioni generate.

1. Apri una Issue per proporre un’idea o segnalare un problema.
2. Oppure apri una Pull Request con una modifica o un nuovo esempio.
3. Se aggiungi una nuova generazione, indica sempre strumento, link e eventuali file HTML inclusi.

---

## 📄 Licenza

Da definire: si suggerisce una licenza aperta (es. MIT o CC BY 4.0) per favorire il riuso da parte di altri formatori o altri enti. Sostituisci questo paragrafo con il testo della licenza scelta e il file `LICENSE` del repo.

## 👤 Autore e contesto

**Gianluigi Cogo**  
Content creator e technical writer interessato ad AI generativa, automazioni, viaggi e strumenti digitali. Consulente e docente sui temi dell’IA generativa nella Pubblica Amministrazione.

Il progetto nasce come esercitazione di sperimentazione e divulgazione sull’uso dell’AI generativa per esplorare testi complessi. Per info sui miei percorsi e contenuti, contattami usando i social qui sotto.

- 📮 **Newsletter:** [gigicogo.substack.com](https://gigicogo.substack.com)
- 📝 **Blog:** [medium.com/webeconoscenza](https://medium.com/webeconoscenza)
- ▶️ **YouTube:** [youtube.com/@gigicogo](https://youtube.com/@gigicogo)
- 💼 **LinkedIn:** [linkedin.com/in/gigicogo](https://www.linkedin.com/in/gigicogo)
