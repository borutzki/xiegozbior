# Xięgozbiór

Poniżej zbiór kwestii technicznych i dokumentacji, jak powstaje cały ten blog.

## Jak przygotować sobie środowisko?

1. Zainstaluj Ruby zgodnie z instrukcją z Jekylla: <https://jekyllrb.com/docs/installation/macos/>
2. Zrób `bundle install` w ścieżce repozytorium.
3. Doinstaluj brakujące zależności:

```bash
bundle add csv
bundle add logger
bundle add base64
bundle install
```

> Po co te zależności? To coś z wersją Jekylla / Ruby. Znalezione w tym wątku na StackOverflow: <https://stackoverflow.com/questions/79348210/github-pages-jekyll-serve-issue>

## Jak odpalić serwer Jekyll lokalnie?

```bash
bundle exec jekyll serve
```

## Logotyp

- czcionka `Pirata`
- kolory czarno-białe: `ffffff` oraz `000000`
- przy rozmiarze obrazka `2500px x 2500px`, grubość obramki w logo: `100px`

## Obrazki

- zdjęcia w formacie 4:5
- znak wodny: `assets/logotypy/xiegozbior_watermark.png`

## Czcionka

Testowo ustawiłem `Palatino`, ale być może się to zmieni.

## Social ikonki

Tu poradnik z którego korzystam do dodawania nowych ikonek w stopce:
<https://blog.jakelee.co.uk/adding-new-social-media-link-to-minima/>

## Jak włączyłem paginację?

1. Dodaj `jekyll-paginate` do Gemfile: `gem 'jekyll-paginate', '~> 1.1'`
2. Zmień nazwę pliku `index.md` na `index.html`.
3. Dodaj do `_config.yml` plugin `jekyll-paginate`.
4. Dodaj do `_config.yml` zmienną `paginate: 10`.

## Publikowanie

1. Instagram
2. Facebook
3. Goodreads
4. Lubimyczytac
5. Mastodon

### Instagram

- [ ] Nowy post: zdjęcie z wpisu
- [ ] Kopiuj-wklej zajawki
- [ ] Dodaj hashtagi
- [ ] Oznacz wydawnictwo i autora (jeżeli opinia jest bardziej pozytywna niż negatywna)
- [ ] Publikuj

- [ ] Stwórz story z linkiem

### Facebook

- [ ] Nowy post: zdjęcie z wpisu
- [ ] Dodaj tytuł z wpisu na początku postu
- [ ] Kopiuj-wklej zajawki
- [ ] Dodaj link do wpisu (template poniżej)
- [ ] Dodaj hashtagi
- [ ] Oznacz wydawnictwo i autora (jeżeli opinia jest bardziej pozytywna niż negatywna)
- [ ] Publikuj

```txt
Autor - Tytuł Książki

<zajawka>

Link do wpisu 🔗
<link>

#hashtagi
```

### Goodreads

- [ ] Kopiuj-wklej zajawki
- [ ] Dodaj link do wpisu (template poniżej)
- [ ] Dodaj daty przeczytania i opinię
- [ ] Publikuj

```txt
<zajawka>

Link do wpisu 🔗
<link>
```

### LubimyCzytac

- [ ] Kopiuj-wklej zajawki
- [ ] Dodaj link do wpisu (template poniżej)
- [ ] Dodaj datę przeczytania i opinię
- [ ] Publikuj

```txt
<zajawka>

Link do wpisu 🔗
<link>
```

### Mastodon

- [ ] Nowy post: zdjęcie z wpisu
- [ ] Dodaj tytuł z wpisu na początku postu
- [ ] Pierwszy akapit zajawki
- [ ] Oryginalny wpis: Link do wpisu
- [ ] Dodaj hashtagi
- [ ] Publikuj

```txt
Autor - Tytuł 

<akapit zajawki>

Link do wpisu 🔗
<link>

#hashtagi
@ksiazki

Pełny wpis w wątku poniżej! ⬇️
```
