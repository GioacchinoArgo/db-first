nome repo: db-first
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
Per la consegna, potete inserire la vostra tabella in un file markdown come vi ho fatto vedere a lezione, oppure farla su Excel, Fogli Google ecc e fare uno screen.


Colonne|Tipo|Attributi                                             
|---|---|---|
id| TINYINT | PRIMARY_KEY, AUTO_INCREMENT
marca| VARCHAR(30) | NOT NULL                              
modello | VARCHAR(30) | NOT NULL
chilometraggio | INT | NOT NULL                            
anno di produzione | YEAR | NOT NULL
prezzo | INT | NOT NULL
tipo di carburante | VARCHAR(7) | NOT NULL
