
# Notebook

Questo "quaderno" è un supporto per questo modulo IFTS di introduzione alla programmazione nel linguaggio JavaScript.

Pagine relative alle lezioni:

* [Lezione 15/02/2017](#lezione-1502), 15, 60/60 - Confronto fra JavaScript e Java/C#
* **[Lezione 14/02/2017](#lezione-1402)**, 14, 56/60 - Ripasso ed esercizi; breve panoramica alle espressioni regolari
* [Lezione 13/02/2017](#lezione-1302), 13, 52/60 - Classi in ECMAScript 6; lavorare con le stringhe con metodi di `String.prototype`
* [Lezione 10/02/2017](#lezione-1002), 12, 48/60 - Gestione degli errori; prototipi; esercizi
* [Lezione 09/02/2017](#lezione-0902), 11, 44/60 - Dereferenziazione di oggetti e garbage collection; proprietà getter/setter; costruttori; esercizi
* [Lezione 08/02/2017](#lezione-0802), 10, 40/60 - L'oggetto `Object`; l'oggetto `Array`; boxing; esercizi
* [Lezione 07/02/2017](#lezione-0702), 9, 36/60 - Introduzione alla programmazione ad oggetti in JavaScript; esercizi
* [Lezione 06/02/2017](#lezione-0602), 8, 32/60 - Funzioni di ordine superiore; consolidamento generale; esercizi
* [Lezione 03/02/2017](#lezione-0302), 7, 28/60 - Ripasso ed esercizi
* [Lezione 02/02/2017](#lezione-0202), 6, 24/60 - Funzioni ricorsive; pseudocodice; consolidamento generale; esercizi
* [Lezione 01/02/2017](#lezione-0102), 5, 20/60 - Funzioni: le basi; esercizi
* [Lezione 31/01/2017](#lezione-3101), 4, 16/60 - Array; strutture di controllo del flusso; esercizi
* [Lezione 30/01/2017](#lezione-3001), 3, 12/60 - Specifiche sw; primi elementi in JS (tipi, var, espressioni)
* [Lezione 27/01/2017](#lezione-2701), 2, 08/60 - Intro ai linguaggi; embedding JS in HTML
* [Lezione 26/01/2017](#lezione-2601), 1, 04/60 - Intro al modulo; ing. del sw

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

Esempi (nota: per convenzione, dopo `=>` indico il valore di ritorno dell'espressione o dello statement/istruzione)

```javascript
var x;   // => undefined   (statement)
x        // => undefined
x = 2+8; // => 10
x        // => 10

x++ // => 10
x   // => 11
++x // => 12
x   // => 12

x += 3 // => 13

var y = "a" + "bc"; // => undefined (statement)
y          // => "abc"
y += "zzz" // => "abczzz"

true || false  // => true
false || true  // => true
false || false // => false
true && true   // => true
false && true  // => false
!false   // true

!false ? "x" + "y" : true || false // => "xy"
// In generale, prima di poter valutare una espressione complessa,
//  le sottoespressioni devono essere valutate.
// Quindi:     !false ? "x"+"y" : true || false
//          => !false ? "xy" : true
//          => "xy"

var w = 7
(w+1) == 8        // => 8 == 8 => true
"abc" != "ab"+"c" // => "abc" != "abc" => false

false == 0  // => true
false === 0 // => false  (uguaglianza stretta)
"22" != 22  // => false
"22" !== 22 // => true   (disuguaglianza stretta)
```

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
- Proprietà `length` restituisce il numero di elementi dell'array
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

```javascript
for(A; B; C) D;
// A;                           ("A" eseguita solo la prima volta)
// if(B){ D } else { "esci"; }  (eseguo corpo "D" solo se "B" è vera)
// C;                           ("C" eseguita dopo ogni iterazione)  
// if(B){ D } else { "esci"; }
// C;
// if(B){ D } else { "esci"; }
// C;
// ..............
```

#### Ancora sui cicli

- `break`: interrompe il ciclo
- `continue`: termina l'iterazione corrente e continua l'esecuzione del ciclo dalla prossima iterazione

<a name="lezione-0102"></a>

<hr />

## Lezione 5: 01/02/2017

Sommario

* Funzioni
* Esercizi 

### Funzioni in JavaScript: i fondamentali

- **Definizione**: `function f(parameters){ body }`
- **Invocazione** `f(arguments)`
- Istruzione `return` specifica il **valore di ritorno**
    - `return` vuota o non specificata: la funzione ritorna valore `undefined`
- **Parametri (formali)** e **argomenti** (parametri attuali) di funzioni; 
- Concetto di **arità**: l'arità di una funzione è il numero di parametri che tale funzione "accetta" (o "riceve").
- Flessibilità invocazione di funzione rispetto al numero di parametri forniti
    - Se fornisco più argomenti all'atto di invocazione rispetto all'arità indicata, i parametri aggiuntivi vengono ignorati
    - Se forniscono meno argomenti, quelli non specificati prenderanno valore `undefined`
- L'array `arguments` tiene traccia degli argomenti con cui la funzione è stata invocata
- Argomenti con valori di default (ES6)
    - Può essere emulato in ES5 controllando se gli argomenti sono `undefined`
- (AVANZATO) Da ES6: "rest parameter" `function(a,...r){ }` e operatore di "spread" `f(...[1,2,3])`
- Le funzioni sono **oggetti "di prima classe"**; cioè, le posso assegnare a variabili, passare ad altre funzioni come argomenti, ritornarle come valori da funzioni etc.
- **Funzioni anonime**: ad es. `function(x,y){ return x+y; } // notare che non c'è nome`

### Esercizi

Esercizi semplici

* Fattoriale di un numero in versione iterativa: `n! = n*(n-1)*(n-2)*...*1`
* Conteggio delle occorrenze di un valore in un array: `howMany([2,5,2,1,2], 2) // 3`

<a name="lezione-0202"></a>

<hr />

## Lezione 6: 02/02/2017

Sommario

* Funzioni ricorsive
* Consolidamento ed esercizi 

### Ancora sulle funzioni

**Funzioni ricorsive**: funzioni che chiamano se stesse

- Occorre un "caso base" che faccia terminare la ricorsione

### Pseudocodice

[Pseudocodice](https://it.wikipedia.org/wiki/Pseudocodice): descrizione informale e "ad alto livello" di un programma o algoritmo.

* Altri nomi per lo stesso concetto: _pseudocodifica_, _pseudolinguaggio_ o _linguaggio di progettazione_
* Uno pseudolinguaggio usa la convenzioni strutturali di un comune linguaggio di programmazione, ma è pensato per essere leggibile più dagli uomini che dai computer.

Esempio

```
INIZIO

Scrivi: "Inserisci un numero naturale n"
Leggi n dall'utente

Se n%2 è = 0 (se il resto della divisione per 2 è 0):
    Scrivi: "Il numero è pari"
Altrimenti:
    Scrivi: "Il numero è dispari".

FINE
```

**Esercizio**: convertire lo pseudocodice qui sopra in codice JavaScript. Consigli per l'implementazione:

* `prompt("Msg")` è la funzione predefinita di JavaScript con cui posso chiedere un input all'utente; questa funzione ritorna una stringa che ha come contenuto il testo digitato dall'utente
* `parseInt(s)` può essere usato per convertire esplicitamente la stringa `s` nel numero intero corrispondente
* `console.log(s)` si può utilizzare per scrivere a console la stringa `s`

### Esercizi

Esercizi semplici

* Funzione per appendere o prependere un elemento a un array
    - `append([4,1], 7) // [4,1,7]`
    - `prepend([4,1], 7) // [7,4,1]`

### Esercizi svolti a lezione

```javascript
/* Funzione per calcolo del numero di occorrenze di un elemento in un array */
function numOccs(arr,elem){
  var n = 0;
  for(var i=0; i<arr.length; i++) if(arr[i]===elem) n++;
  return n;
}
numOccs([7,3,5,7,1,7],7) // 7

/* Funzione ricorsiva per il calcolo del fattoriale di un numero */
function fattoriale(n){
  if(n<=0) return 1;
  else return n * fattoriale(n-1); // n * fattoriale(n-1) = n * (n-1) * fattoriale(n-1-1)...
}
fattoriale(0) // 1
fattoriale(5) // 120

/* Funzione ricorsiva per il calcolo del numero minimo in un array */
function min(lst,i,m){
  if(lst.length==0) return "BAD";
  if(typeof(i)==="undefined") return min(lst,1,lst[0]);
  if(i>=lst.length) return m;
  var newM = lst[i]<m ? lst[i] : m;
  return min(lst,i+1,newM);
}
min([3,7,1,8]) // 1
// min([3,7,1,0])
// \-> min([3,7,1,0], 1, 3)
//     \-> min([3,7,1,0], 2, 3)
//         \-> min([3,7,1,0], 3, 1)
//             \-> min([3,7,1,0], 4, 1)
//                 \-> 1

/* Funzione di utilità che scarta l'elemento in testa all'array in input */
function resto(arr){
  var result = [];
  for(var i=1; i<arr.length; i++) result[i-1] = arr[i];
  return result;
}
resto([8,2,4,1]) // [2,4,1]

/* Restituisce true o false a seconda che l'array 'arr' contenga 'elem' o meno. 
Versione iterativa */
function contains(arr, elem){
  for(var i=0; i<arr.length; i++) if(arr[i]===elem) return true;
  return false;
}
contains(["bob","john","will","drake"], "john") // true
contains(["bob","john","will","drake"], "carl") // false

/* Restituisce true o false a seconda che l'array 'arr' contenga 'elem' o meno. 
Versione ricorsiva */
function contains2(arr, elem){
  if(arr.length==0) return false;
  return arr[0]===elem || contains(resto(arr),elem);
}

/* Conta il numero di occorrenze di 'elem' in 'arr'. */
function numOccs(arr, elem){
  if(arr.length==0) return 0;
  return (arr[0]===elem ? 1 : 0) + numOccs(resto(arr),elem);
}
contains(["bob","john","bob","will","drake"], "bob") // 2
contains(["bob","john","bob","will","drake"], "carl") // 0

/* Conversione dallo pseudocodice d'esempio (vedi sopra) al codice JavaScript */
function esercizio(){
  var n = parseInt(prompt("Inserisci un numero naturale n"));
  if(n%2===0) console.log("Il numero " + n + " è pari");
  else console.log("Il numero " + n + " è dispari");
}

/* Appende (cioè, aggiunge un elemento alla fine) un elemento in un array. 
Questa versione modifica l'array di input sul posto (non ne crea uno nuovo). */
function append(lst, x){
  lst[lst.length] = x;
  return lst;
}
var ar = [1,2]
append(ar, "x")
ar // [1,2,"x"]

/* Prepende un elemento in un array (cioè, lo inserisce in testa all'array). 
Modifica 'arr' sul posto (non ne crea uno nuovo). */
function prepend(arr, elem){
  var prev = elem;
  var size = arr.length;
  for(var i=0; i<=size; i++){
    var temp = prev;
    prev = arr[i];
    arr[i] = temp;
  }
  return arr;
}

/* Versione di "prepend" che ritorna un nuovo array. */
function prepend2(arr, elem){
  var res = [elem];
  for(var i=0; i<arr.length; i++) res[i+1] = arr[i];
  return res;
}
```

<a name="lezione-0302"></a>

<hr />

## Lezione 7: 03/02/2017

Sommario

* Ripasso
* Consolidamento ed esercizi 

### Esercizi

* Funzione per ripetere una stringa `s` un numero `n` di volte; opzionalmente, dev'essere possibile indicare una stringa di separazione.
     - `ripeti("abc", 3) // "abcabcabc"`
     - `ripeti("abc", 3, "-") // "abc-abc-abc"`
* Inversione degli elementi in un array: `reverse([3,7,1]) // [1,7,3]`
* Funzione che somma tutti i parametri numerici forniti: 
     - `somma(1,4,2,3) // 10`
     - `somma(1,"xxx",2) // 3`
     - Nota: occorre utilizzare `arguments` per gestire un qualsiasi numero di argomenti
     - Consiglio: utilizzare l’operatore `typeof` per controllare i tipi degli argomenti

Esercizio di comprensione: cercare di capire qual è il funzionamento della seguente funzione.

```javascript
function xyz(p){
  for(var i=0; i<p.length/2; i++) if(p[i]!==p[p.length-1-i]) return false;
  return true;
}
```

Soluzioni agli esercizi svolti

```javascript
/* Ripete la stringa "s" un numero "n" di volta,
   separando con un parametro "d" opzionale */
function ripeti(s, n, d){
  if(typeof(d)==="undefined") d = " ";
  var result = "";
  for(var i=1; i<n; i++) result = result + s + d;
  result += s; // result = result + s
  return result;
}

/* Restituisce un nuovo array che è l'inverso dell'array di input. */
function reverse(arr){
  var res = [];
  for(var i=0; i<arr.length; i++)
    res[arr.length-1-i] = arr[i];
  return res; 
}
function reverse2(arr){
  var res = [];
  for(var i=arr.length-1; i>=0; i--)
    res[arr.length-1-i] = arr[i];
  return res; 
}
// NOTA: unica differenza tra "reverse" e "reverse2"
// è l'ordine in cui scorro l'array di input.

/* Somma esclusivamente i parametri numerici forniti. */
function somma(){
  var res = 0;
  for(var i=0; i<arguments.length; i++)
    if(typeof(arguments[i])=="number") res += arguments[i];
  return res;
}
```

### Array e tipi riferimento

Contrastare il comportamento dei tipi primitivi (dove le variabili contengono il valore e lo "passano" per copia)

```javascript
var x = 10 // => undefined
var y = x  // => undefined
++y // => 11
x   // => 10
y   // => 11
```

rispetto al comportamento dei tipi riferimento (come ad es. gli array; dove le variabili contengono il **puntatore** all'oggetto)

```javascript
var x = [3,7] // => undefined
var y = x     // => undefined   (NOTA: è copiato il puntatore, non l'intero oggetto)
y[1] = 8      // => 8
x[1]          // => 8  (!!!!!)
```

<a name="lezione-0602"></a>

<hr />

## Lezione 8: 06/02/2017

Sommario

* Funzioni di ordine superiore
* Consolidamento ed esercizi 

### Ancora sulle funzioni

**Funzioni "di ordine superiore" (higher-order)**: funzioni che manipolano altre funzioni.

- Funzioni che accettano altre funzioni come parametri
- Funzioni che ritornano altre funzioni in output

Esempi:

```javascript
function howMany(arr, predicato){
  var result = 0;

  for(var k=0; k<arr.length; k++){
    if(predicato(arr[k])) result++;
  }

  return result;
}

function times(n){
  return function(x){ return x*n; }
}
var raddoppia = times(2);
var triplica = times(3);
raddoppia(3); // 6
triplica(3); // 9
```

Esempio: funzione `howMany(arr,p)` che ritorna il numero di elementi dell'array `arr` che "soddisfano" il predicato `p`.

* NOTA: un **predicato** è una funzione che "mappa" (cioè, "fa corrispondere") il parametro di input in un valore booleano.
* Esempio: `howMany([1,4,7,9,11,0,-4,8], function(n){ return n>5; }) // 4`

Esercizi su funzioni “higher-order”

* `map([1,2,3], function(i){ return i+1; }) // [2,3,4]`
    - `map` applica la funzione fornita come secondo parametro a tutti gli elementi della lista fornita come primo parametro
* `filter([1,2,3,4,5], function(n){ return n%2==0; }) // [2,4]`
    - Filtra gli elementi della lista sulla base della funzione fornita
    
```javascript
function map(arr, f){
  var res = [];
  for(i=0; i<arr.length; i++)
    res[i] = f(arr[i]);
  return res;
}

function filter(arr, p){
  var res = [];
  var j = 0;
  for(var i=0; i<arr.length; i++){
    if(p(arr[i])) res[j++] = arr[i];
  }
  return res; 
}
```

### Esercizi svolti

Funzioni ricorsive

* Serie di Fibonacci: `0,1,1,2,3,5,8,13,21,34,...`

```javascript
function fib(n){
  if(n<=1) return 0;
  if(n==2) return 1;
  return fib(n-1)+fib(n-2);
}
```

Altri esercizi

```javascript
// Verifica che 'arr' alterna numeri pari a numeri dispari (o viceversa)
function f(arr) {
  if(arr.length==0) return true;
  var p = !(arr[0]%2==0);
  for(var i=1; i<arr.length; i++){
     var currP = arr[i]%2==0;
     if(currP!=p) return i;
     p = !p;
  }
  return true;
}

// Esercizio di comprensione: cosa fa?
function xyz(arr){
  var k = 0;
  for(var i=0; i<arr.length; i++){
    for(var j=1; j<arguments.length; j++){
      if(arr[i]===arguments[j]) k++;
    }
  }
  return k;
}
```

<a name="lezione-0702"></a>

<hr />

## Lezione 9: 07/02/2017

Sommario

* Introduzione alla programmazione orientata agli oggetti
* Oggetti in JavaScript

### Programmazione orientata agli oggetti

[Object-Oriented Programming - OOP](https://en.wikipedia.org/wiki/Object-oriented_programming)([Ita](https://it.wikipedia.org/wiki/Programmazione_orientata_agli_oggetti))

* L'OOP si fonda sul concetto di **oggetto**.
* Gli **oggetti** sono delle entità software che incapsulano dati (spesso chiamati **campi, proprietà, attributi**) e funzionalità (**metodi**).

```scala
// NOTA: questi esempi sono in linguaggio Scala (non JavaScript)
object WillSmith {
  val name: String = "Will"
  val surname: String = "Smith"
  var age: Int = 48
      
  def presentMe() = s"Hi, my name is " + this.name + " " + this.surname + 
                    " and I am " + this.age + " years old"
}

WillSmith.presentMe()
```

* Il principio di **incapsulamento**: gli oggetti raccolgono al loro interno sia dati sia funzioni (metodi) che agiscono su questi dati.
* Il principio di **information hiding**: l'interazione con un oggetto avviene attraverso una specifica **interfaccia** che nasconde tutta una serie di dettagli circa il funzionamento concreto dell'oggetto
    - Il concetto di **interfaccia**
    - Solitamente, metodi e proprietà possono avere diversi **livelli di visibilità**

```scala
object WillSmith {
  // ...
  private var yearOfBirth: Int = 1968
      
  def age() = Calendar.getInstance().get(Calendar.YEAR) - this.yearOfBirth
}
    
WillSmith.yearOfBirth // ERRORE: non si può accedere a proprietà privata
WillSmith.age() // 48
```

* Il concetto di **classe**: schema per la costruzione di oggetti
    - Nota: JavaScript ha aggiunto le classi solo a partire da ECMAScript 6
* Gli oggetti sono anche chiamati **istanze** (di una classe)
* **Ereditarietà**: relazione "è un"; consente di creare una specializzazione ("figlio") di un concetto esistente (detto "padre").

```scala
trait FormaGeometrica
class Rettangolo(val base: Int, val altezza: Int) extends FormaGeometrica {
  def area = this.base * this.altezza
}
class Quadrato(lato: Int) extends Rettangolo(lato,lato)

val q = new Quadrato(5)
q.area // 25

val r = new Rettangolo(3,4)
r.area // 24
```

### Oggetti in JavaScript

#### Basi

Creazione di oggetti

* Sintassi letterale: `var o1 = { prop1: value1, prop2: value2 }`
* Per istanziazione: `var o2 = new Object` 

```javascript
var WillSmith = {
  name: "Will",
  surname: "Smith",
  yearOfBirth: 1968,
  age: function(){ return new Date().getFullYear()-this.yearOfBirth; }
};
```

**Proprietà**:

* dot-notation (notazione puntata) 
* array-notation (notazione array)
* creazione per definizione

**Metodi**: in pratica sono proprietà di tipo funzione.

- `this`: all'interno di un metodo, punta all'oggetto corrente su cui il metodo è invocato.

```javascript
WillSmith.name        // => "Will"
WillSmith.yearOfBirth // => 1968
WillSmith["surname"]  // => "Smith" (Accesso con notazione array)

WillSmith.name = "Willy" // => "Willy" (viene modificata la proprietà 'name')

WillSmith.age()       // => 49 (Invocazione di metodo)
WillSmith["age"]()    // => 49 (Invocazione di metodo)

WillSmith.title = "Mr." // => "Mr." (Creazione di una nuova proprieta')
WillSmith.presentMe = function(quick) { // Creazione di un nuovo metodo
  if(quick) return this.name + " " + this.surname;
  else return this.title + " " + this.name + " " + this.surname;
};

WillSmith.presentMe()  // "Mr. Willy Smith"

var SeanConnery = { 
  name: "Sean", 
  surname: "Connery", 
  title: "Sir.",
  presentMe: WillSmith.presentMe // NOTA: sto riferendo (NON invocando) la funzione
};

SeanConnery.presentMe() // "Sir. Sean Connery"
```

Esercizio effettuato in aula: rettangolo

```javascript
var r = {
  base: 0,
  altezza: 0,
  area: function(){ return this.base*this.altezza; },
  setBase: function(b){ this.base = b; },
  setAltezza: function(a){ this.altezza = a; }
}; // =>undefined
r.area() // => 0
r.setAltezza(5); // => undefined
r.setBase(3);    // => undefined
r.base       // => 3
r["altezza"] // => 5
r.area()     // => 15
```

#### Oggetti e tipi riferimento

* Differenza tra tipi di dato primitivi e oggetti: mentre i primi sono manipolati "per valore", i secondi "per riferimento"

### Esercizi svolti

```javascript
var av = {
  init: 0,
  end: 2,
  arr: [],
  setArray: function(arr){ 
    this.arr = arr;
  },
  setWindow: function(init,end){
    if(init<0 || end<0) return "BAD: negative nums";
    if(init > end) return "BAD: init<end";
    this.init = init;
    this.end = end;
  },
  getView: function(){
    var res = [], j=0;
    for(var i=this.init; i<this.arr.length && i<=this.end; i++)
      res[j++] = this.arr[i];
    return res;
  }
};

av.setArray([3,1,7,8,9]) // => undefined
av.getView()       // => [3, 1, 7]
av.setWindow(-4,3) // => "BAD"
av.setWindow(4,-3) // => "BAD"
av.setWindow(8, 4) // => "BAD"
av.setWindow(1, 3) // => undefined
av.getView()       // => [1, 7, 8]
av.setArray([8])   // => undefined
av.getView()       // => []
av.setArray([8,9]) // => undefined
av.getView()       // => [9]


/* Verifica se tutti gli oggetti in 'obs' posseggono le proprietà in 'propNames' */
function have(objs, propNames){
  for(var i=0; i<objs.length; i++)
    for(var j=0; j<propNames.length; j++)
      if(typeof(objs[i][propNames[j]])==="undefined") return false;
  return true;
}
/* Calcolo distanza tra due oggetti con coordinate 'x' e 'y';
   Verifica con 'have()' che i due oggetti in input 'p1' e 'p2'
   sono del formato corretto.
*/
function distance(p1,p2){
  if(!have([p1,p2],["x","y"])) return "BAD";
  return Math.sqrt(Math.pow(p2.x-p1.x,2) + Math.pow(p2.y-p1.y,2));
}

```

<a name="lezione-0802"></a>

<hr />

## Lezione 10: 08/02/2017

Sommario

* L'oggetto `Object`
* Alla scoperta dell'oggetto `Array`
* Cos'è una "libreria standard"
* Boxing: conversione da tipi primitivi ad oggetti

### L'oggetto `Object`

Vedere [cosa dice la guida di riferimento di JavaScript su Object](https://developer.mozilla.org/it/docs/Web/JavaScript/Reference/Global_Objects/Object).

- Metodi ereditati da `Object`: `toString` (conversione oggetto a stringa), `valueOf` (conversione oggetto a tipo primitivo); questi metodi sono chiamati implicitamente da JavaScript in alcune situazioni.
- `valueOf` è chiamato implicitamente ogni volta che un oggetto è usato con un operatore
- `toString` è chiamato implicitamente quando l'oggetto è utilizzato in una situazione in cui ci si aspetta una stringa

```
"Hello " + WillSmith // "Hello [object Object]"
WillSmith.toString = WillSmith.presentMe
"Hello " + WillSmith // "Hello Mr. Will Smith"
```

Esempi mostrati a lezione

```javascript
{}.toString()   // Uncaught SyntaxError: Unexpected token .
({}).toString() // "[object Object]"
var o = {}      // undefined
o.toString = function(){ return "il mio oggetto"; }
o.toString()    // "il mio oggetto"
" => " + o      // " => il mio oggetto"
10 + o          // "10il mio oggetto"
10 - o          // NaN 
o - 10          // NaN
o.valueOf()     // Object {...}
10 - {}         // NaN
{} - 10         // -10
({}) - 10       // NaN
o.valueOf = function(){ return 5; }; 
10 - o          // 5
o - 3           // 2
```

### L'oggetto `Array`

Vedi [a proposito degli Array nella guida di riferimento](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).

#### Esempi mostrati a lezione

```javascript
[1, "xy", true].forEach(function(e,i,a){ 
  console.log(i+"/"+(a.length-1) +") "+e) 
})
// 0/2) 1
// 1/2) xy
// 2/2) true

var arr = [7, "xy", true] // undefined
arr.push([1,2])      // 4
arr                  // [7, "xy", true, Array[2]]
arr.push("abc", 77)  // 6
arr                  // [7, "xy", true, Array[2], "abc", 77]


a = [7, "zzz", true, 88]
a.pop()    // 88
a          // [7, "zzz", true]


a.shift() // 7
a         // ["zzz", true]


a = [7, "zzz", true]
a.unshift(5.5)  // 4
a               // [5.5, 7, "zzz", true]
a.unshift(7, 9) // 6
a               // [7, 9, 5.5, 7, "zzz", true]

a.indexOf("zzz") // 4
a.indexOf("fsdhsafdasdf") // -1

a.splice(1, 3) // [9, 5.5, 7]
a              // [7, "zzz", true]
a.splice()     // []
a              // [7, "zzz", true]

a.slice(0, a.length) // [7, "zzz", true]
a.slice()            // [7, "zzz", true]
```

#### Esercizi mostrati a lezione

```javascript
/* Implementazione foreach(arr,f) che si comporta come
   Array.prototype.forEach (cioè il forEach della libreria standard).
*/
function foreach(arr,f){
  for(var i=0; i<arr.length; i++)
    f(arr[i],i,arr);
}

foreach([1, "xy", true], function(e,i,a){ 
  console.log(i+"/"+(a.length-1) +") "+e) 
})

/* Reimplementazione di push della libreria standard */
function push(arr){
  if(!Array.isArray(arr)) throw new Error("Bisogna passare un array!");
  for(var i=1; i<arguments.length; i++)
    arr[arr.length] = arguments[i];
  return arr.length; 
}

var arr = [1]       // undefined
push(arr, 7, "xy")  // 3
arr                 // [1, 7, "xy"]

/* Reimplementazione di pop della libreria standard */
function pop(arr){
  var result = arr[arr.length-1];
  arr.length--;
  return result;
}

a = [7, "zzz", true]
pop(a)    // true
a         // [7, "zzz"]

/* Reimplementazione di shift della libreria standard */
function shift(arr){
  if(arr.length==0) return undefined;
  var toWrite = arr[arr.length-1];
  for(var i=arr.length-2; i>=0; i--){
    var temp = toWrite
    toWrite = arr[i];
    arr[i] = temp;
  }
  arr.length = arr.length-1;
  return toWrite;
}

a = [7, "zzz", true]
shift(a) // 7
a        // ["zzz", true]0: "zzz"1: truelength: 2__proto__: Array[0]
shift([])

function slice(arr,init,end){
  if(typeof(init)==="undefined") init = 0;
  if(typeof(end)==="undefined") end = arr.length;
  var res = [], j=0;
  for(var i=init; i<end; i++)
    res[j++] = arr[i];
  return res;
}

slice([1,7,9,10,4,8],1, 4) // [7, 9, 10]
```

### Altre note

**Libreria standard** ([standard library](https://en.wikipedia.org/wiki/Standard_library)): libreria messa a disposizione in tutte le implementazioni di un certo linguaggio di programmazione.

- Ad esempio, la libreria standard di JavaScript è quella libreria utilizzabile in ogni implementazione di JavaScript.
- Ad esempio, i metodi sulle stringhe (`"abc".toUpperCase()`) e sugli array (`[1,2].forEach(...)`) fanno parte della libreria standard.

**Boxing**: conversione implicita di valori primitivi in oggetti

- I valori di tipi primitivi quali stringhe, booleani, numeri, null, undefined non hanno metodi invocabili su di essi.
- Tuttavia, è possibile comunque invocare metodi su essi in quanto implicitamente avviene un processo che si chiama **boxing**, cioè la conversione automatica del valore in un oggetto di una classe wrapper che invece fornisce tali metodi.

```javascript
"abc".toUpperCase() // "ABC"
20.toString()       // "20"
```

**Approcci alla modifica di valori**

- Approccio 1) modifica "in place" dell'oggetto
    - Più "orientato agli oggetti"; in quanto gli oggetti sono entità con stato (mutabile).
- Approccio 2) restituzione di un **nuovo oggetto** con le modifiche rispetto all'oggetto di partenza
    - Più funzionale (dove tipicamente le strutture dati sono immutabili).

**Gestione degli errori**

- E' possibile sollevare un errore via: `throw new Error("messaggio")`

<a name="lezione-0902"></a>

<hr />

## Lezione 11: 09/02/2017

Sommario

* Dereferenziazione di oggetti e garbage collection
* Proprietà getter/setter
* Costruttori

### Ricapitoliamo

* Gli **oggetti**, in JavaScript, sono collezioni non ordinate di proprietà.
* Una **proprietà**, in JavaScript, è effettivamente una coppia nome/valore.
    - Quando il valore di una proprietà è una funzione, essa è chiamata **metodo**.
* Gli oggetti sono **valori riferimento**, cioè, istanze di **tipi riferimento**.
    - Quando assegnati a una variabile, viene assegnato un puntatore (riferimento) alla locazione di memoria in cui l'oggetto è memorizzato.
* Gli oggetti sono **dinamici**, nel senso che possono cambiare ad ogni punto durante l'esecuzione del codice.

#### Tipi riferimento built-in

* Sono i seguenti: `Array, Date, Error, Function, Object, RegExp`
* Alcuni di questi tipi riferimento ammettono forme letterali che consentono di definire valori riferimento senza creare un oggetto esplicitamente via `new`.
    - Sapete fare degli esempi?
    
#### Tipi riferimento "wrapper" di tipi primitivi

* Sono i seguenti: `String, Number, Boolean`
* Se usate valori di tipi primitivi come se fossero oggetti (ad esempio?), allora i corrispondenti valori riferimento sono creati/distrutti automaticamente (**autoboxing**).

### Programmazione ad oggetti in JavaScript

#### Dereferenziazione di oggetti

```javascript
var obj = new Object
//...
obj = null
```

* JavaScript è un linguaggio che prevede un **garbage-collector**; cioè, la macchina virtuale che esegue i "programmi" JavaScript ha uno strumento che si occupa di **liberare la memoria** relativa ad oggetti che non sono più utilizzati, in modo automatico.

#### Proprietà

Le **proprietà** sono di due tipi:

1. **Proprietà dato**: contengono un valore.
    - Valori di tipi primitivi o valori di tipi riferimento (come funzioni).
2. **Proprietà d'accesso/accessorie**: non contengono un valore ma definiscono una funzione da chiamare in caso di accesso in lettura o in scrittura su una proprietà
    - Definite mediante keyword `get` (per i **getter**) e `set`(per i **setter**).

```javascript
var obj = {
  _name: "Bob",
  get name(){ return this._name.toUpperCase(); },
  set name(v){ this._name = v + " !!!"; },
  
  // NOTARE differenza rispetto a:
  getName: function(){ return this.name.toUpperCase(); },
  setName: function(v){ this._name = v + " !!!"; }
}

obj.name = "Will"  // => "Will"
obj.name           // => "Will !!!"

// NOTARE differenza rispetto a:
obj.setName("Sean")// => undefined
obj.getName()      // => "Sean !!!"
```

NOTA: proprietà getter/setter sono definite mediante parole chiave `get` e `set` all'interno di una definizione letterale di un oggetto. Per poter dichiarere dei getter e dei setter su oggetti già creati, occorre utilizzare il metodo `Object.defineProperty(o, p, d)`, il quale dichiara/imposta una proprietà di nome `p` sull'oggetto `o` con caratteristiche definite mediante il descrittore `d`. Per creare getter/setter, il descrittore `d` deve specificare due proprietà di nome `get` e `set` rispettivamente.

* Si veda la guida di riferimento per [dettagli su Object.defineProperty](https://developer.mozilla.org/it/docs/Web/JavaScript/Reference/Global_Objects/Object/defineProperty)

Una proprietà può essere **rimossa** da un oggetto mediante l'operatore `delete`:

```javascript
var obj = { x: 10, y: 77 }
delete obj.x     // true
delete obj["y"]  // true
obj // { }
```

#### Costruttori

Un **costruttore** è una normale funzione. In particolare, si chiama "costruttore" una funzione utilizzata per costruire un oggetto.

* Per istanziare un oggetto mediante un costruttore, si utilizza la parola chiave `new`.
* L'effetto di `new` è quello di creare un nuovo oggetto e di fare in modo che, all'interno del costruttore, `this` punti a questo nuovo oggetto creato.
    - `this` è sempre disponibile in ogni scope (ambito di visibilità). Per funzioni definite al top-level, `this` rappresenta l''oggetto globale.

```javascript
function Rect(base,altezza){
  this.base = base;
  this.altezza = altezza;
  this.area = function(){ return this.base * this.altezza; }
}

var r1 = new Rect(3,5);
typeof(r1) // "object"
r1 instanceof Rect      // true
r1 instanceof Object    // true
r1.constructor === Rect // true

var r2 = Rect(3,5); // SBAGLIATO! 
/* La funzione sopra è invocata ma 'this' non viene fatto puntare
   ad un nuovo oggetto. Invece, 'this' punterà all'oggetto globale. */
```

### Esercizi svolti

```javascript
var o ={
  yearOfBirth: 2000,
  get age(){ return new Date().getFullYear() - this.yearOfBirth; },
  set age(v){ this.yearOfBirth = new Date().getFullYear() - v; }
} // undefined
o.age         // 17
o.age = 40    // 40
o.age         // 40
o.yearOfBirth // 1977

// COSTRUTTORE PER UN PUNTO GEOMETRICO
function Point(x,y){
  this.x = x;
  this.y = y;
  this.distanceTo = function(p){
    return Math.sqrt(Math.pow(p.x-this.x,2) + Math.pow(p.y-this.y,2))
  };
} // undefined
var p1 = new Point(1,2) // undefined
var p2 = new Point(3,5) // undefined
p1       // Point {x: 1, y: 2}
p2       // Point {x: 3, y: 5}
p1.distanceTo(p2) // 3.605551275463989
p2.distanceTo(p1) // 3.605551275463989
p1.x       // 1
p1.x = 3   // 3
p2.distanceTo(p1)  // 3
p1.distanceTo(p2)  // 3

// FUNZIONE "BUILDER" o "FACTORY" PER CREARE RETTANGOLI
function BuildRect(p1,p2){
  if(!(p1 instanceof Point && p2 instanceof Point)) 
    throw new Error("Bisogna fornire dei punti");
  return new Rect(Math.abs(p1.x-p2.x),Math.abs(p1.y-p2.y));
}
var myRect = BuildRect(new Point(0,0), new Point(2,3)); // undefined
myRect // Rect {base: 2, altezza: 3}
myRect.area() // 6

// FUNZIONE "BUILDER" o "FACTORY" PER CREARE RETTANGOLI/QUADRATI
function BuildSquare(s){
  return new Rect(s,s);
}
BuildSquare(3).area() // 9 

// ALTRA VERSIONE DEL COSTRUTTORE "Rect"
function Rect(p1,p2){
  this.p1 = p1;
  this.p2 = p2;
  Object.defineProperty(this, "base", { 
    get: function(){ return Math.abs(this.p1.x-this.p2.x); },
    set: function(v){ throw new Error("Cannot be set"); }
  });
  Object.defineProperty(this, "altezza", { 
    get: function(){ return Math.abs(this.p1.y-this.p2.y); },
    set: function(v){ throw new Error("Cannot be set"); }
  });
}
var r = new Rect(new Point(0,0), new Point(2,3)) // undefined
r // Rect { p1: Point, p2: Point }
r.base // 2
r.altezza // 3
r.base = 10 // ERROR: cannot be set
```

<a name="lezione-1002"></a>

<hr />

## Lezione 12: 10/02/2017

Sommario

* Gestione degli errori
* Prototipi
* Approfondimento: ereditarietà pseudoclassica

### Gestione degli errori in JavaScript

```javascript
try {
    // ........
    throw "Errore";            // lancia un errore
    throw new Error("BAD"); // istruzione non raggiunta
}
catch(e) {
    // Catturo l'errore e lo gestisco in qualche modo
    if(e instanceof Error) console.log(e + "!!!");
    else throw e;
}
finally {
    // Questo blocco è eseguito sempre e comunque
    // Sia in caso di eccezione sia senza.
    console.log("Finally")
}
// Finally
// Uncaught Errore
```

* L'istruzione `throw e` solleva un'eccezione con valore `e`.
* Quando tale istruzione viene incontrata, si ferma l'esecuzione della funzione corrente e il controllo è passato al primo blocco `catch` nello stack delle chiamate. 
* Se nessun blocco `catch` cattura l'eccezione, il programma termina.
* Costruttori predefiniti per [oggetti "errore"](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Error): `Error(msg), RangeError, SyntaxError, TypeError`
    - Hanno due proprietà predefinite: `name, message`

### Prototipi

* Quando si crea un nuovo oggetto mediante `new C` (dove `C` è un costruttore), la proprietà `prototype` del costruttore `C` è assegnata alla proprietà interna `[[Prototype]]` del nuovo oggetto creato.
    - In diversi browser (cioè implementazioni di JavaScript) il prototipo è accessibile mediante una proprietà `__proto__`.
* `Object.getPrototypeOf(obj)` consente di leggere il valore della proprietà interna `[[Prototype]]` dell'oggetto `obj`.
* **Risoluzione delle proprietà**: quando si accede a una proprietà di un oggetto, questa viene cercata prima tra le proprietà possedute dall'oggetto stesso, e se non trovata, si prosegue la ricerca nel prototipo dell'oggetto. 
* I prototipi consentono di **condividere dati e metodi** attraverso tutte le istanze (oggetti) che hanno lo stesso prototipo.
* **Relazione tra istanze, prototipi e costruttori**
    - C'è un collegamento diretto tra un'istanza e il suo prototipo (proprietà interna `[[Prototype]]`)
    - C'è un collegamento diretto tra il prototipo e il costruttore (`C.prototype` e `P.constructor`)
    - C'è un collegamento indiretto tra un'istanza e il costruttore attraverso il prototipo.
* Poiché tutte le istanze di un particolare tipo riferimento condividono un prototipo, si possono aggiungere funzionalità a tutti questi oggetti in una volta sola aggiungendo agendo sul prototipo.
    - Vale anche per gli oggetti built-in come stringhe ed array!
* Quando si definisce una funzione (costruttore), la sua proprietà `prototype` è assegnata con un nuovo oggetto (che eredita da `Object.prototype`) che possiede una sola proprietà `constructor` (assegnata alla funzione stessa).
    - Questo è il motivo per cui le istanze ottenute mediante un costruttore definito dall'utente ereditano da `Object.prototype`. Quindi diciamo che tale costruttore è un **sottotipo** di `Object`.

```javascript
function Con(n){ this.name = n }

// APPROCCIO 1
// Con.prototype.constructor = Con  (default per ogni funzione di nome "Con")
Con.prototype.sayName = function(){ console.log(this.name); };
Con.prototype.favorites = [];

// APPROCCIO 2
Con.prototype = {
  sayName: function(){ console.log(this.name); },
  favorites: [],
  constructor: Con // IMPORTANTE! Altrimenti ci perdiamo il costruttore...
};

var obj1 = new Con("Vash")
var obj2 = new Con("Legato")
obj1.sayName()  // Prints out: Vash
obj2.sayName()  // Prints out: Legato

obj1.favorites.push("a");
obj2.favorites.push("b");
console.log(obj1.favorites); // Prints out: ["a","b"]

obj1.constructor === Con // true
```

#### Schema sui prototipi

Preso da: http://exploringjs.com/es6/images/classes----methods_150dpi.png

![](http://exploringjs.com/es6/images/classes----methods_150dpi.png)

Codice equivalente per la figura sopra:

```javascript
var Foo = new Function("this.prop = 123;")
Foo.staticMethod = function(){ return 55; }
console.log("Foo.[[Prototype] === Function.prototype ? " + 
            (Object.getPrototypeOf(Foo)===Function.prototype));
console.log("Foo.prototype.constructor === Foo ? " + 
            (Foo.prototype.constructor === Foo));
console.log("Foo.prototype.[[Prototype]] === Object.prototype ? " + 
            (Foo.prototype.__proto__ === Object.prototype));
Foo.prototype.prototypeMethod = function(){ return 77; }
var foo = new Foo();
console.log("foo.[[prototype]] === Foo.prototype ? " + 
            (foo.__proto__ === Foo.prototype));
console.log("foo.prop="+foo.prop+
            " ; Foo.staticMethod()="+Foo.staticMethod()+
            " ; foo.prototypeMethod()="+foo.prototypeMethod());
// Foo.[[Prototype] === Function.prototype ? true
// Foo.prototype.constructor === Foo ? true
// Foo.prototype.[[Prototype]] === Object.prototype ? true
// foo.[[prototype]] === Foo.prototype ? true
// foo.prop=123 ; Foo.staticMethod()=55 ; foo.prototypeMethod()=77
```


#### Operatore  `instanceof`

[Operatore instanceof](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/instanceof): `<obj> instanceof <constructor>`

* Questo operatore verifica la presenza di `constructor.prototype` nella catena di prototipi dell'oggetto.
* L'esempio seguente è preso dalla guida di riferimento:

```javascript
// defining constructors
function C() {}
function D() {}

var o = new C();

o instanceof C; // true, because: Object.getPrototypeOf(o) === C.prototype
o instanceof D; // false, because D.prototype is nowhere in o's prototype chain

o instanceof Object; // true
C.prototype instanceof Object // true

C.prototype = {};
var o2 = new C();

o2 instanceof C; // true
o instanceof C;  // false, because C.prototype is nowhere in o's prototype chain anymore

D.prototype = new C(); // use inheritance
var o3 = new D();
o3 instanceof D; // true
o3 instanceof C; // true
```

### Esempi mostrati a lezione

```javascript
function Point(x,y){
  this.x = x;
  this.y = y;
}
Point.prototype.distanceTo = function(p){
    return Math.sqrt(Math.pow(p.x-this.x,2) + Math.pow(p.y-this.y,2))
};
  
var o1 = { a: 7 }     // undefined
var o2 = { b: "x" }   // undefined
var o3 = { c : true } // undefined
o1.__proto__ = o2     // Object {b: "x"}
o2.__proto__ = o3     // Object {c: true}
o1.b          // "x"
o1.c          // true
o2.a          // undefined
o3.__proto__ = o1 // Uncaught TypeError: Cyclic __proto__ value
```

### Approfondimento: ereditarietà (pseudoclassica)

* Abbiamo detto che le proprietà di un prototipo sono automaticamente disponibili sulle istanze che hanno tale prototipo. Questa è una forma di **ereditarietà**.
- Ma poiché un prototipo è a sua volta un oggetto, allora un prototipo possederà direttamente alcune proprietà e ne erediterà altre dal suo prototipo. In altre parole, si ha in generale una **catena di prototipi**.
- Si può quindi implementare l'**ereditarietà tra tipi creando una catena di prototipi a partire da un costruttore**.
    - La catena tipicamente termina con `Object.prototype` che ha `null` come prototipo (`[[Prototype]]`).
- **Ereditarietà tra oggetti**: si può impostare direttamente il prototipo di un oggetto mediante `Object.create(proto, desc)` dove `desc` è un oggetto del tipo `{ objProp: { value: 88, writable: true }, ... }`
    - Un oggetto "completamente nudo" si può definire mediante: `Object.create(null)`
- **Ereditarietà tra costruttori**

```javascript
function Rect(h,w){ this.height = h; this.width = w; }
Rect.prototype.getArea = function(){ return this.height*this.width; }
Rect.prototype.toString = function(){
    return "[Rect " + this.height + "x" + this.width + "]";
}

function Square(side){ this.height = side; this.width = side; }
Square.prototype = Object.create(Rect.prototype) // Concatenazione prototipi
Square.prototype.constructor = Square;           // NOTE: ripristinato il riferimento al costruttore
Square.prototype.toString = function(){
    return "[Square " + this.height + "x" + this.width + "]";
}

var rect = new Rect(5,10)
var square = new Square(6)

rect.getArea()    // 50
square.getArea()  // 36
rect.toString()   // "[Rect 5x10]"
square.toString() // "[Square 6x6]"

square instanceof Square // true
square instanceof Rect   // true
```

* **Constructor stealing**

```javascript
function Square(side){
  Rect.call(this,side,side);
}
```

* L'approccio basato su prototype chaining e constructor stealing è spesso chiamato **ereditarietà pseudo-classica** perché mima l'ereditarietà classica nei linguaggi basati su classi.

<a name="lezione-1302"></a>

<hr />

## Lezione 13: 13/02/2017

Sommario

* Classi in ECMAScript 16
* Esplorazione della libreria standard: stringhe ed espressioni regolari

### Classi

* Definizione: `class NomeClasse { /* corpo della classe */ }`
    - Il corpo della classe consiste in definizione di costruttore, metodi, e/o proprietà getter/setter.
* Le proprietà possono essere create solo all'interno del costruttore o dei metodi.
* Le classi sono in realtà **"zucchero sintattico"** sopra l'utilizzo di funzioni costruttrici, prototipi etc.
* Chiamare il costruttore della classe senza `new` provoca un errore.
* I metodi utilizzano la **"sintassi concisa"** disponibile da ES6: `{ myMethod(){...}, oldMethod: function(){...} }`
* **Ereditarietà** si indica mediante `class ClasseFiglia extends ClassePadre`
    - Una **classe figlia** (**sottoclasse**) eredita da una **classe padre** (**superclasse** o **classe base**).
* All'interno dei metodi, `super` consente di richiamare funzionalità definite nelle superclassi.
    - Si può anche utilizzare nei prototipi per riusare le funzionalità del prototipo del prototipo.
* Quando una classe figlia specifica un metodo `m` già presente nella classe padre, quest'ultimo viene "sovrascritto", ma è possibile comunque riusarlo mediante chiamata esplicita `super.m()`.
* I **metodi statici** (indicati con parola chiave `static`) appartengono alla classe (e non alle istanze); sono invocati attraverso `NomeClasse.metodoStatico(...)`.
    - I metodi statici sono ereditati dalle sottoclassi.
* Come per le funzioni, le classi sono elementi **first-class** e possono essere assegnate a variabili, usate come argomenti di funzioni, etc.

```javascript 
class Persona {
  constructor(name, yob){ this.name = name; this.yearOfBirth = yob; }
  get age(){ return new Date().getFullYear() - this.yearOfBirth; }
  toString(){ return "Sono " + this.name + " and ho " + this.age + " anni."; }
  
  static descrizione(){ console.log("Ogni persona ha un nome."); }
}

//var p = Persona(); // TypeError: Class constructor Person cannot be invoked without 'new'
var p = new Persona("Bob",1990);
p.age // 27
p.toString() // "Sono Bob e ho 27 anni."
Persona.descrizione() // Prints: Ogni persona ha un nome.

var Impiegato = class extends Persona {
  constructor(name,yob){ 
    super(name,yob); // Chiamata (necessaria) al costruttore della classe padre
  }
  toString(){ return super.toString() + " Sono un impiegato."; }
}
var i = new Impiegato("Bob",2000);
i.toString() // // "Sono Bob e ho 17 anni. Sono un impiegato."
Impiegato.descrizione() // Prints: Ogni persona ha un nome.
```

#### Esercizio: rettangoli e quadrati

```javascript
class Rect { /* DA IMPLEMENTARE */ }
class Square { /* DA IMPLEMENTARE */ }

// SPECIFICA
var r = new Rect(2,3);
r.area // 6
r.toString() // "Sono un rettangolo di base 2 e altezza 3"
r.diagonal // 3.605551275463989

var s = new Square(8)
s.diagonal // 11.313708498984761
s.side = 10
s.toString() // "Sono un quadrato di lato 10. Oppure... Sono un rettangolo di base 10 e altezza 10"
s.width = 11
s.area // 121
```

**SOLUZIONE**

```javascript
var Rect = class {
  constructor(w,h){ this._width = w; this._height = h; }
  get width(){ return this._width; }
  set width(w){ this._width = w; }
  get height(){ return this._height; }
  set height(h){ this._height = h; }
  get area(){ return this.width * this.height; }
  get diagonal(){ return Math.sqrt(Math.pow(this.width,2)+Math.pow(this.height,2)); }
  toString(){ return "Sono un rettangolo di base " + this.width + " e altezza " + this.height + "."; }
}
var Square = class extends Rect {
  constructor(s){ super(s,s); }
  set side(s){ super.width = s; super.height = s; } 
  set width(w){ this.side = w; }
  set height(h){ this.side = h; }
  get width(){ return super.width; }   
  get height(){ return super.height; } 
  toString(){ return "Sono un quadrato di lato " + this.width + ". Oppure... " + super.toString(); }
}
```

**STUDIO DELLA SOLUZIONE**

```javascript
var Rect = class {
  constructor(w,h){ this._width = w; this._height = h; }
  get width(){ console.log("GET rect.width"); return this._width; }
  set width(w){ console.log("SET rect.width"); this._width = w;  }
  get height(){ console.log("GET rect.height"); return this._height;  }
  set height(h){ console.log("SET rect.height"); this._height = h; }
  get area(){ console.log("GET rect.area"); return this.width * this.height; }
  get diagonal(){ console.log("GET rect.diagonal"); return Math.sqrt(Math.pow(this.width,2)+Math.pow(this.height,2)); }
  toString(){ return "Sono un rettangolo di base " + this.width + " e altezza " + this.height + "."; }
}
var Square = class extends Rect {
  constructor(s){ super(s,s); }
  set side(s){ console.log("SET square.side"); super.width = s; super.height = s; } 
  set width(w){ console.log("SET square.width"); this.side = w; }
  set height(h){ console.log("SET square.width"); this.side = h; }
  get width(){ console.log("GET square.width"); return super.width; }   
  get height(){ console.log("GET square.width"); return super.height; } 
  toString(){ return "Sono un quadrato di lato " + this.width + ". Oppure... " + super.toString(); }
}

var s = new Square(8)
s.width = 11
// SET square.width
// SET square.side
// SET rect.width
// SET rect.height

s.area
// GET rect.area
// GET square.width
// GET rect.width
// GET square.width
// GET rect.height
```

**ESERCIZIO: trovare il problema nella seguente implementazione**

```javascript
var Rect = class {
  constructor(w,h){ this.width = w; this.height = h; }
  get area(){ return this.width * this.height; }   get diagonal(){ return Math.sqrt(Math.pow(this.width,2) +  Math.pow(this.height,2)); }
  toString(){ return "Sono un rettangolo di base " + this.width + " e altezza " + this.height + "."; }
}

var Square = class extends Rect {
  constructor(s){ super(s, s); }
  set side(s){ super.width = s; super.height = s; }
  set width(w){ this.side = w; }
  set height(h){ this.side = h; }
  get width(){ return super.width; }
  get height(){ return super.height; }
  toString(){ return "Sono un quadrato di lato " + this.width + ". Oppure... " + super.toString(); }
}
```

Consiglio: ispezionare/debuggare mediante stampe a console.

```javascript
var Rect = class {
  constructor(w,h){ console.log("RECT constructor"); this.width = w; console.log("RECT constructor after setting this.width"); this.height = h; console.log("RECT constructor END"); }
  get area(){ console.log("RECT.area"); return this.width * this.height; }   
  get diagonal(){ return Math.sqrt(Math.pow(this.width,2) +  Math.pow(this.height,2)); }
  toString(){ return "Sono un rettangolo di base " + this.width + " e altezza " + this.height + "."; }
}

var Square = class extends Rect {
  constructor(s){ console.log("SQUARE constructor"); super(s, s); }
  set side(s){ console.log("SET square.side"); super.width = s; super.height = s; }
  set width(w){ console.log("SET square.width");this.side = w; }
  set height(h){ console.log("SET square.height");this.side = h; }
  get width(){ console.log("GET square.width");return super.width; }
  get height(){ console.log("GET square.height");return super.height; }
  toString(){ return "Sono un quadrato di lato " + this.width + ". Oppure... " + super.toString(); }
}

var s = new Square(8)
// SQUARE constructor
// RECT constructor
// SET square.width
// SET square.side
// RECT constructor after setting this.width
// RECT constructor END
s.width = 11
s // Square {width: 11, height: 8}
```

### Stringhe

[A proposito delle stringhe nella guida di riferimento.](https://developer.mozilla.org/it/docs/Web/JavaScript/Reference/Global_Objects/String)

* `length` restituisce la lunghezza della stringa
* Concatenazione attraverso operatori `+` e `+=`
* Confronto lessicografico tra stringhe mediante `<` e `>`
* `charAt(i)`: ritorna il carattere all'indice `i` specificato.
* `indexOf(s)`: ritorna l'indice della prima occorrenza della stringa `s` (dell'ultima via `lastIndexOf(s)`), oppure `-1`
* `match(regex)`
* `replace(olds,news)`
* `substr(i,e)`
* `toLowerCase(), toUpperCase()`
* `trim()`

Esempi visti a lezione

```javascript
function replace(s, r, x){
  var iocc = s.indexOf(r);
  if(iocc==-1) return s;
  var res = "";
  for(var i=0; i<iocc; i++)
    res += s[i];
  res += x;
  for(i=iocc+r.length; i<s.length; i++)
    res += s[i];
  return res;
} 

function replace(s, r, x){
  var iocc = s.indexOf(r);
  if(iocc==-1) return s;
  var res = s.substr(0, iocc);
  res += x;
  res += s.substr(iocc + r.length, s.length-iocc-r.length);
  return res;
}
```

<a name="lezione-1402"></a>

<hr />

## Lezione 14: 14/02/2017

Sommario

* Espressioni regolari
* Ripasso ed esercizi

### Espressioni regolari

[A proposito delle espressioni regolari nella guida di riferimento.](https://developer.mozilla.org/it/docs/Web/JavaScript/Reference/Global_Objects/RegExp)

* Sintassi letterale: `/pattern/flags`
* Sintassi "object-oriented": `new RegExp(pattern, flags)`
* Flags
    - **g**: match globale; trova tutte le corrispondenze invece di fermarsi alla prima
    - **i**: ignora il case
    - **m**: gestione di stringhe multi-linea; tratta i caratteri d'inizio e fine (`^`, `$`) per ogni linea.
* Sintassi delle espressioni regolari: **caratteri**
    - `.` corrisponde a qualunque carattere tranne i delimitatori di riga
    - `\d` corrisponde a una qualunque cifra del pattern `[0-9]`
    - `\D` corrisponde a qualunque carattere che NON è una cifra
    - `\w` corrisponde a qualunque carattere alfanumerico del pattern `[a-zA-Z0-9_]`
    - `\W` corrisponde a qualunque carattere che NON fa parte di una parola (cioè, il contrario di `\w`)
    - `\s` corrisponde a uno spazio (spazio vuoto, tab, ..)
    - `\S` corrisponde a un NON spazio
* Sintassi delle espressioni regolari: **set di caratteri**
    - `[xyz], [a-c]` set di caratteri
    - `[^xyz], [^a-c]` negazione di un set di caratteri
* Sintassi delle espressioni regolari: **alternativa**
    - `x|y` corrisponde a `y` OPPURE `x`
* Sintassi delle espressioni regolari: **limiti**
    - `^` corrisponde all'inizio dell'input o di una linea in caso di regex multilinea
    - `$` corrisponde alla fine dell'input (o di linea)
    - `\b` corrisponde al limite di una parola; `\B` corrisponde a un NON-limite di una parola.
* Sintassi delle espressioni reglari: **raggruppamenti e riferimenti all'indietro**
    - **Gruppo di cattura**: `(x)` corrisponde a `x` e ricorda tale match
    - `(?:x)` corrisponde a `x` ma non ricorda tale match
    - **Riferimento all'indietro**: `\N` sostituisce con il contenuto dell'N-esimo gruppo catturato.
* Sintassi delle espressioni regolari: **quantificatori**
    - `x*`: corrisponde ad avere `x` zero o più volte
    - `x+`: corrisponde ad avere `x` una o più volte
    - `x?`: corrisponde ad avere `x` zero o una volta
    - `x{N}`: corrisponde ad avere `x` esattamente N volte
    - `x{N,}`: corrisponde ad avere `x` almeno N volte
    
Metodi di `RegExp.prototype`

* `exec(s)`
* `test(s)`

Esempio dalla guida

```javascript
var myRe = /ab*/g;
var str = 'abbcdefabh';
var myArray;
while ((myArray = myRe.exec(str)) !== null) {
  var msg = 'Found ' + myArray[0] + '. ';
  msg += 'Next match starts at ' + myRe.lastIndex;
  console.log(msg);
}
// Found abb. Next match starts at 3
// Found ab. Next match starts at 9
```

### Ripasso e domande

- Specifiche software e sviluppo behavior/test-driven
- Paradigmi di programmazione
- Embedding JavaScript in pagine HTML; la console (REPL)
- Tipi di dato primitivi e riferimento
- Espressioni e variabili
- Programmazione imperativa
- Strutture di controllo del flusso
- Array
- Programmazione funzionale e funzioni, in JavaScript
- Funzioni ricorsive; funzioni di ordine superiore; chiusure
- Programmazione ad oggetti ed oggetti, in JavaScript
- Prototipi e classi in JavaScript
- Gestione degli errori
- Libreria standard: array, stringhe, date

### Esercizi

**Esercizio 1**: Scrivere l'evoluzione dello stack delle chiamate

```javascript
function g(s){
  return s.trim();
}

function f(s){
  return g(s).toUpperCase();
}

function greet(who) {
  console.log("Hello " + f(who));
}

greet("Harry");
console.log("Bye");
```

**Esercizio 2**: Comprensione codice seguente

```javascript
function xyz(num, tl) {
   var ns = num.toString();
   var nz = tl - ns.length;
   for (var i = 1; i <= nz; i++) {
      ns = "0" + ns;
   }
   return ns;
}
```

**Esercizio 3**: reimplementare i seguenti metodi di `Array.prototype`

* `[2,4,8].every(function(n){ return n>0; }) // true` (verifica il predicato su ogni elemento)
* `[2,4,8].some(function(n){ return n<0; }) // true` (testa se il predicato vale in almeno un elemento)
* `unshift()`: aggiunge uno o più elementi in testa all'array e restituisce la nuova lunghezza dell'array.

**Esercizio 4**: reimplementare i seguenti metodi di `String.prototype`

* `split(sep)`: spezza una stringa in un array di stringhe, effettivamente separando la stringa in sottostringhe sulla base del separatore `sep`
    - `"abc,def,ghi".split(",") // ["abc", "def", "ghi"]`
    
**Esercizio 5**: realizzare le seguenti funzionalità

* `"abc".padStart(5,"*") // "**abc"` 
Pads the current string from the start with a given string to create a new string from a given length

<a name="lezione-2102"></a>

<hr />

## Lezione 15: 21/02/2017

Sommario

* TODO

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
