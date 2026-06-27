# beaver-22.github.io

Academic homepage for Jaeyong Ko, built with Jekyll and deployed through GitHub Pages.

Live site:

```txt
https://beaver-22.github.io/
```

## Overview

This repository contains a personal academic website with:

- Profile and contact links
- Education
- Publications
- Research experience
- Selected projects
- Other experience
- News
- CV PDF

The site is based on the MIT-licensed
[academic-homepage](https://github.com/luost26/academic-homepage) template.

## Editing Content

Most content lives in data or collection files:

```txt
_data/profile.yml                 Profile, education, experience, projects
_data/authors.yml                 Publication author links and highlighting
_news/                            Homepage news items
_publications/                    Publication entries
cv/CV_jaeyongko.pdf               Downloadable CV
assets/images/badges/             Institution and organization logos
assets/images/covers/             Publication cover figures
assets/images/photos/portrait.jpg Profile photo
```

## Local Preview

Install Ruby, Bundler, and Jekyll dependencies:

```bash
bundle install
bundle exec jekyll serve
```

Then open:

```txt
http://127.0.0.1:4000/
```

On Ubuntu/Debian, native gems may require:

```bash
sudo apt install ruby-dev build-essential
```

## Deployment

This repository is intended to be deployed as a GitHub Pages user site from the `main` branch root.

GitHub Pages settings:

```txt
Source: Deploy from a branch
Branch: main
Folder: / (root)
```
