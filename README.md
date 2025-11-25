# GrafcetT Editor

**[GrafcetT Editor](https://github.com/tulliocarlassara/GrafcetT_Editor/releases)** è un ambiente grafico per la modellazione di sistemi sequenziali a stati (Sequential Function Chart) con transizioni condizionate.  
Dal diagramma genera automaticamente codice C++ per microcontrollori basato sulla libreria **[GrafcetT](https://github.com/tulliocarlassara/GrafcetT)**.
![](Immagine.png)

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
- Libreria di casi (cases.json)
  - Blocchi funzionali riutilizzabili (es. servo, sensori, ecc.)
  - Possibilità di estendere la libreria con casi personalizzati
- Supporto al debug
  - Visualizzazione grafica dello stato degli step
  - Visualizzazione delle varibili supportate
