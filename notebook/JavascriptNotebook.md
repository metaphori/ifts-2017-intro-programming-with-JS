
# Notebook

Questo "quaderno" è un supporto per questo modulo IFTS di introduzione alla programmazione nel linguaggio JavaScript.

Pagine relative alle lezioni:

* **[Lezione 31/01/2017](#lezione-3101)**
* [Lezione 30/01/2017](#lezione-3001)
* [Lezione 27/01/2017](#lezione-2701)
* [Lezione 26/01/2017](#lezione-2601) 

# Lezioni

<a name="lezione-2601"></a>

---------------------------------------------------------

## Lezione 1:  26/01/2017

**Comunicazione di servizio**: Pianini ha pubblicato, nel sito del modulo precedente, un testo di esame con cui potrete esercitatvi.

Sommario

* Presentazioni
* Introduzione al modulo
* Rudimenti di ingegneria del software
* Paradigmi di programmazione
* Presentazione di JavaScript

### i) Presentazioni

* **Chi sono**: Roberto Casadei, dottorando in Computer Science & Engineering all'Università di Bologna 
* **Chi siete?**
    - Competenze "al computer"
    - Esperienza con la programmazione
    - Esperienza con linguaggi imperativi/object-oriented
    - Esperienza con JavaScript
* Descrizione di questo sito.

### ii) Descrizione modulo (prima parte)

Corso di introduzione alla programmazione

* Pragmatico, operativo, abilitante, di base

#### Obiettivi

* Alla fine del modulo, si è in grado di comprendere e scrivere piccoli programmi, già orientati a contesti applicativi specifici (ad es. web)

#### Modalità

* Teoria minimale e approccio pratico

#### Contenuti: panoramica

* Rudimenti: software e programmazione
* Impostazione di un ambiente per lo sviluppo e l'esecuzione di programmi
* **Basi della programmazione in JavaScript**
* Da JavaScript a Java/C#: cenni

#### Risorse

Risorse utilizzate in questo modulo:

* http://www.html.it/guide/guida-javascript-di-base/ -- in italiano, taglio introduttivo

Reference su JavaScript:

* https://developer.mozilla.org/it/docs/Web/JavaScript/Reference
* http://www.w3schools.com/jsref/

Risorse ulteriori per approfondimenti:

* Sulla programmazione a oggetti in JavaScript: *The Principles of Object-Oriented JavaScript*
* Sulla versione più recente di JavaScript: *Understanding ECMAScript 6*

Risorse per esercizi:

* http://eloquentjavascript.net/code/
* http://www.w3resource.com/javascript-exercises/

#### Consigli

* La programmazione (così come una lingua) non si impara a lezione, né sui libri: si impara mettendo in pratica, sperimentando, e utilizzando un approccio (pro)attivo
    - Prendere appunti
    - Idealmente, per gran parte, gli appunti dovrebbero essere il codice stesso
* In caso di dubbi, fate domande: potrebbero servire a tutti

### iii) Programma

Note: 

* Potrebbe essere soggetto a variazione.
* I vari punti potrebbero avere pesi diversi relativamente al numero di ore di lezione.
* L'idea è di mantenere una certa flessibilità per quanto riguarda contenuti e modalità di erogazione.

#### Parte 0: Introduzione e contestualizzazione

1. Rudimenti di ingegneria del software
1. Introduzione alla programmazione
1. Impostazione dell'ambiente di lavoro

#### Parte 1: Elementi di base della programmazione in JavaScript

1. Introduzione a JavaScript
1. Tipi di dato
1. Variabili, dichiarazioni, scope
1. Espressioni
1. Istruzioni di controllo
1. Strutture dati
1. Elementi di programmazione funzionale
1. Elementi di programmazione orientata agli oggetti

#### Parte 2: Da JavaScript a Java/C&#35;

1. Sulla tipizzazione dei linguaggi 

### Rudimenti di ingegneria del software

Prerequisiti

* Cos'è il software?
* Come si realizza il software?

#### Principi e concetti

* **Ingegneria del software come disciplina**: principi, metodologie, tecnologie per migliorare il processo di sviluppo del software, rapportando conoscenza e strumenti in modo sistematico.
* **L'idea**: il prodotto software deve risultare da un **processo** ben definito.
    - Cioè, lo sviluppo del software non come attività episodica/artigianale ma *sistematica*.
* **Motto**: non c'è codice senza progetto, non c'è progetto senza analisi, non c'è analisi senza requisiti.
    - In altre parole, ci vuole una progressione dal *perché* al *cosa* al *come*
* Il focus è la **gestione della complessità**
    - Complessità essenziale vs. complessità accidentale
* Tracciabilità

#### Le fasi dello sviluppo del software

Dove iniziano i progetti software?

* Software house
* Sviluppatori software

Progetti software

* Software su commessa
* Prodotti software a pacchetto
* Servizi software
    - Prodotto vs. servizio
* Componenti software e librerie
* Altra categorizzazione: nuovo sviluppo / mantenimento / migrazione
  
[Fundamental activities](https://en.wikipedia.org/wiki/Systems_development_life_cycle#Phases) ([Ita](https://it.wikipedia.org/wiki/Ciclo_di_vita_del_software#Le_attivit.C3.A0_fondamentali))

2. **Specifica/raccolta dei requisiti**
3. **Analisi**
    - Dei requisiti
         - Casi d'uso, scenari
         - Modello del dominio: struttura/interazione/comportamento
         - Piani di collaudo
    - Analisi del problema
         - Architettura logica
         - Valutazione dell'abstraction gap
         - Analisi dei rischi
5. Piano di lavoro
6. **Progettazione (design)**
7. **Implementazione**
8. **Testing**
9. Deployment
10. Manutenzione

#### Modelli di ciclo di vita di sviluppo del software 
  
[Software Development Approaches](https://en.wikipedia.org/wiki/Software_development_process#Approaches) ([Ita](https://it.wikipedia.org/wiki/Ciclo_di_vita_del_software#Processi_di_sviluppo_software))

* [Waterfall model](https://en.wikipedia.org/wiki/Waterfall_model) ([Ita](https://it.wikipedia.org/wiki/Modello_a_cascata))
* [Spiral model](https://en.wikipedia.org/wiki/Spiral_model) ([Ita](https://it.wikipedia.org/wiki/Modello_a_spirale))
    - Pianificazione, Analisi dei rischi, Sviluppo, Verifica
    
#### Metodologie di sviluppo del software

* Classica
* [Agile](https://en.wikipedia.org/wiki/Agile_software_development) ([Ita](https://it.wikipedia.org/wiki/Metodologia_agile))
    - [Agile Manifesto](http://agilemanifesto.org/) ([Ita](http://agilemanifesto.org/iso/it/manifesto.html))
    - Pratiche agile: sviluppo guidato dai test (TDD), consegne frequenti, interazione col cliente, programmazione in coppia, ...
    - Sotto-metodologie: XP
    - Framework di processo: Scrum

#### A proposito dei requisiti

* Requisiti **di prodotto** e **di processo**
* Requisiti **funzionali** e **non-funzionali**
* Proprietà emergenti -- non realizzabili da un singolo componente 
* I requisiti dovrebbero essere **quantificabili**
* Requisiti **relativi al sistema** e **relativi al software**

#### La costruzione del software
  
E' l'attività centrale dello sviluppo del software. Fanno parte della costruzione le sotto-attività:

* Architettura del software
* Design di dettaglio
* Codifica e debugging
* Testing

Metafora: la costruzione di un edificio

* **(Definizione del problema)** Che tipo di casa vuoi costruire?
* **(Design architetturale)** Si interagisce con un architetto, il quale definirà un progetto di massima.
* **(Design di dettaglio)** L'architetto sviluppa il progetto.
* **(Costruzione)** L'impresa edile costruisce l'edificio dalle fondamenta.
* **(Ottimizzazione)** La casa è su, ma dev'essere rifinita. Si ricorre ad operai specializzati (imbianchini, progettista di interni, ...).
* **(Revisione e ispezione)** Durante il progetto, vari ispettori controllano il sito, le fondamenta, ...
* Il costo principale è di manodopera.
* Il costo per rifare da capo il progetto è molto alto; così come è alto il costo di cambiamenti strutturali.
* Per progetti molto grandi, occorre più tempo per la pianificazione, per non incorrere in costi maggiori successivamente.
* **(Manutenzione)** Una volta che la casa viene abitata, può essere necessario effettuare interventi riparatori.
* **(Riuso del software)** Non tutto viene costruito da capo (travi, mobilia, elettrodomestici, ...).
* La pianificazione, il progetto, e il controllo qualità possono essere visti a **livelli differenti**
* A seconda del contesto e dai requisiti, diversi approcci di costruzioni possono essere usati (zona sismica? zona franosa? zona di montagna?)

#### Pratiche comuni

* Sviluppo collaborativo: team e ruoli
* Controllo di versione
* Automazione della build
* Test di regressione automatici
* Generazione della documentazione dai commenti
* Integrazione continua

### Paradigmi di programmazione

[Programming paradigms](https://en.wikipedia.org/wiki/Programming_paradigm) ([Ita](https://it.wikipedia.org/wiki/Paradigma_di_programmazione))

Principali paradigmi di interesse in questo corso:

* **Programmazione imperativa**
    - Ispirazione: architettura di von Neumann
    - Ispirazione "tecnologica"
* **Programmazione funzionale**
    - Concetto chiave: la funzione matematica e la sua applicazione
    - Ispirazione "teorica"
* **Programmazione a oggetti**
    - Concetti chiave: modellazione del mondo reale, oggetti, interazione fra oggetti via scambio di messaggi
    - Pilastri fondamentali: incapsulamento, ereditarietà, polimorfismo

Altri paradigmi comunemente riferiti in discorsi circa la programmazione (NOTA: le demarcazioni non sono nette; paradigmi diversi possono coesistere; alcuni paradigmi possono condividere parte delle idee di base)

* Programmazione strutturata
    - Teorema della programmazione strutturata: sequenza, selezione (branch), iterazione
    - Critica al "go-to"
    - Elementi: strutture di controllo, subroutine (procedure, funzioni, ...), blocchi
* Programmazione modulare
    - Concetti chiave: modulo, interfaccia
* Programmazione procedurale
    - Concetto chiave: chiamata a procedura
    - Spesso sinonimo di programmazione imperativa
* Programmazione dichiarativa
    - Esprime la logica di computazione senza specificare il flusso di controllo
* Programmazione logica
    - I programmi consistono in fatti e regole
    - L'elaborazione avviene mediante un processo deduttivo di verifica di ipotesi

Linguaggi multi-paradigma

* Principalmente: programmazione imperativa, a oggetti, funzionale

<a name="lezione-2701"></a>

------------------------------------

## Lezione 2: 27/01/2017

Sommario

* Riallacciamento lezione precedente: paradigmi di programmazione
* Introduzione a JavaScript
* Incorporamento di codice JavaScript in pagine HTML
* Verifica di asserzioni, testing

### Paradigmi di programmazione: esempio

```prolog
% LOGICO
max([X],X).
max([X|Xs],X):- max(Xs,Y), X >=Y.
max([X|Xs],N):- max(Xs,N), N > X.
```

```Scala
// IMPERATIVO/PROCEDURALE
def max(lst: List[Int]): Int = {
  assert(lst.size>0, "La lista non può essere vuota")
  var currMax = lst.head
  for(x <- lst.tail){
    if(x > currMax) currMax = x;
  }
  return currMax
}
```

```Scala
// FUNZIONALE
def max(lst: List[Int]): Int = 
  lst.reduce((max,curr) => if(curr>max) curr else max)
```

```Scala
// ORIENTATO AGLI OGGETTI
class Lista(val nums: Int*){
  def max = nums.max
}
new Lista(4,7,1).max
```

### A proposito dei linguaggi di programmazione

[Linguaggi di programmazione](https://en.wikipedia.org/wiki/Programming_language) ([Ita](https://it.wikipedia.org/wiki/Linguaggio_di_programmazione))

* **Sintassi**
* **Semantica**
* **Sistema di tipi**: classificazione valori ed espressioni in tipi
* Linguaggi general-purpose (GPL) e linguaggi domain-specific (DSL)
* Come già indicato precedentemente, la nozione di **paradigma di programmazione** serve a classificare i linguaggi sulla base dello stile di programmazione.

### JavaScript

#### Introduzione a JavaScript

- Cos'è JavaScript
    - Linguaggio di scripting: linguaggio di programmazione che supporta la scrittura di script, cioè programmi scritti per ambienti runtime "speciali" finalizzati all'automazione di alcune attività che potrebbero essere eseguite passo-passo da un operatore umano
    - Da non confondersi con Java
- Possibile riferimento: http://www.html.it/guide/guida-javascript-di-base/
- Perché è stato scelto come linguaggio per questo corso introduttivo sulla programmazione
- Storia ed evoluzione del linguaggio: ECMAScript, AJAX, librerie, utilizzo server-side, evoluzione tecnica (ES6)
- Popolarità e ruolo nello sviluppo Web moderno

#### I primi passi: ambiente di lavoro ed esecuzione di script

- Gli strumenti di lavoro: editor, interprete/compilatore (engine), debugger
- Strumenti di sviluppo nei browser: console (*REPL: Read Evaluate Print Loop*)
- Utilizzo di JavaScript in pagine HTML
    - Inline su attributi HTML
    - Blocchi di codice nella pagina
    - Inclusione di script JavaScript

```html
<!DOCTYPE html>
<html>
  <head>
    <!-- INCLUSIONE SCRIPT JAVASCRIPT -->
    <script src="script.js"></script>
  </head>
  <body>
    <script>
    // CODICE JAVASCRIPT
    </script>
    
    <button onclick="alert('Hello, JS')" />
  </body>
</html>
```

#### Esperimenti iniziali

Prompt e alert

```javascript
var nome = window.prompt("Qual è il tuo nome?", "Default");
alert("Benvenuto, " + nome);
```

Scrittura sulla pagina

```javascript
document.write("Hello world");
```

Output a console

```javascript
console.log("Hello world");
```

### Esercizio: esplorazione del DOM

* In modo "programmatico" da console
    - Navigazione struttura gerarchica
* Attraverso il DOM inspector presente nei Developer Tools dei browser

### Esecuzione di codice JavaScript al caricamento della pagina

**Modalità 1**

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Test</title>
        <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
        <script type="text/javascript">
        function entryPoint() {
            alert('Hello');
        }
        </script>
    </head>
    <body onload="entryPoint();">
    </body>
</html>
```

**Modalità 2**

```javascript
function entryPoint() {
  alert('Hello');
}
window.onload = entryPoint;
```

**Modalità 3**

```javascript
document.addEventListener('DOMContentLoaded', function() {
    alert("Hello");
}, false);
```

* Digressione: cos'è il [Document Object Model (DOM)](https://en.wikipedia.org/wiki/Document_Object_Model) ([Ita](https://it.wikipedia.org/wiki/Document_Object_Model))
* Digressione: evento `onload` ed evento `DOMContentLoaded`
    - _The DOMContentLoaded event is fired when the initial HTML document has been completely loaded and parsed, without waiting for stylesheets, images, and subframes to finish loading. A very different event load should be used only to detect a fully-loaded page_ (https://developer.mozilla.org/en-US/docs/Web/Events/DOMContentLoaded)

**Modalità 4** (posizionamento alla fine del codice di markup)

```html
<html>
...
</html>
<script>
alert("Hello")
</script>
```

**Modalità 5** (differimento del caricamento di script)

```html
<script src="file.js" defer></script>
```

**Modalità 6** (JQuery)

```javascript
$(document).ready(function(){
   alert("Hello");
});
```

* Digressione: il problema della **compatibilità dei browser**

### Esercizio di comprensione: qual è l'output nella pagina?

```html
<!DOCTYPE html>
<html>
<head>

<script>
  
function write(msg){
  var div = document.getElementById("content");
  if(div == null) return;
  div.innerHTML = div.innerHTML + msg + "<br />";
}
  
window.onload = function(){ write("Onload"); };

document.addEventListener('DOMContentLoaded', function() {
    console.log("DOM loaded");
    write("DOM loaded");
}, false);

write("Scrivo sul documento");

</script>

</head>
<body>

<script>
  write("Messaggio1");
</script>
  
  <div id="content"></div>
  
<script>
  write("Messaggio2");
</script>  

</body>
</html>
```

<a name="lezione-3001"></a>

<hr />

## Lezione 3: 30/01/2017

Sommario

* Specifiche di comportamento in JasmineJS
    - Questo anche mostra come utilizzare librerie JavaScript esterne
    - Oltre che essere un esempio di testing / specifica di "aspettative"
* Commenti ed elementi sintattici di base
* Tipi di dato in JavaScript
* Variabili, costanti, dichiarazioni
* Espressioni e operatori

### Verifica di assunzioni in [JasmineJS](https://jasmine.github.io/)

Esempio

```html
<html>

<head>

<link rel="shortcut icon" type="image/png" href="jasmine-lib/lib/jasmine-2.5.2/jasmine_favicon.png">
<link rel="stylesheet" type="text/css" href="jasmine-lib/lib/jasmine-2.5.2/jasmine.css">

<script type="text/javascript" src="jasmine-lib/lib/jasmine-2.5.2/jasmine.js"></script>
<script type="text/javascript" src="jasmine-lib/lib/jasmine-2.5.2/jasmine-html.js"></script>
<script type="text/javascript" src="jasmine-lib/lib/jasmine-2.5.2/boot.js"></script>

</head>
<body>

<script>
describe("Somma fra numeri", function() {
  it("ha proprieta' associativa", function() {
    expect(1 + (4 + 5) === (1 + 4) + 5).toBe(true);
  });
});
</script>


</body>
</html>
```

* Notare l'utilizzo di una libreria esterna

Digressione

* [Test-Driven Development](https://en.wikipedia.org/wiki/Test-driven_development) ([Ita](https://it.wikipedia.org/wiki/Test_driven_development))
* [Behavior-Driven Development](https://en.wikipedia.org/wiki/Behavior-driven_development) ([Ita](https://it.wikipedia.org/wiki/Behavior-driven_development))

### Primi passi con JavaScript

#### Commenti, punti e virgola e maiuscola

- **Punto e virgola** è opzionale ma buona pratica usarlo
- **Case-sensitiveness**
- **Commenti**: singola linea `//...`, e multilinea `/*...*/`

#### Variabili, costanti e dichiarazioni

- Con `var`; nomi validi per variabili; le variabili possono possono contenere, nel tempo, valori di tipi diversi
- Oppure con `let` (ES6)
    - *Block-scoped*, cioè, la visibilità delle variabili dichiarate in questo modo è limitata al blocco in cui sono dichiarate.
- Dichiarazione implicita di variabili (senza `var`, in realtà è assegnamento di proprietà sull'oggetto globale)
    - **Strict mode**: da ES5, modalità meno permissiva (attivabile via `"use strict";` all'inizio di uno script o di una funziona) per ottenere errori in caso di utilizzo "poco buono" di JS
- **Costanti**: dichiarabili con parola chiave `const` (ES6); *block-scoped*

#### Tipi di dato in JavaScript

- La nozione di **tipo**
- **Tipi primitivi** (gestiti "per valore") e **tipi riferimento** (gestiti "per riferimento").
    - I valori primitivi sono memorizzati direttamente nella variabile.
    - I valori riferimento (oggetti) sono memorizzati nella variabile come puntatori a oggetti in memoria.
- **5 tipi primitivi**: numeri, stringhe, booleani, Null, Undefined
- Tutti i tipi primitivi hanno **rappresentazioni letterali** dei loro valori.
- E' possibile ispezionare il tipo di un valore attraverso l'operatore `typeof`
- Un tipo di dato complesso (**oggetti**) da cui derivano altri elementi (ad es. array, regexps, funzioni, ...)
- Conversione automatica dati primitivi a **oggetti wrapper**
- **Stringhe**: sintassi (singoli o doppi apici), escaping e caratteri speciali
- **Numeri**: interi e float; internamente rappresentati tutti come floating point; `Infinity`; `NaN`
- `null`: rappresenta nessun valore; è di tipo Null (anche se `typeof` riporta `"object"`); può essere visto come "puntatore vuoto ad oggetto" 
- `undefined`: è il valore assegnato a una variabile che non è inizializzata 
- Tipizzazione debole e dinamica: l'informazione di tipo è acquisita a runtime (tipizzazione dinamica), conversioni implicite fra tipi (tipizzazione debole)  

#### Espressioni e operatori

Nozioni fondamentali

- **Espressioni**: composizione di elementi la cui valutazione risulta in un valore
- **Operatori**: costrutti per la combinazione di valori; possono essere unari, binari, ternari a seconda del numero di valori (operandi) che ricevono
- **Associatività** e **precedenza** degli operatori: [consulta reference manual](https://developer.mozilla.org/it/docs/Web/JavaScript/Reference/Operators/Operator_Precedence)

Operatori 

- Operatori aritmetici: `+, -, *, /, %`; quelli unari sono negazione `-2`, incremento/decremento `x++` (notazione postfissa: "prima ritorna, poi opera"), `--x` (notazione prefissa: "prima opera, poi ritorna")
- Operazioni relazionali: `>, >=, <, <=, ==, !=`; particolari sono `===` (strettamente uguale) e `!==` (strettamente diverso)
- Operatori logici: `&&, ||, !`
- Operatori bitwise: `&, |, ^, ~, <<, >>`
- Operatore di assegnamento: `=` (restituisce il valore dell'espressione assegnata, ma non quando una variabile è dichiarata con `var`, faccenda un po' complicata: http://stackoverflow.com/questions/22844840/why-does-javascript-variable-declaration-at-console-results-in-undefined-being)
- Operatore condizionale (o ternario): `cond ? thenExpr : elseExpr`
- Operatori di assegnamento composti: `x += y; x /= y;` etc.
- Concatenazione di stringhe: `"ab"+"cd" // "abcd"`

<a name="lezione-3101"></a>

<hr />

## Lezione 4: 31/01/2017

Sommario

* Conversioni tra tipi
* Gli array
* `if`-`else if`-`else`
* `switch`
* `while` e `do..while`
* `for`
* `break` e `continue`

### Ancora sui tipi

#### Conversioni tra tipi di variabili

Conversioni

- **Da tipo a booleano**: `undefined, null, 0, NaN, ""` vengono convertiti in `false`
    - Nota: sui "valori falsi" le cose sono complesse (http://stackoverflow.com/questions/19839952/all-falsey-values-in-javascript)
- **Da tipo a numero**: `undefined` -> `NaN`, `false` -> 0, `true` -> 1, `null`->0, valori stringa dipendentemente dal valori
- **Da tipo a stringa**: i valori mantengono la rappresentazione (e.g., `NaN`->"NaN", `null`->"null", ecc.)

Altre questioni collegate ai tipi

- **Operatori polimorfi**: 
    - `+` (somma numeri, concatenazione stringhe se almeno un operando è stringa), 
    - operatori relazionali (se nessuno dei due operandi è un numero, allora viene eseguito un confronto tra stringhe, altrimenti viene eseguito un confronto tra numeri), 
    - operatori di confronto `!=,==` (e entrambi gli operatori sono stringhe allora viene effettuato un confronto tra stringhe, altrimenti si esegue un confronto tra numeri; unica eccezione è `null == undefined` che è vera per definizione)
- **Assegnamento condizionale**: `var x = y || ""`
- **Uguaglianza e disuguaglianza strette**: `===` e `!==` confrontano gli operando senza effettuare alcuna conversione

Consiglio:

- Evitare le conversioni implicite: utilizzare conversioni esplicite (`parseInt(s), parseFloat(s)`) o la verifica di tipo (`typeof 77 == "number"`)

### Array in JavaScript
    
- La nozione di **array** (in JavaScript): collezione eterogenea di elementi indicizzati (0-indexed)
- Sintassi: definizione letterale `[e1,e2,...,eN]`
- Array multidimensionali `[[e11,e12], [e21,e22,[e231]]]`
- Destrutturazione dell'assegnamento (da ES6)

### Strutture di controllo del flusso

#### `if`, istruzioni condizionali e blocchi di codice
    
- L'`if` fa parte dei **costrutti/strutture di controllo del flusso** (https://it.wikipedia.org/wiki/Struttura_di_controllo)
- Approfondimento: programmazione imperativa (https://it.wikipedia.org/wiki/Programmazione_imperativa), programmazione strutturata (https://it.wikipedia.org/wiki/Programmazione_strutturata)
- Blocchi di codice: insiemi di istruzioni racchiusi tra parentesi graffe
- `if(c){ t }`
- `if(c){ t } else { e }`
- `if(c){ t1 } else if(c2){ t2 } else { e }` (esprimibile con if-else annidati)

#### If-else e switch-case, combinare più condizioni

- Switch: `switch(c){ case e1: ...; break; case e2: ...; break; default: ... }`
    
#### While e do-while, le iterazioni di base
    
- `while(c){ ... }`
- `do { ... } while(c);`

#### I cicli for
    
- `for(init; cond; mod){ ... }`
- Inizializzazioni multiple o vuote
- `for-in`: per iterare sulle proprietà iterabili di oggetti
- `for-of`: nuovo modo (ES6) per iterare su oggetti iterabili, basato sulla proprietà interna [Symbol.iterator]

#### Ancora sui cicli

- `break`
- `continue`

-----------------------------------------

# Risorse

### Html.it: Guida JavaScript di Base

http://www.html.it/guide/guida-javascript-di-base/

Outline commentato ed espanso

1. Introduzione a JavaScript
    - Popolarità e ruolo nello sviluppo Web moderno
    - Storia ed evoluzione del linguaggio: ECMAScript, AJAX, librerie, utilizzo server-side, evoluzione tecnica (ES6)
1. Gli strumenti di lavoro
    - Editor, interprete/compilatore (engine), debugger
    - Strumenti di sviluppo nei browser: console
1. ECMAScript6 e il supporto dei browser
    - Transpiler: TypeScript, Traceur, Babel
1. JS e HTML, librerie e codice JavaScript esterno
    - Inserire codice JS in una pagina HTML: inline su attributi HTML, blocchi di codice nella pagina, inclusione di script
1. Commenti, punti e virgola e maiuscola
    - Punto e virgola è opzionale ma buona pratica usarlo
    - Case-sensitiveness
    - Commenti: singola linea `//...`, e multilinea `/*...*/`
1. Stringhe, numeri e altri tipi di dati JavaScript
    - 5 tipi primitivi: numeri, stringhe, booleani, Null, Undefined
    - 1 tipo di dato complesso (oggetti) da cui derivano altri elementi (ad es. array, regexps, funzioni, ...)
    - Conversione automatica dati primitivi a oggetti wrapper
    - Stringhe: sintassi (singoli o doppi apici), escaping e caratteri speciali
    - Numeri: interi e float; internamente rappresentati tutti come floating point; `Infinity`; `NaN`
    - `null`: rappresenta nessun valore; è di tipo Null (anche se typeof riporta "object"); può essere visto come "puntatore vuoto ad oggetto" 
    - `undefined`: è il valore assegnato a una variabile che non è inizializzata 
    - Tipizzazione debole e dinamica: l'informazione di tipo è acquisita a runtime (tipizzazione dinamica), conversioni implicite fra tipi (tipizzazione debole)  
1. Variabili, costanti e dichiarazioni
    - Con `var`; nomi validi per variabili; le variabili possono possono contenere, nel tempo, valori di tipi diversi
    - Dichiarazione implicita di variabili (senza `var`, in realtà è assegnamento di proprietà sull'oggetto globale)
    - Strict mode: da ES5, modalità meno permissiva (attivabile via `"use strict";` all'inizio di uno script o di una funziona) per ottenere errori in caso di utilizzo "poco buono" di JS
    - Costanti: dichiarabili con parola chiave `const`
1. Espressioni e operatori
    - Espressioni: composizione di elementi la cui valutazione risulta in un valore
    - Operatori: costrutti per la combinazione di valori; possono essere unari, binari, ternari a seconda del numero di valori che ricevono
    - Operatori aritmetici: `+, -, *, /, %`; quelli unari sono negazione `-2`, incremento/decremento `x++` (notazione postfissa: "prima ritorna, poi opera"), `--x` (notazione prefissa: "prima opera, poi ritorna")
    - Operazioni relazionali: `>, >=, <, <=, ==, !=`; particolari sono `===` (strettamente uguale) e `!==` (strettamente diverso)
    - Operatori logici: `&&, ||, !`
    - Operatori bitwise: `&, |, ^, ~, <<, >>`
    - Operatore di assegnamento: `=` (restituisce il valore dell'espressione assegnata, ma non quando una variabile è dichiarata con `var`, faccenda un po' complicata: http://stackoverflow.com/questions/22844840/why-does-javascript-variable-declaration-at-console-results-in-undefined-being)
    - Operatore condizionale (o ternario): `cond ? thenExpr : elseExpr`
    - Operatori di assegnamento composti: `x += y; x /= y;` etc.
    - Concatenazione di stringhe: `"ab"+"cd" // "abcd"`
1. Conversioni tra tipi di variabili
    - Da tipo a booleano: `undefined, null, 0, NaN, ""`
    - Nota: sui "valori falsi" le cose sono complesse (http://stackoverflow.com/questions/19839952/all-falsey-values-in-javascript)
    - Da tipo a numero: `undefined` -> `NaN`, `false` -> 0, `true` -> 1, `null`->0, valori stringa dipendentemente dal valori
    - Da tipo a stringa: i valori mantengono la rappresentazione (e.g., `NaN`->"NaN", `null`->"null", ecc.)
    - Operatori polimorfi: `+` (somma numeri, concatenazione stringhe se almeno un operando è stringa), operatori relazionali (se nessuno dei due operandi è un numero, allora viene eseguito un confronto tra stringhe, altrimenti viene eseguito un confronto tra numeri), operatori di confronto `!=,==` (e entrambi gli operatori sono stringhe allora viene effettuato un confronto tra stringhe, altrimenti si esegue un confronto tra numeri; unica eccezione è `null == undefined` che è vera per definizione)
    - Assegnamento condizionale: `var x = y || ""`
    - Uguaglianza e disuguaglianza strette: confrontano gli operando senza effettuare alcuna conversione
    - Evitare le conversioni implicite: conversioni esplicite (`parseInt(s), parseFloat(s)`), verifica di tipo (`typeof 77 == "number"`)
1. Definire Array in JavaScript
    - La nozione di array (in JavaScript): collezione eterogenea di elementi indicizzati (0-indexed)
    - Sintassi: definizione letterale
    - Array multidimensionali
    - Destrutturazione dell'assegnamento (da ES6)
1. IF, istruzioni condizionali e blocchi di codice
    - L'IF fa parte dei costrutti di controllo del flusso (https://it.wikipedia.org/wiki/Struttura_di_controllo)
    - Approfondimento: programmazione imperativa (https://it.wikipedia.org/wiki/Programmazione_imperativa), programmazione strutturata (https://it.wikipedia.org/wiki/Programmazione_strutturata)
    - Blocchi di codice: insiemi di istruzioni racchiusi tra parentesi graffe
    - `if(c){ t }`
    - `if(c){ t } else { e }`
    - `if(c){ t1 } else if(c2){ t2 } else { e }` (esprimibile con if-else annidati)
1. If-else e switch-case, combinare più condizioni
    - Switch: `switch(c){ case e1: ...; break; case e2: ...; break; default: ... }`
1. While e do-while, le iterazioni di base
    - `while(c){ ... }`
    - `do { ... } while(c);`
1. I cicli for
    - `for(init; cond; mod){ ... }`
    - Inizializzazioni multiple o vuote
    - for-in: per iterare sulle proprietà iterabili di oggetti
    - for-of: nuovo modo (ES6) per iterare su oggetti iterabili, basato sulla proprietà interna [Symbol.iterator]
1. Break e continue
1. Funzioni in JavaScript: i fondamentali
    - Definizione
    - Invocazione
    - Istruzione `return`
    - Parametri (formali) e argomenti (parametri attuali) di funzioni; concetto di "arità"
    - Flessibilità invocazione di funzione rispetto al numero di parametri forniti
    - L'array `arguments` tiene traccia degli argomenti con cui la funzione è stata invocata
    - Argomenti con valori di default
    - Da ES6: "rest parameter" `function(a,...r){ }` e operatore di "spread" `f(...[1,2,3])`
    - `return` vuota o non specificata: la funzione ritorna valore `undefined`
1. Variabili globali e locali: lo scope
    - Scope (ambito di visibilità) di variabili
    - Variabili locali: dichiarate all'interno di una funzione
    - Variabili globali: dichiarate fuori a qualsiasi funzione
    - Nota: dichiarare una variabile all'interno di un blocco di codice non crea un nuovo scope per la variabile
    - Da ES6: l'istruzione `let` (e `const`) limita lo scope di una variabile al blocco corrente (si parla dunque di dichiarazioni a livello di blocco)
1. Funzioni predefinite
    - `parseInt`, `parseFloat`
    - `isNan`, `isFinite` (restituisce true se l'argomento è diverso da `Infinity` e da `NaN`)
    - `escape` e `unescape` (entrambe deprecate)
    - `encodeURI`, `decodeURI`, `encodeURIComponent`, `decodeURIComponent`
    - `eval`: accetta una stringa e la interpreta come codice JavaScript
1. Oggetti JavaScript: proprietà, metodi, this
    - Programmazione orientata agli oggetti: oggetti, incapsulamento
    - Object literal
    - Proprietà; dot-notation; array-notation; creazione per definizione
    - Metodi
    - `this`
1. Tipi primitivi, oggetti e riferimenti
    - Differenza tra tipi di dato primitivi e oggetti: mentre i primi sono manipolati "per valore", i secondi "per riferimento"
    - Creazione oggetti mediante `new` e costruttore `Object`
    - Metodi ereditati da `Object`: `toString` (conversione oggetto a stringa), `valueOf` (conversione oggetto a tipo primitivo); questi metodi sono chiamati implicitamente da JavaScript in alcune situazioni.
    - `valueOf` è chiamato implicitamente ogni volta che un oggetto è usato con un operatore
    - `toString` è chiamato implicitamente quando l'oggetto è utilizzato in una situazione in cui ci si aspetta una stringa
