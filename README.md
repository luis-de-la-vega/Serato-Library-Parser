# 🎧 Serato Library Parser
**Serato Library Parser** è uno strumento avanzato che permette di leggere e convertire il file **`database V2`** di Serato DJ Pro / Lite in formati aperti:

- ✔ JSON (lettura semplice)
- ✔ XML stile Rekordbox (compatibilità estesa)
- ✔ Operazione *read-only* (non modifica file di Serato)

Perfetto per DJ, programmatori, sviluppatori di tool musicali, software engineer e per chi ha bisogno di estrarre i metadati del proprio archivio musicale.

---

# 📂 Funzionalità principali

### ✔ Estrai automaticamente:
- Percorso reale della traccia
- Artista
- Titolo
- Album
- BPM
- Key (tonalità)
- Genere
- Durata
- Bitrate
- Altri metadati supportati da `seratolibraryparser`

### ✔ Converti verso:
- **JSON**
- **XML Rekordbox-like**

### ✔ Compatibilità garantita con:
- Serato DJ Lite
- Serato DJ Pro
- Serato Studio (parziale)

### ✔ Non richiede Serato installato

### ✔ Nessuna scrittura o modifica sui file originali

---

# ⚠️ Limitazioni note
Questo tool **NON** esporta:
- crates `.crate`
- smart crates `.scrate`
- cue points
- beatgrid
- waveform
- file di analisi Serato

Funziona solo sul contenuto presente nel file **`database V2`**.
Il file "database V2" deve essere nella stessa cartella root di questo tool

---

# 🧱 Requisiti

## Software necessario
- **Node.js 18+**
  - Download: https://nodejs.org/
 
# Installa
Per installare questo tool basta eseguire questo script
```bash
Install.bat
```


# ✔ Esportare in JSON
Esegui il file 

```bash
Export_Library_Serato_JSON.bat
```
Verrà generato un file chiamato `serato-library.json`

# ✔ Esportare in XML (Rekordbox-like)
Esegui il file 
```bash
Export_Library_Serato_XML.bat
```
Verrà generato un file chiamato `serato-library.xml`

# 🔐 Privacy

Questo tool:
- non invia dati online
- non traccia nulla
- non legge file audio
- non modifica file Serato

È sicuro per uso personale e professionale.

# 👤 Autore

## LuisDev_
