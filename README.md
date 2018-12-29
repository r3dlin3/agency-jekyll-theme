# Agency Jekyll vNext theme

Up-to-date version of [Agency theme](https://github.com/y7kim/agency-jekyll-theme) for [Jekyll](http://jekyllrb.com/).

This theme is theme based on the [Agency bootstrap theme](https://startbootstrap.com/template-overviews/agency/).

This version differs from the original with:
* Up to date Jekyll (3.7.2) and plugins
* Use of CDN instead of local files for Bootstrap, Bootswatch theme & FontAwesome
* Add a neat favicons/touch icon
* Use of SASS
* Included file for:
   * Analytics (site-analytics.html)
   * To load all CSS (site-styles.html)
   * To load all JS (site-js.html)
   * To declare icons (site-favicons.html)
* Use of collection for projects
* Use of data for:
   * Team members
   * Social icons
   * Navigation bar
* Use of plugins for:
   * SEO tags
   * RSS Feed

> Note: the navigation bar links are not computed automatically (as in https://github.com/t413/SinglePaged) to let user use additional links

## Credits

This upgraded version is based on :

* https://y7kim.github.io/agency-jekyll-theme/
* https://github.com/CloudCannon/hydra-jekyll-template
* https://github.com/t413/SinglePaged
* https://github.com/daviddarnes/alembic

## To do

* [ ] Make Contact form work (e.g. with [FormSpree](https://formspree.io/))

## How to use

1. Add your site and author details in `_config.yml`.
2. Add your Google Analytics to `_config.yml`.

## Develop

### Basic Jekyll command:

    bundle install
    bundle exec jekyll build
    bundle exec jekyll serve --livereload

### Sections

Sections are present in the `_posts` folder.

Almost each section has its own style in 

### Portfolio 

Portfolio projects is a collection in the folder `_projects`.

Images are in `/images/portfolio`.

### About

Images are in `/images/about/`

### Team

Team members info are in the data file `_data/people.yml`.

Images are in `/images/team/`.

### Navigation bar/links

Links to include can be set in the file `_data/navigation.yml`.


## Demo

None for this version but the rendering is identical to the 
 [original one](https://y7kim.github.io/agency-jekyll-theme)

