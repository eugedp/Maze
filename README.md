# Maze-main
Programma per calcolare l'ordine dei bracci di un labirinto un cun un animale si muove e calcolare il tempo in cui un animale resta all'interno di ogni bracco.

LANCIARE IL PROGRAMMA SU MAC-OS:
creao un ambiente virtuale che ha già installate le dipendenze necessarie:
per attivarlo devo:
1) entrare nella cartella Maze-main
2) Creao l'ambiente virtuale con il comando: python3 -m venv maze 
3) dare il comando: source maze/bin/activate 

INSTALLAZIONE:
A) Per prima cosa installo tutte le dipendenze con il comando:
    pip install -r requirements.txt

UTILIZZO
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
    
 


 
