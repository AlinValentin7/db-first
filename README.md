// Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

# Macchine
- Id BIGINT AI NOTNULL UNIQUE 
- marca VARCHAR (20) NOTNULL
- modello VARCHAR (20) NOTNULL
- targa CHAR (7) NULL UNIQUE
- carburante VARCHAR (30) NULL
- stato  VARCHAR (20) NULL 
- cambio VARCHAR (10) NULL 
- anno YEAR NULL 
- ? classe_ecologica CHAR (5) NULL <!-- (R)DBMS -->
- prezzo DECIMAL (9,2) NULL
- km MEDIUMINT NULL DEFAULT 
- ? categoria VARCHAR (20) NOTNULL <!--(R)DBMS  -->
- colore VARCHAR (20) NOTNULL
- cv TINYINT NOTNULL
- ? interni Varchar (20) NULL <!-- (R)DBMS -->
- note TEXT NULL