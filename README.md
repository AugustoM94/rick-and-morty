This template should help get you started developing with Vue 3 in Vite.

Recommended IDE Setup
VSCode + Volar (and disable Vetur) + TypeScript Vue Plugin (Volar).

Customize configuration
See Vite Configuration Reference.

Project Setup
npm install
Compile and Hot-Reload for Development
npm run dev
Compile and Minify for Production
npm run build
Scaffolding progetto
Se creo prima repo
clona la repo dentro cartella esercizi

apro la cartella in vs code

digitare:

  npm create vue@latest
alla prima domanda sul nome del progetto mettere un punto ad indicare che il progetto è quello della cartella corrente

alla seconda domanda 'pacckage-name' inserire il nome del progetto ovvero lo stesso nome della repo

proseguire rspondndo sempre no

digitare:

    npm install
per controllare che tutto funziona far partire il server

    npm run dev
per arrestare il server:

        ctrl + c
Se creo prima progetto
apro la cartella degli esercizi in vs code

digitare:

  npm create vue@latest
alla prima domanda sul nome del progetto mettere il nome della repo

proseguire rspondendo sempre no

mi porto dentro la cartella creata:

      cd  nome repo
      code . -r
digitare:

    npm install
per controllare che tutto funziona far partire il server

    npm run dev
per arrestare il server:

        ctrl + c
Se tutto funziona pusho su github

Pulizia dello scaffolding
Apro App.vue e cancello tutto e scrivo il mio codice in modalità 'options'
Apro la cartella components e la svuoto
Apro la cartella assets svuoto tutto tranne main.css
Cancello tutto il contenuto del main.css e lo rinomino in main.scss
creo in assets le cartelle images e styles
sposto dentro la cartella styles main.scss
aggiorno il path a main.scss in main.js
aggiungo eventuale cartella immagini a public
aggiungo dentro la cartella styles una cartella partials per i file partial scss (es. varibili, animazioni, mixins, ecc).


###Installare dipendenze 

`sh 
     npm install -D sass
`

`sh     
    npm install bootstrap axios   @fortawesome/fontawesome-free
`
 
 - importare bootstrap dentro main.scss  @import 'bootstrap/scss/bootstrap'