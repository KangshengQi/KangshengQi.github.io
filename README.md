# kangshengqi.github.io

Personal academic website of Kangsheng Qi, built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme.

## Where to edit

| What                     | File                                                                   |
| ------------------------ | ---------------------------------------------------------------------- |
| Name, site URL, settings | `_config.yml`                                                          |
| About page (bio)         | `_pages/about.md`                                                      |
| Profile photo            | add `assets/img/prof_pic.jpg`, then uncomment `image:` in `about.md`   |
| Publications             | `_bibliography/papers.bib` (`selected = {true}` shows it on the About) |
| CV page content          | `_data/cv.yml`                                                         |
| CV PDF                   | replace `assets/pdf/Kangsheng_Qi_CV.pdf`                               |
| Email / GitHub / Scholar | `_data/socials.yml`                                                    |

## Run locally

```bash
bundle install
bundle exec jekyll serve   # http://localhost:4000
```

Pushing to `main` runs `.github/workflows/deploy.yml`, which builds the site and publishes it to the `gh-pages` branch.
