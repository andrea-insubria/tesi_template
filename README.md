# Progetto tesi template

In questa cartella trovat un template per il progetto di tesi sia esso triennale o magistrale. Naturalmente questo è solo un aiuto, quindi potete personalizzarlo e o ricorrere ad altre risorse per strutturare la tesi.

## Informazioni preliminari

Per utilizzare il template potete procedere in due modi:

  1. se si ha un account github o si è intenzionati a crearlo, potete 
    * creare l'account github
    * scaricare e installare *github desktop*, questo non è essenziale ma è più *user friendly* rispetto all'utilizzo da linea di comando in bash. Se volete utilizzare la modalità d'uso da linea di comando suggerisco di leggere questa [guida](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners) passo passo.
  2. entrati nel vostro account e un volta che si è sulla pagina del progetto si può selezionare il pulsante per clonare il progettoe scegliere se aprirlo in _github desktop_ oppure scaricarlo in formato compresso.
  3. una volta che avete a disposizione la la cartella con il template della tesi, potete vedere che la struttura è questa 
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

Il file `tesi.tex` è il file principale, all'interno di questo ci sono i comandi `\include{<file>}` che fanno riferimento ai capitoli contenuti nella directory `tesi_data`.  
Nella directory `figures` vanno messe tutte le immagini che si inseriscono nell'elaborato, per vedere esempi di come si possono inserire le immagini nella tesi si può vedere il capitolo `A.tex`.  

## Compilazione
Il template così come fornito è compilabile direttamente in `LaTeX`, in modo tale da vedere il risultato e fare qualche prova base per capirne il funzionamento. Per quanto riguarda distribuzioni LaTeX e guide base sul suo uso vi rimando alla pagina [`Risorse`](https://andrea-insubria.github.io/risorse/) del mio sito web dove troverete la sezione *Scrivere con LaTex*.

