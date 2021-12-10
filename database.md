# Concessionaria

## Auto Usate

- id | SMALLINT - PRIMARY KEY, UNIQUE, AUTO_INCREMENT, NOTNULL
- numero_telaio | CHAR(17) - NOTNULL, UNIQUE
- modello | VARCHAR(30) - NOTNULL
- anno_immatricolazione | YEAR - NOTNULL
- chilometraggio | MEDIUMINT - NOTNULL
- prezzo | MEDIUMINT - NULL
- sconto | TINYINT - NULL
- condizione | VARCHAR(15) - NULL
- potenza_kW | SMALLINT - NULL
- potenza_cavalli | SMALLINT - NULL
- numero_porte | TINYINT - NULL
- numero_posti | TINYINT - NULL
- metallizzato | TINYINT (vero/falso | 1/0) - NULL
- cerchi in lega | TINYINT (vero/falso | 1/0) - NULL
- precedenti_proprietari | TINYINT - NULL
- veicolo_danneggiato | TINYINT (vero/falso | 1/0) - NULL
- veicolo_non_fumatori | TINYINT (vero/falso | 1/0) - NULL
- tagliandi_certificati | TINYINT (vero/falso | 1/0) - NULL
- garanzia | TINYINT (vero/falso | 1/0) - NULL
- (?)foto_veicolo | ('/car/fiat_duna124155.jpg') | VARCHAR(255) - NULL
- filtro_antiparticolato | TINYINT (vero/falso | 1/0) - NULL
- marmitta_catalitica | TINYINT (vero/falso | 1/0) - NULL
- data_inserimento_database | DATE - DEFAULT (today)


APPOGGIO SU ALTRO DATABASE
- categoria_modello | VARCHAR(25) - NULL
- marca | VARCHAR(25) - NOTNULL
- alimentazione | VARCHAR(30) - NULL
- cambio | VARCHAR(30) - NULL
- nazione_produzione | VARCHAR(30) - NULL
- optional | VARCHAR(255) - NULL
- colore_carrozzeria | VARCHAR(30) - NULL
- colore_imbottiture | VARCHAR(30) - NULL
- materiale_imbottiture | VARCHAR(30) - NULL
- tipo_veicolo | VARCHAR (30) - NULL
- programma_produttore | VARCHAR(255) - NULL
- classe_emissioni | VARCHAR(20) - NULL
- bollino_polveri_sottili | VARCHAR(20) - NULL

