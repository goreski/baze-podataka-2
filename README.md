# Baze podataka II – SQL vježbaonice

Interaktivne SQL vježbe uz predavanja iz kolegija **Baze podataka II** (Fakultet informatike u Puli).

Svaka vježbaonica je jedna samostalna HTML stranica. Baza podataka (SQLite, biblioteka [sql.js](https://github.com/sql-js/sql.js)) radi u pregledniku studenta, pa nije potreban nikakav poslužitelj. Vježbaonice 04 i 06 uz to sadrže mali interpretator MySQL pohranjenih rutina (funkcije, procedure, kursori, rukovatelji, SIGNAL), a vježbaonica 06 i trigera (BEFORE/AFTER, NEW/OLD), INSERT IGNORE, ON DUPLICATE KEY UPDATE, REPLACE te korisnika, uloga i privilegija (GRANT, REVOKE, SHOW GRANTS), pa se sve piše sintaksom sa slajdova. Vježbaonica 07 (fizička pohrana) nema SQL zadataka osim upita nad katalogom: odgovori se upisuju u polja, a laboratorij simulira RAID 5, datoteke zapisa, blok sa zaglavljem i buffer. Vježbaonica 08 emulira MySQL indekse (CREATE INDEX s prefiksom, ALTER TABLE … ADD/DROP INDEX, SHOW INDEX) i naredbu EXPLAIN pojednostavljenim modelom troška.

## Vježbaonice

| # | Predavanje | Zadataka |
|---|------------|---------:|
| 01 | [Ponavljanje I: SQL jezik](01-ponavljanje-sql/) · [asistent](https://notebook.google.com/notebook/b4074a6c-5329-49c8-8565-5c3777267d4c) | 29 |
| 02 | [Ponavljanje II: SQL DDL](02-ponavljanje-ddl/) · [asistent](https://notebook.google.com/notebook/6bf7da5d-018a-4929-9d2d-359e3d9baf5e) | 19 |
| 03 | [SQL DDL II](03-sql-ddl-ii/) · [asistent](https://notebook.google.com/notebook/96041da4-927a-4210-b8b6-46f2dd6e5748) | 19 |
| 04 | [SQL pohranjene procedure](04-pohranjene-procedure/) · [asistent](https://notebook.google.com/notebook/e4dcc377-d8b2-4585-a8c6-59bce7174ae6) | 27 |
| 05 | [Skladište](05-skladiste/) (vizualizacija zadatka) · [asistent](https://notebook.google.com/notebook/e4dcc377-d8b2-4585-a8c6-59bce7174ae6) | – |
| 06 | [Napredni SQL DDL](06-napredni-sql-ddl/) · [asistent](https://notebook.google.com/notebook/4fee5d0d-34fb-42b9-b96b-8a9e04ad0c53) | 25 |
| 07 | [Sustavi fizičke pohrane](07-fizicka-pohrana/) · [asistent](https://notebook.google.com/notebook/d949cdca-497c-410b-bc50-f1e7f4e70b11) | 30 |
| 08 | [Performanse baze podataka i indeksi](08-performanse-indeksi/) · [asistent](https://notebook.google.com/notebook/7c32235c-ac02-425a-91eb-5a0e109a5e3f) | 24 |

## Struktura

```
index.html                 početna stranica s popisom vježbaonica
01-ponavljanje-sql/        jedna mapa po predavanju
  index.html
02-ponavljanje-ddl/
  index.html
03-sql-ddl-ii/
  index.html
04-pohranjene-procedure/
  index.html
05-skladiste/
  index.html             vizualizacija zadatka sa slajdova 48–67
06-napredni-sql-ddl/
  index.html
07-fizicka-pohrana/
  index.html             zadaci s provjerom, laboratorij (RAID, zapisi, buffer) i katalog
08-performanse-indeksi/
  index.html             indeksi, EXPLAIN (pojednostavljeni MySQL optimizator), laboratorij B+ stabla
.nojekyll                  GitHub Pages poslužuje datoteke bez obrade
```

Nova vježbaonica: nova mapa `NN-naziv/index.html` i nova stavka u `index.html` i u tablici iznad.

## Objava (GitHub Pages)

Settings → Pages → Build and deployment → Source: **Deploy from a branch**, Branch: **main**, mapa **/ (root)** → Save.

Stranica je nakon minute ili dvije dostupna na `https://goreski.github.io/<naziv-repozitorija>/`.
