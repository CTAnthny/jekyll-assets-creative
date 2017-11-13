# Jekyll Assets Creative

A port of the jekyll creative theme (port) to jekyll assets (rails-style asset management with sprockets) 

## Features

- Bootstrap 3
- Jquery 3.2.1
- Sass and custom bootstrap overwrites
- Font Awesome
- Autoprefixer
- Asset caching and cache busting with digests
- Minification, uglification, and concatenation of js and css
- JS ES6 syntax support
- Livereload
- Image Magick and Image Optim
- Jekyll SEO tags support
- Jekyll Pagination
- Minima theme markdown syntax highlighting styles
- Google analytics
- Disqus comments 

## Prerequisites

- ruby
- ruby gems
- jekyll `gem install jekyll`
- bundler `gem install bundler`

## Installing

- fork
- `git clone`
- `bundle`

## Getting Started

- edit the `_config.yml` file for site and user specific details (title, email, etc.)

- Development: `bundle exec jekyll serve`
- Production: `bundle exec jekyll build`

## Other Notes

- Default layouts for the minima theme are still included for easy blog setup
- Minima styles are *not* included though, so if desired copy them from the gem directory `bundle show minima`

## Built With

* [Jekyll Assets 2.4](https://github.com/jekyll/jekyll-assets/tree/2.4-legacy)
* [Sprockets 3](https://github.com/rails/sprockets)
* [Jekyll Creative Theme](https://github.com/volny/creative-theme-jekyll)

## Acknowledgments

* All the authors, contributors, and maintainers of the above-mentioned libraries and components =)
