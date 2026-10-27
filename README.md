# Davide Pietrafesa

Sito personale: https://cidoimo.github.io

Costruito con Jekyll e il tema [al-folio](https://github.com/alshedivat/al-folio) (licenza MIT).

## Dove si modifica cosa

| Cosa                           | File                                   |
| ------------------------------ | -------------------------------------- |
| Testo della home e foto        | `_pages/about.md`, `assets/img/prof_pic.jpg` |
| Novità in home                 | `_news/` (un file per notizia)         |
| Pubblicazioni                  | `_bibliography/papers.bib`             |
| Presentazioni e poster         | `_pages/publications.md`               |
| CV                             | `_data/cv.yml`                         |
| Cene con delitto               | `_projects/` (un file per cena) e `assets/img/cene/` |
| Link (Scholar, ORCID, Etsy...) | `_data/socials.yml`                    |
| Impostazioni generali          | `_config.yml`                          |

Ogni volta che fai push su `main`, GitHub ricostruisce e pubblica il sito da solo in un paio di minuti.

## Vederlo sul tuo computer prima di pubblicare

Con Docker:

    docker compose up

poi apri http://localhost:8080

Oppure con Ruby (serve Ruby 3.x e ImageMagick):

    bundle install
    bundle exec jekyll serve

poi apri http://localhost:4000
