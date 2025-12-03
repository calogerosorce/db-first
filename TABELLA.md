## Table name: Cars (entity name: Car)

Columms:

- id BIG PK AI NOT NULL
- macchina VARCHAR(30) NOT NULL
- modello VARCHAR(60) NOT NULL
- condizioni VARCHAR(200) NOT NULL
- anno SMALL NOT NULL
- immagine NULL
- disponibilità TINYINT DEFAULT(0)
- note TEXT NULL
- prezzo SMALL NOT NULL
- numero_telaio INT NOT NULL
- km NOT NULL FLOAT(8,2)
- targa VARCHAR(8) NULL
- carburante VARCHAR(10) NOT NULL
- porte SMALL NOT NULL
- anno_di_immatricolazione YEAR NOT NULL
- tipo_di_cambio VARCHAR(10) NOT NULL
- potenza SMALL NULL
- cilindrata SMALL NOT NULL
- peso SMALL NULL
- classe_euro CHAR(5) NOT NULL