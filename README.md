## Łukasz Mielewczyk

[Informacje o komputerze oraz wykonane zadania](https://romety2.github.io/nosql/)

(zaliczenie)

- [ ] EDA

(egzamin)

- [ ] Aggregation Pipeline
- [ ] MapReduce

WZORZEC:


## Przedstawić dane

Przykładowy rekord. Ile tego jest/będzie (w sztukach, w GB)

```json
{
  "x": "raz dwa trzy",
  "latlon": [-6, 60]
}
```

Z tych danych zrobię mapki, podsumowania.

## Czyszczenie danych

Zmienić nazwy pól, wybrano te pola i dlaczego.

## Elasticsearch

Mapping -- przygotować i zapisać w Elasticsearch

### Import danych

```sh
time gunzip -c dane.json.gz | .... # calość
...                                # próbka / sample
```

### Przykładowe zapytania

Czego szukam?

### Mapki

Zapytania mapkowe.

```sh
curl localhost:9200/.... | jq .hits.hits[] | przerabiamy na GEOJson / TopoJSON
```

... [mapka-es](mapki-es)


## PostgreSQL

Schema -- przygotować i użyć w trakcie importu.

### Import danych


## MongoDB

Pamiętać aby DateTime było zaimportowane jako DateTime, liczby – to samo

### Import danych
