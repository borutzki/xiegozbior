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
