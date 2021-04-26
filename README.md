# Maze
Programma per tracciare come un animale si muove all'interno di un labirinto composto da 3 rami. 
Oltre alla sequenza dei percorsi presi, viene calcolare il tempo in cui un animale resta all'interno di ogni braccio.

INSTALLAZIONE SU MAC-OS:
A) creao un ambiente virtuale in cui installo tutte le dipendenze necessarie:

1) Da terminale entro nella cartella Maze-main;
2) Creao l'ambiente virtuale con il comando: python3 -m venv maze 
3) Attivo l'ambiente con il comando: source maze/bin/activate 

B) installo tutte le dipendenze con il comando: pip install -r requirements.txt

UTILIZZO
1) Con il terminale raggiungo la cartella del programma e lancio il comando:

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
    
 


 
