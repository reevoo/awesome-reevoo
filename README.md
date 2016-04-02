# Awesome Reevoo [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A collection of awesome libraries, frameworks, tools, resources and other beasts used in [Reevoo](http://reevoo.github.io/).

## Table of contents

- [Front-end Development](#front-end-development)
- [Infrastructure](#infrastructure)

## Front-end Development

- JavaScript
  - [React](https://facebook.github.io/react/) - Don't you know what is React? Really?
  - [Redux](http://redux.js.org/) - Our favourite implementation of a Flux approach.
  - [npm](https://www.npmjs.com/) - Because we need a package manager for JavaScript modules.
    - [npm docs](https://docs.npmjs.com/) - Direct link to npm documentation.
- CSS
  - [BEM](https://en.bem.info/) - Block-Element-Modifier convention. Helps with CSS. A lot.
  - [SASS](http://sass-lang.com/) - If you are not using SASS to write your CSS rules, you are wasting time.
- Building tools
  - [Babel](https://babeljs.io/) - Tired of waiting for browsers to implement the newest and awesome ES6 features? Wait no more. Start using Babel and write the JavaScript (or EcmaScript) code of tomorrow, today ;)
  - [Webpack](https://webpack.github.io/) - A module bundler that helps saving a lot of time. Deserves its own category.
    - [Webpack and React](http://survivejs.com/webpack_react/introduction/) - A free book to make Webpack accept React as a good friend.
  - [PostCSS](http://postcss.org/) - This one is really awesome. It allows you to use a huge number of plugins on your CSS to make your life easier.
    - [Autoprefixer](https://github.com/postcss/autoprefixer) - Our favourite PostCSS plugin. You write standard CSS and it will add the vendor prefixes (`-moz, -webkit, -msie, ...`) needed according to you configuration.

## Infrastructure

- Containers
  - [Docker](https://www.docker.com/) - Don't you know what Docker is? Really?
  - [Kubernetes](https://kubernetes.io/) - Kubernetes is an open-source system for automating deployment, operations, and scaling of containerized applications, oh and it's awesome.
    - [KubeCon EU 2016 - Videos](https://www.youtube.com/playlist?list=PLosInM-8doqcBy3BirmLM4S_pmox6qTw3) - All the presentations from KubeCon EU 2016 that took place in London, watch out for the awesome keynote from the awesome [Kelsey Hightower](https://twitter.com/kelseyhightower).
  - [CoreOS](https://coreos.com/) - CoreOS is designed for security, consistency, and reliability. CoreOS is lightweight and runs on almost any platform. Instead of installing software packages with a package manager like apt or yum everything is installed as a container.
- [Chef](https://www.chef.io/chef/) - Configuration management with the power of Ruby. At Reevoo we manage over 100 servers using chef.

___

This list is inspired by the [awesome list of awesome lists](https://github.com/sindresorhus/awesome).
