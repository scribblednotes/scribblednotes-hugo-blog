# Hello Friend

![Hello Friend](https://github.com/panr/hugo-theme-hello-friend/blob/master/images/screenshot.png?raw=true)

This theme was made to help you present your ideas easier. We all know how hard is to start something on the web, especially these days. You need to prepare a bunch of stuff, configure them and when that’s done — create the content.

This theme is pretty basic and covers all of the essentials. All you have to do is start typing!

## Features

- **dark/light mode**, depending on your preferences (dark is default)
- great reading experience thanks to [**Inter UI font**](https://rsms.me/inter/), made by [Rasmus Andersson](https://rsms.me/about/)
- nice code highlighting thanks to [**PrismJS**](https://prismjs.com)
- an easy way to modify the theme (**Webpack, NodeJS, PostCSS** — initial setup created by [Marcin Dziewulski](http://www.mobily.pl))
- fully responsive

#### Code highlighting

By default the theme is using PrismJS to color your code syntax. All you need to do is to wrap you code like this:

<pre>
```html
  // your code here
```
</pre>

**Supported languages**: css, clike, javascript, apacheconf, applescript, c, csharp, cpp, coffeescript, ruby, csp, css-extras, diff, django, docker, elixir, elm, markup-templating, erlang, fsharp, flow, git, go, graphql, less, handlebars, haskell, http, java, json, kotlin, latex, markdown, makefile, objectivec, ocaml, perl, php, php-extras, sql, processing, scss, python, jsx, typescript, reason, textile, rust, sass, stylus, scheme, pug, swift, yaml, haml, twig, tsx, vim, visual-basic, wasm.

## How to start

You can download the theme manually by going to [https://github.com/panr/hugo-theme-hello-friend.git](https://github.com/panr/hugo-theme-hello-friend.git) and pasting it to `themes/hello-friend` in your root directory.

You can also clone it directly to your Hugo folder:

```
$ git clone https://github.com/panr/hugo-theme-hello-friend.git themes/hello-friend
```

If you don't want to make any radical changes, it's the best option, because you can get new updates when they are available. To do so, include it as a git submodule:

```
$ git submodule add https://github.com/panr/hugo-theme-hello-friend.git themes/hello-friend
```

## How to configure

The theme doesn't require any advanced configuration. Just copy:

```
baseUrl = "https://example.com/"
languageCode = "en-us"
title = "Your site title"
theme = "hello-friend"
copyright = ""
paginate = 5

[params]
  subtitle = "Your site subtitle"

[params.logo]
  logoText = "hello friend"
#   or
#
#   path = "/img/your-example-logo.svg"
#   alt = "Your example logo alt text"

[menu]
  [[menu.main]]
    identifier = "about"
    name = "About"
    url = "/about"
  [[menu.main]]
    identifier = "contact"
    name = "Contact"
    url = "/contact"

```

to `config.toml` file in your Hugo root directory and change params fields.

## How to run your site

From your Hugo root directory run:

```
$ hugo server -t hello-friend
```

and go to `localhost:1313` in your browser. From now on all the changes you make will go live, so you don't need to refresh your browser every single time.

## How to edit the theme

If you really want to edit the theme, you need to install Node dependencies. To do this, go to the theme directory (from your Hugo root directory):

```
$ cd themes/hello-friend
```

and then run:

```
$ npm install
$ npm i yarn
$ yarn
```

## How to contribute

If you spot any bugs, please use [Issue Tracker](https://github.com/panr/hugo-theme-hello-friend/issues) or if you want to add a new feature directly please create a new [Pull Request](https://github.com/panr/hugo-theme-hello-friend/pulls).

## Licence

Copyright © 2018 Radosław Kozieł ([@panr](https://twitter.com/panr))

The theme is released under the MIT License. Check the [original theme license](https://github.com/panr/hugo-theme-hello-friend.git/blob/master/LICENSE.md) for additional licensing information.
