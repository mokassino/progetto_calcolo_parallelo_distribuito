# Progetto Calcolo parallelo e distribuito
Traccia 5: Implementazione di un algoritmo parallelo (np core) per il calcolo dell'operazione c = alpha*a + b , con a,b vettori di dimensione N e alpha uno scalare, in ambiente openMP

## File utilizzati
1. `effplot.py` è stato usato per creare i grafici nella relazione
2. `executor.py` è stato usato per calcolare i tempi nella tabella, generare un numero alpha casuale e automatizzare l'esecuzione di file_populator.c per creare i file ed esegue 100 volte vectorsum.c per tutti gli input scelti, con il numero di processori specificato in input.
3. `file_populator.c` è un programma che si occupa di popolare i due file da cui vengono letti i valori per i due array
4. `vectorsum.c` è il programma descritto nella traccia 5
