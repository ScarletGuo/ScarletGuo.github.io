# scarletguo.github.io

Personal site. Jekyll, served by GitHub Pages from `master`.

## Adding a publication

Edit [`_data/publications.yml`](_data/publications.yml) — nothing else. Both the
home page and `/publications/` read from it.

```yaml
- title: "Paper Title"
  authors: "**Zhihan Guo**, Someone Else"   # ** ** bolds your name
  venue: "VLDB"
  year: 2026
  selected: true                            # optional — also shows on the home page
  links:
    - name: "Paper"
      url: "/files/mypaper.pdf"             # local PDFs live in /files/
```

## Adding a job, degree or course

Edit [`_data/experience.yml`](_data/experience.yml). It has four lists: `work`,
`earlier`, `education`, `teaching`. `selected: true` on a `work` entry also puts
it on the home page.

Logos go in `images/logo/small/` at 168px (2× their 42px display size):

```sh
sips -Z 168 images/logo/new-logo.png --out images/logo/small/new.png
```

## Structure

```
_layouts/base.html            the only layout
_includes/profile.html        sidebar: identity + nav
_includes/publication-list.html
_includes/job-list.html
_data/publications.yml        all publications
_data/experience.yml          work / earlier / education / teaching
_data/navigation.yml          sidebar nav (url must match each page's permalink)
_pages/about.md               /
_pages/publications.md        /publications/
_pages/experience.md          /experience/
assets/css/site.css           the whole stylesheet
```

Identity in the sidebar (name, title, employer, location, links) comes from
`author:` in [`_config.yml`](_config.yml).

## Running locally

macOS system Ruby needs a UTF-8 locale or Sass fails on the en dashes:

```sh
export LANG=en_US.UTF-8 LC_ALL=en_US.UTF-8
bundle install          # first time; installs into vendor/bundle
bundle exec jekyll serve
```

Then open http://localhost:4000.
