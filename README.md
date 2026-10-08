# Baze podataka II – SQL vježbaonice

Interaktivne SQL vježbe uz predavanja iz kolegija **Baze podataka II** (Fakultet informatike u Puli).

Svaka vježbaonica je jedna samostalna HTML stranica. Baza podataka (SQLite, biblioteka [sql.js](https://github.com/sql-js/sql.js)) radi u pregledniku studenta, pa nije potreban nikakav poslužitelj.

## Vježbaonice

| # | Predavanje | Zadataka |
|---|------------|---------:|
| 01 | [Ponavljanje I: SQL jezik](01-ponavljanje-sql/) · [asistent](https://notebook.google.com/notebook/b4074a6c-5329-49c8-8565-5c3777267d4c) | 29 |

## Struktura

```
index.html                 početna stranica s popisom vježbaonica
01-ponavljanje-sql/        jedna mapa po predavanju
  index.html
.nojekyll                  GitHub Pages poslužuje datoteke bez obrade
```

Nova vježbaonica: nova mapa `NN-naziv/index.html` i nova stavka u `index.html` i u tablici iznad.

## Objava (GitHub Pages)

Settings → Pages → Build and deployment → Source: **Deploy from a branch**, Branch: **main**, mapa **/ (root)** → Save.

Stranica je nakon minute ili dvije dostupna na `https://goreski.github.io/<naziv-repozitorija>/`.
