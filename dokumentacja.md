# Xięgozbiór - dokumentacja rzeczy różnych

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

## Czcionka

Testowo ustawiłem `Palatino`, ale być może się to zmieni.

## Social ikonki

Tu poradnik z którego korzystam do dodawania nowych ikonek w stopce:
<https://blog.jakelee.co.uk/adding-new-social-media-link-to-minima/>

## Publikowanie

1. Instagram
2. Facebook
3. Goodreads
4. Lubimyczytac

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

Oryginalny wpis:
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

Oryginalny wpis:
<link>
```

### LubimyCzytac

- [ ] Kopiuj-wklej zajawki
- [ ] Dodaj link do wpisu (template poniżej)
- [ ] Dodaj datę przeczytania i opinię
- [ ] Publikuj

```txt
<zajawka>

Oryginalny wpis:
<link>
```

### Mastodon

- [ ] Nowy post: zdjęcie z wpisu
- [ ] Dodaj tytuł z wpisu na początku postu
- [ ] Pierwszy akapit zajawki
- [ ] Oryginalny wpis: Link do wpisu
- [ ] Dodaj hashtagi

```txt
Autor - Tytuł 

<akapit zajawki>

Oryginalny wpis:
<link>

#hashtagi
```
