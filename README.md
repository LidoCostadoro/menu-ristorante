# Ristorante Costadoro

## Struttura dei file e istruzioni di modifica
- Ogni file contenuto nella cartella `menu` rispecchia una Categoria del menù concordato, nel nostro caso abbiamo:
  - AntipastiDiMare.txt
  - AntipastiDiTerra.txt
  - Bianchi.txt
  - Bibite.txt
  - C&L.txt (Caffè & Liquori)
  - Contorni.txt
  - Frutta.txt
  - Insalatone.txt
  - PrimiDiMare.txt
  - PrimiDiTerra.txt
  - Rossi.txt
  - SecondiDiMare.txt
  - SecondiDiTerra.txt
  
- Ogni riga di ogni file rappresenta una portata di quella categoria (file)
- Tutte le righe, e dunque portate, sono composte da 3 informazioni:
  - 1 titolo piatto
  - 2 prezzo (senza il carattere €, che viene inserito in automatico)
  - 3 eventuale descrizione (facoltativa)
- Le 3 informazioni separate da un carattere speciale `|` componendo così la riga,
> ESEMPIO RIGA: <br>
> Pasta e fagioli|5|pasta con fagioli Borlotti<br>
> **i dati devono essere inseriti rispettando l'ordine delle 3 informazioni**: al primo posto sempre il titolo, al secondo il prezzo e al terzo la descrizione (facoltativa)
- Se si desidera **annullare** un piatto specifico basterà anteporre ad inizio riga il carattere speciale `|` <br> in tal modo il piatto rimarrà nel file, pronto ad essere reintegrato appena disponibile senza dover riscrivere le 3 informazioni
> ESEMPIO: <br>
> |Pasta e fagioli|5|pasta con fagioli Borlotti <br>
> **in tal caso il piatto verrà ignorato e non sarà visualizzabile nel sito, ma rimane disponibile nel file**
