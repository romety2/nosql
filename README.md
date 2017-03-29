## Łukasz Mielewczyk

[Rozwiązanie zadań](https://romety2.github.io/nosql/)

(zaliczenie)

- [ ] EDA

(egzamin)

- [ ] Aggregation Pipeline
- [ ] MapReduce

| Nazwa | Wartosć    |
|-----------------------|------------|
| Procesor | Core(TM) i3-4005U CPU 1,7 GHz 1,7 GHz |
| RAM | 12 GB |
| Dysk | HDD |
| System operacyjny | Windows 10 64-bit |
| Wersje użytych baz danych | |
| Wersje bibliotek | |
|

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
