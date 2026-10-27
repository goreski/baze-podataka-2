# Baze podataka II – SQL vježbaonice

Interaktivne SQL vježbe uz predavanja iz kolegija **Baze podataka II** (Fakultet informatike u Puli).

Svaka vježbaonica je jedna samostalna HTML stranica. Baza podataka (SQLite, biblioteka [sql.js](https://github.com/sql-js/sql.js)) radi u pregledniku studenta, pa nije potreban nikakav poslužitelj. Vježbaonica 04 uz to sadrži mali interpretator MySQL pohranjenih rutina (funkcije, procedure, kursori, rukovatelji, SIGNAL), pa se rutine pišu sintaksom sa slajdova.

## Vježbaonice

| # | Predavanje | Zadataka |
|---|------------|---------:|
| 01 | [Ponavljanje I: SQL jezik](01-ponavljanje-sql/) · [asistent](https://notebook.google.com/notebook/b4074a6c-5329-49c8-8565-5c3777267d4c) | 29 |
| 02 | [Ponavljanje II: SQL DDL](02-ponavljanje-ddl/) · [asistent](https://notebook.google.com/notebook/6bf7da5d-018a-4929-9d2d-359e3d9baf5e) | 19 |
| 03 | [SQL DDL II](03-sql-ddl-ii/) · [asistent](https://notebook.google.com/notebook/96041da4-927a-4210-b8b6-46f2dd6e5748) | 19 |
| 04 | [SQL pohranjene procedure](04-pohranjene-procedure/) · [asistent](https://notebook.google.com/notebook/e4dcc377-d8b2-4585-a8c6-59bce7174ae6) | 27 |

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
.nojekyll                  GitHub Pages poslužuje datoteke bez obrade
```

Nova vježbaonica: nova mapa `NN-naziv/index.html` i nova stavka u `index.html` i u tablici iznad.

## Objava (GitHub Pages)

Settings → Pages → Build and deployment → Source: **Deploy from a branch**, Branch: **main**, mapa **/ (root)** → Save.

Stranica je nakon minute ili dvije dostupna na `https://goreski.github.io/<naziv-repozitorija>/`.
