#Automobile

- id | BIGINT - PRIMARY KEY, NOTNULL, AUTO INCREMENT, UNIQUE
- marca | VARCHAR(50) - NOTNULL
- modello | VARCHAR(50) - NOTNULL
- codice_telaio | CHAR(17) - NULL, UNIQUE
- cavalli | SMALLINT - NULL
- km_percorsi | MEDIUMINT - NULL
- immatricolazione | YEAR - NULL
- condizione | VARCHAR(50) - NULL <!-- nuova / usata / km0 -->
- peso | SMALLINT - NULL
- alimentazione | VARCHARR(10) - NULL
- targa | CHAR(7) - NULL, UNIQUE
- colore | VARCHAR(20) - NULL
- prezzo | DECIMAL(8,2) - NULL
