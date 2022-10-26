CREATE DATABASE progetto_esame;
USE progetto_esame;

CREATE TABLE calciatori (
    id int AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR (30) NOT NULL,
    cognome VARCHAR (30) NOT NULL,
    ruolo CHAR (1) NOT NULL,
    nazione CHAR (30) NOT NULL,
    gol_fatti int not NULL,
    assist_fatti int NOT NULL,
    ammonizioni int NOT NULL DEFAULT 0,
    espulsioni int NOT NULL DEFAULT 0,
    
