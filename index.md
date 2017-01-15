---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---

# JavaScript Notebook

Questo è un "quaderno" per imparare le basi della programmazione in JavaScript.

## Programma

### Parte 0: Introduzione

1. Presentazioni
1. Descrizione modulo: obiettivi, modalità, contenuti
1. Rudimenti: cos'è il software, ciclo di sviluppo del software
1. Introduzione alla programmazione
1. Impostazione dell'ambiente di lavoro

### Parte 1: Elementi di base della programmazione in JavaScript

1. Introduzione a JavaScript
1. Tipi di dato
1. Variabili e dichiarazioni
1. Espressioni
1. Istruzioni di controllo
1. Elementi di programmazione funzionale
1. Elementi di programmazione orientata agli oggetti

### Parte 2: Da JavaScript a Java/C#

1. Sulla tipizzazione dei linguaggi 

## Risorse

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
    - Inserire codice JS in una pagina HTML: inline su attributi HTML, blocchi di codice nella pagina con, JavaScript esterno
1. Commenti, punti e virgola e maiuscola
    - Punto e virgola è opzionale ma buona pratica usarlo
    - Case-sensitiveness
    - Commenti: singola linea //, e multilinea /* */
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
    - Da tipo a booleano: valori falsi sono `undefined, null, 0, NaN, ""`
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

## Contenuti

### Presentazioni

* Chi sono
* Chi siete
    - Competenze 'al computer', con la programmazione, con linguaggi imperativi/object-oriented, con JavaScript

### Descrizione modulo

Corso di introduzione alla programmazione
* Pragmatico, operativo, abilitante, di base

#### Obiettivi

* Alla fine del modulo, si è in grado di comprendere e scrivere piccoli programmi, già orientati a contesti applicativi specifici (ad es. web)

#### Modalità

* Teoria minimale e approccio pratico

#### Contenuti

* Rudimenti: software e programmazione
* Basi della programmazione in JavaScript

#### Risorse

* http://www.html.it/guide/guida-javascript-di-base/ -- in italiano, taglio introduttivo

#### Consigli

* La programmazione (così come una lingua) non si impara a lezione, né sui libri: si impara mettendo in pratica, sperimentando, e utilizzando un approccio (pro)attivo
    - Prendere appunti
    - Idealmente, per gran parte, gli appunti dovrebbero essere il codice stesso
* In caso di dubbi, fate domande: potrebbero servire a tutti

### Rudimenti

#### Cos'è il software

#### Ciclo di sviluppo del software

### Introduzione alla programmazione

### Impostazione dell'ambiente di lavoro


```javascript
console.log("Hello world")
```

    Hello world





    undefined




```javascript

```
