// Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

# Concessionario 

- Id BIGINT AI NOTNULL UNIQUE 
- Marca VARCHAR (20) NOTNULL
- Modello VARCHAR (20) NOTNULL
- Targa CHAR (7) NULL UNIQUE
- Carburante VARCHAR (30) NULL
- Stato  VARCHAR (20) NULL 
- Cambio VARCHAR (10) NULL 
- Anno DATE NULL 
- Classe ecologica CHAR (5) NULL 
- Prezzo DECIMAL (9,2) NULL
- Km MEDIUMINT NULL DEFAULT 
- Categoria VARCHAR (20) NOTNULL
- Colore VARCHAR (20) NOTNULL
- CV TINYINT NOTNULL
- Note TEXT NULL