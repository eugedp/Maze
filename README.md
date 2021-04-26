# Maze-main
Programma per calcolare il tempo in cui un animale resta all'interno di uno dei tre bracci di un labirinto.

LANCIARE IL PROGRAMMA SU MAC-OS:
ho utilizzato un ambiente virtuale che ha già installate le dipendenze necessarie:
per attivarlo devo:
1) entrare nelal cartella Maze-main
2) dare il comando: source env/bin/activate 

UTILIZZO:

1) Da dentro la cartella lancio il comando:

   python3 maze.py    

2) Inserisco il numero di sessione nella riga più alta e faccio 'INIZIA'. Dopo ciò non parte nessun timer. I timer partono solo quando scelgo il braccio.

3) Per scegliere un braccio uso le lettere:
  j= Braccio A 
  k= Braccio B
  l= Braccio C
  s= centro del labirinto
  
 4) Appena scelgo un braccio, parte il timer che conta il tempo in quel braccio. Quando scelgo un altro braccio il precedente timer si stoppa e parte quello del secondo braccio.
   - Quando scelgo 's' viene messo in pausa il timer precedente e non ne parte nessun altro.
 
 
 5) Terminato di analizzare la sessione, clicco su FINE SESSIONE.
    Per esportare i file sul file excel, clicco sul bottone ESPORTA.
    Adesso nella cartella Maze-main ho il file excel con i dati della sessione.
    
    
 OSSERVAZIONI:
   A) Se durante la sessione ho commesso un errore, clicco su FINE SESSIONE, poi su ESPORTA. In questo modo potrò ricomincare cliccando ancora su INIZIA.
      I dati acquisiti prima dell'errore vengono comunque esportati nel file excel.
    
 


 
