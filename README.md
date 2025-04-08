# Database intro
Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
Cosa consegnare:
- come visto in classe fai un file readme.md
- inserisci nome della tabella,
- inserisci le colonne per definire il modello
- assicurati di indicare la struttura dati da usare ed eventuali attributi per ciascuna colonna
- PUSHA

## Table name: `cars`

## Table columns
- id (BIGINT) - primary key - auto_increment - NOT NULL
- brand (VARCHAR(50)) - NOT NULL
- model (VARCHAR(150)) - NOT NULL
- color (VARCHAR(50)) - NULL
- price (DECIMAL(7, 2)) - NULL
- price evaluation (VARCHAR(50)) - NULL
- fuel (VARCHAR(50)) - NOT NULL
- year registration (YEAR()) - NOT NULL
- kilometres (MEDIUMINT) - NULL
- power (SMALLINT) - NULL
- transimission (VARCHAR(50)) - NULL 
- seating (TINYINT) - NULL 
- doors (TINYINT) - NULL
- optional (TEXT()) - NULL
- conditions (VARCHAR(50)) - NULL
- description (TEXT()) - NULL