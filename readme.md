**Version 0.7.1**

## Introduction
Shepherd Framework is my attempt of creating a CSS starter kit for my daily work. I try to include Best Practices from the Frontend Development Community without the bloat. Also its focused on Responsive Webdesign - but its also usable for old school websites.
It's running on [SASS](http://www.sass-lang.com) and is using the principles of [SMACSS](http://www.smacss.com) and [OOCSS](http://www.oocss.org). Shepherd makes use of the placeholder feature introduced in SASS 3.2, so even its feature rich, its not in your final CSS when you don't use it.

Its not a Framework like [Twitter Bootstrap](http://twitter.github.com/bootstrap/) or [Zurb's Foundation](http://foundation.zurb.com) - if you want already styled components **I suggest to try the former mentioned Tools.**

Its right now in an early alpha stage but its usable - but don't get too attached to the folder structre and modules. Update carefully.

## Documentation
I wrote a rough, already outdated, ugly documentation: http://heroheman.github.io/shepherd/

### Vanilla SASS? Why not Compass?
Shepherd is designed with [Compass](http://compass-style.org) in mind, but its not necessary. Basic mixins are provided e.g. the vendorize function. There is a config.rb in the root folder, so you could also use compass commands (if installed).

## Installation
- Install Sass
- Clone this Project
- Navigate to your project
- use "sass --watch sass/style.scss:css/style.css" or with compass "compass watch"
- Done

## Still To Do
- more modules
- better demo site
- themes
- more OOCSS modules
- include external libraries with submodules
- add more "Smacss"y styling
- read more about BEM and try a BEM branch
- Theming

*PS: English is not my native language, please excuse grammar and typo*
