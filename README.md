# Abbia

### Gulp Overview

Github pages and jekyll have some major limitations when used alone (such has inability to use jekyll plugins). This gulp workflow provides some workarounds

running 'gulp' will compile and concatenate scss and js files and open up the site in a web browser with hot reloading

running 'gulp build --prod' compiles, concatenates, minifys, and gzips css and js files, optimizes all images, and builds a production ready version of the site with jekyll plugins.

'gulp deploy' pushes the production build to the github pages branch

### Adding New Pages

Add a new markdown file to the 'src' directory. Make sure it has the 'pages' layout. Use the 'default' layout to make a another page like the home page

```
---
layout: pages
permalink: /learn-more/
title: Learn More
---
```

## To get started
```sh
npm install gulp
```
```sh
npm install
```
```sh
bundle install
```

```sh
$ gulp
```

## To Deploy

```sh
$ gulp build [--prod]
```

```sh
$ gulp deploy
```

#### Settings
In your `_config.yml` and `humans.txt` you should add your Github and Twitter
profile if you want to.


## Github
For more information on how to use your new project, please refer to the [README
on Github](https://github.com/sondr3/generator-jekyllized).

## Owner

> [Elizabeth Simonian](http://esimonian.github.io/abbia)
