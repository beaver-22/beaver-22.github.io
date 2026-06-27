# jaeyong_ko_homepage

Jekyll-based academic personal homepage for Jaeyong Ko.

This site is based on the MIT-licensed
[luost26/academic-homepage](https://github.com/luost26/academic-homepage)
template, matching the structure of the reference site at
<https://jinulee-v.github.io/>.

## Structure

```txt
_data/profile.yml       Profile, education, experience, projects, skills
_data/navigation.yml    Top navigation
_news/                  News collection
_publications/          Publication collection
cv/                     CV source and PDF
assets/                 Template assets
index.html              Homepage layout
publications.html       Publications page
```

## Local Preview

Install Ruby/Bundler prerequisites, then run:

```bash
bundle install
bundle exec jekyll serve
```

On Ubuntu/Debian, native gems may require Ruby headers:

```bash
sudo apt install ruby-dev build-essential
```

The local server will print a preview URL, usually:

```txt
http://127.0.0.1:4000/
```

## Content Notes

- The CV PDF linked from the site is `cv/CV_jaeyongko.pdf`.
- The LaTeX CV source is `cv/main.tex`.
- Main profile content should be edited in `_data/profile.yml`.
- Publications should be added under `_publications/<year>/`.
- News items should be added under `_news/`.

## Deployment

For a clean GitHub Pages user site, use a repository named:

```txt
<github-username>.github.io
```

For a project site, set `baseurl` in `_config.yml` to the repository path.
