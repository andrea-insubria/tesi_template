# Progetto tesi template

In questa cartella trovate un _template_ per il progetto di tesi sia esso triennale o magistrale. Naturalmente questo è solo un aiuto, quindi potete personalizzarlo e o ricorrere ad altre risorse per strutturare la tesi come meglio credete/prferite.

## Informazioni preliminari

Il modo più semplice per utilizzare il template è scaricandolo il progetto in formato compresso con il pulsante _Clone or download_. Se invece si vuole utilizzare il progetto ma mantenendolo sincronizzato online con github potete procedere come segue:

  1. se si ha un account github o si è intenzionati a crearlo, potete 
  
    * creare l'account github
    * scaricare e installare *github desktop*, questo non è essenziale ma è più *user friendly* rispetto all'utilizzo da linea di comando in bash. Se volete utilizzare la modalità d'uso da linea di comando suggerisco di leggere questa [guida](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners){target="_blank"} passo passo.
  2. entrare nel vostro account, accedere alla pagina del progetto di template della tesi e selezionare il pulsante _Use this template_ e assegnare un nome al proprio progetto di tesi.
  3. aprire il progetto e scegliere di aprirlo in _github desktop_ (opzione che si trova in _Clone or download_. In questo modo si crea una copia locale del template e qualsiasi modifica che fate ai file in questa directory è sincronizzata con github desktop, in questo modo avrete a disposizioni anche tutte le variazioni che avete fatto e potete recuperare le versioni precedenti.
  
Una volta proceduto in uno dei due modi testé descritti, avrete a disposizione la cartella con il template della tesi, potete vedere che la struttura del progetto è questa 
```
		.
		│    tesi.tex
		│    tesi.tex.latexmain
		│    logo.pdf
		│    logo.jpg
		└─── figures
		│      image.jpg
		└─── tesi_data
		       introduzione.tex
		       A.tex
		       B.tex
		       C.tex
``` 

Il file `tesi.tex` è il file principale, all'interno di questo ci sono i comandi `\include{<file>}` che permettono di inserire i cotenuti dei capitoli, che sono nella directory `tesi_data`.  
Nella directory `figures` vanno messe tutte le immagini che si inseriscono nell'elaborato, per vedere esempi di come si possono inserire le immagini nella tesi si veda il capitolo `A.tex`.  

## Compilazione
Il template così come fornito è compilabile direttamente in `LaTeX`, come detto sopra il file da compilare è `tesi.tex`. Una volta compilato vedrete il risultato e vi consiglio di fare qualche prova "base" per capirne il funzionamento. 
Per quanto riguarda distribuzioni LaTeX e guide base sul suo uso vi rimando alla pagina [`Risorse`](https://andrea-insubria.github.io/risorse/) del mio sito web dove troverete la sezione *Scrivere con LaTex*.

Volendo è anche possibile modificare e compilare il file direttamente dal browser su _github_, ma per fare questo è necessario  
utilizzare le _actions_ di github. Solo a titolo di esempio, in questa [pagina](https://github.com/marketplace/actions/latex-compilation){target="_blank"} una _action_ per la compilazione dei file latex.
