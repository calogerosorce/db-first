## Table name: Cars (entity name: Car)

Columms:

- id BIG PK AI NOT NULL
- casa_produttrice VARCHAR(50) NOT NULL
- modello VARCHAR(50) NOT NULL
- condizioni? VARCHAR(200) NOT NULL
- anno YEAR NOT NULL
- immagine_url VARCHAR(255) NULL
- disponibilita TINYINT DEFAULT(0)
- note TEXT NULL
- prezzo FLOAT(8,2) NOT NULL
- numero_telaio CHAR(17) NOT NULL
- km FLOAT(8,2) NOT NULL 
- targa VARCHAR(8) NULL
- carburante VARCHAR(10) NOT NULL
- porte TYNINT NOT NULL
- anno_di_immatricolazione YEAR NOT NULL
- tipo_di_cambio VARCHAR(10) NOT NULL
- potenza SMALLINT NOT NULL  (60 KW)
- cilindrata SMALLINT NOT NULL (900CC)
- peso SMALLINT NULL
- classe_euro CHAR(5) NOT NULL
- cambio VARCHAR(15) NOT NULL