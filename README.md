# 🕊️ Protocollo di Comunicazione Avanzata (Non per Piccioni)

## Introduzione al Secolo Corrente
### (O: Come smettere di usare i volatili e iniziare a vivere)
#### Sottotitolo per chi ha bisogno di tempo per capire
##### Ancora più piccolo, per chi sussurra
###### Livello 6, invisibile quasi quanto l'efficienza di un piccione

*Come si implementa: Da 1 a 6 simboli `#` seguiti da uno spazio. Più `#` metti, più il titolo diventa piccolo. Modificabile a piacere per creare gerarchie.*

---

<a name="ancora-piccione"></a>
*Come si implementa: La riga qui sopra è un'ancora HTML personalizzata `<a name="..."></a>`. Non si vede nel testo, ma ci permetterà di "saltare" a questo punto esatto del documento.*

### 1. Stili di Testo e Critiche Ricorrenti

Quando Pierluigi ci vede lavorare, usa sempre la solita frase:

> "Lo fai su GitHub?" 🙄

*Come si implementa: Il simbolo `>` all'inizio della riga crea una citazione (Blockquote). Se vai a capo e metti un altro `>`, la citazione continua. Perfetto per riportare le frasi storiche.*

Certo che lo facciamo su GitHub, Pierluigi. Altrimenti come potremmo avere:
* **Testo in grassetto** per le cose **veramente importanti** (come la connessione internet). *Sintassi: `**testo**` o `__testo__`.*
* _Testo in corsivo_ per i termini _tecnici_ che i pennuti non capiscono. *Sintassi: `*testo*` o `_testo_`.*
* ~~Lettere inviate via piccione~~ testo barrato per le tecnologie obsolete. *Sintassi: `~~testo~~`.*
* Formattazione chimica per l'acqua che diamo agli uccelli: H<sub>2</sub>O. *Sintassi: `<sub>testo</sub>` (pedice).*
* La nostra superiorità tecnologica elevata al quadrato: GitHub<sup>2</sup>. *Sintassi: `<sup>testo</sup>` (apice).*
* Cose che vanno <ins>assolutamente sottolineate</ins>. *Sintassi: `<ins>testo</ins>`.*

### 2. Codice vs. Tubi di Scappamento

Se devi mandare un messaggio, invece di legare un bigliettino alla zampa, noi usiamo comandi inline come `git push`. 
*Come si implementa: Un singolo backtick ( ` ) attorno alla parola. Utile per far risaltare comandi o percorsi di file all'interno di una frase.*

Se invece Danilo deve scrivere un protocollo di emergenza per quando il piccione si perde, fa così:

```python
def invia_messaggio_moderno(messaggio):
    if mezzo == "piccione":
        print("Errore 404: Volatile non trovato")
    else:
        return "Messaggio consegnato su GitHub in 0.01 secondi"
```
*Come si implementa: Tre backtick ( ``` ) per aprire il blocco, seguiti dal nome del linguaggio (es. `python`, `javascript`) per la colorazione della sintassi, e tre backtick per chiuderlo.*

### 3. I Colori del Piumaggio (Solo per Issue e Pull Request)

*Nota di Doppio Check: Pierluigi, se leggi questo in un file `.md` normale non vedrai i colori. Questa funzione è un'esclusiva delle Issue, delle Pull Request e delle Discussioni di GitHub.*

* HEX: `#808080` (Il grigio tristezza del tuo piccione)
* RGB: `rgb(255, 0, 0)` (Il colore della faccia di Danilo quando aspetti che arrivi la tua lettera)
* HSL: `hsl(120, 100%, 50%)` (Il verde speranza che il messaggio arrivi integro)

*Come si implementa: Inserendo il codice colore tra singoli backtick (es. `#808080`). Modificabile cambiando i valori esadecimali o numerici.*

### 4. Navigazione Veloce (Perché non abbiamo tempo da perdere)

Pierluigi, se ti perdi, ecco come usare i link:
* **Link esterno:** Vai a studiare su [Wikipedia: Piccione Viaggiatore](https://it.wikipedia.org/wiki/Piccione_viaggiatore). *Sintassi: `[Testo da cliccare](URL)`.*
* **Link di sezione:** Torna all'[Introduzione al Secolo Corrente](#introduzione-al-secolo-corrente). *Sintassi: `[Testo](#titolo-formattato-con-trattini)`. GitHub crea ancore automatiche per ogni titolo.*
* **Link all'ancora custom:** Clicca qui per [tornare alla citazione in alto](#ancora-piccione). *Sintassi: `[Testo](#nome-ancora-custom)`.*
* **Link relativo:** Leggi il nostro [Manuale di Volo](../docs/manuale_volo.md). *Sintassi: `[Testo](../percorso/del/file.md)`. Utile per collegare file dentro lo stesso repository senza usare link web assoluti.*

### 5. Gestione delle Interruzioni di Riga

Nei file Markdown, se vai a capo normalmente con Invio, GitHub spesso ignora lo spazio e unisce le frasi.  
Per andare a capo sul serio, ci sono tre modi:
1. Lasciare due spazi vuoti alla fine di questa riga.  
2. Mettere un backslash alla fine di questa riga.\
3. Usare il tag HTML `<br/>`<br/>così vai a capo con prepotenza.

### 6. Liste di Cose che GitHub fa meglio dei volatili

**Lista Non Ordinata:**
* Non deve mangiare.
* Non sporca il balcone di Danilo.
* Non viene intercettato dai falchi.
  * E non perde i dati (nidificazione!).

*Come si implementa: Usa `-` o `*` seguiti da uno spazio. Per nidificare, vai a capo e indenta con gli spazi (di solito 2 o 4).*

**Lista Ordinata (Procedure di Deploy):**
1. Salvatore scrive il codice.
2. Danilo fa la code review.
3. Pierluigi fischia al piccione (opzionale e inutile).

*Come si implementa: Numero seguito da punto e spazio (`1. `).*

**Lista di Attività (Task List):**
- [x] Abbandonare l'avifauna per la messaggistica.
- [x] Aprire un account su GitHub.
- [ ] Smettere di chiedere "Lo fai su GitHub?".

*Come si implementa: `- [ ]` per un'attività aperta, `- [x]` per una completata. Su GitHub queste caselle sono cliccabili e interattive!*

### 7. Risorse Visive e Sociali

Se non hai capito, ti metto un'immagine:

![Un bellissimo piccione che non sa usare Git](https://upload.wikimedia.org/wikipedia/commons/thumb/1/1d/Pigeon_in_flight.jpg/300px-Pigeon_in_flight.jpg)

*Come si implementa: Esattamente come i link, ma con un punto esclamativo davanti: `![Testo Alternativo se l'immagine non carica](URL_immagine)`.*

E se ci sono problemi, invece di lanciare segnali di fumo, apriamo una issue citandoti: Ehi @Pierluigi, guarda che la Issue #404 (Piccione Disperso) è ancora aperta. :bell:

*Come si implementa: `@username` per menzionare (manda una notifica!), `#numero` per linkare una Issue o Pull Request del repository corrente, e `:nome_emoji:` per le emoji.*

### 8. L'Arte dell'Evasione (Escaping)

Se vuoi scrivere un hashtag # senza che diventi un titolo enorme, o degli asterischi \*così\* senza che diventino corsivo, usa il backslash `\` prima del carattere.

*Come si implementa: `\# Testo` oppure `\*Testo\*`.*