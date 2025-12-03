# GrafcetT Editor

**[GrafcetT Editor](https://github.com/tulliocarlassara/GrafcetT_Editor/releases)** è un ambiente grafico per la modellazione di sistemi sequenziali a stati (Sequential Function Chart) con transizioni condizionate.  
Dal diagramma genera automaticamente codice C++ per microcontrollori basato sulla libreria **[GrafcetT](https://github.com/tulliocarlassara/GrafcetT)**.
![](Immagine.png)

GrafcetT Editor è sviluppato in [Python](https://www.python.org/) e si appoggia alle librerie
[PySide6](https://doc.qt.io/qtforpython/), [SymPy](https://www.sympy.org/) e
[pyserial](https://pyserial.readthedocs.io/) per l’interfaccia grafica, l’elaborazione simbolica
e la comunicazione seriale.

### Caratteristiche principali

- Editor grafico per step, transizioni, azioni
- Tabella simboli con supporto a:
  - Flag
  - Input
  - Output
  - Timer
  - Counter
  - Altro (variabili definite dall’utente)
- Generazione automatica del codice C++
  - Struttura già pronta per essere integrata nel firmware
  - Nomi di variabili coerenti con quelli usati nel diagramma
- Inserimento codice C++ utente
  - Gestione guidata del codice C++ senza dover modificare manualmente il file generato
- Libreria di casi (`cases.json`)
  - Blocchi funzionali riutilizzabili (es. servo, sensori, ecc.)
  - Possibilità di estendere la libreria con casi personalizzati
- Supporto al debug
  - Visualizzazione grafica dello stato degli step
  - Visualizzazione delle variabili supportate

### Tecnologie utilizzate

GrafcetT Editor è realizzato utilizzando:

- **Python** – linguaggio principale dell’applicazione
- **PySide6 (Qt for Python)** – interfaccia grafica
- **SymPy** – manipolazione di espressioni simboliche
- **pyserial** – comunicazione seriale con i microcontrollori
- Altre librerie standard di Python

### Licenze

Il software GrafcetT Editor, nella forma in cui viene distribuito
(eseguibile e moduli Python compilati), è rilasciato sotto licenza **MIT**.
Il testo completo della licenza è incluso nel file `LICENSE.txt`.

L’applicazione utilizza librerie di terze parti:

- **PySide6 (Qt for Python)**
- **SymPy**
- **pyserial**

Per queste librerie e per l’implementazione di Python si applicano **le rispettive licenze**,
le cui copie sono incluse nella cartella `LICENSES`.
