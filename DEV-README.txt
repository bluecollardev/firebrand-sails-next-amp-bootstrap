FIREBRAND DEV README

Setting up facebook page tab

- Go to https://developers.facebook.com/apps

AMP

AMP Examples:
https://ampbyexample.com

Dev Paradigms
- All development done using JavaScript with views that render AMP (browser ouput) OR JSON (service calls used to populate data in an AMP 'view') output
- All apps/websites must be isomorphic or server-side rendered for compatibility with AMP specifications; use Express.js for app server
- No client-side JS libs may be used, as they depend on a browser DOM for rendering

Routing:
- Express.js and react-router-dom both support server-side routing

HTTP Client/Framework:
- Axios (https://github.com/axios/axios) supports making requests from either node.js or the browser

JS Frameworks:
- ItemsAPI (itemsapi.com) ItemsAPI is an abstraction layer of Elasticsearch written in Express.js. 
While Elasticsearch is flexible but also very complex, ItemsAPI emphasis on simplicity, productivity and easy to use especially for web and mobile applications. 
ItemsAPI is also set of various open source tools like crawlers, CLI and website generators (mostly written in Node.js).

- Sails.js (https://sailsjs.com) Sails is the most popular MVC framework for Node.js, designed to emulate the familiar MVC pattern of frameworks like Ruby on Rails, but with support for the requirements of modern apps: data-driven APIs with a scalable, service-oriented architecture.

CSS Frameworks:

For internal apps, only the following two CSS frameworks will be used.
https://niutech.github.io/amp-spectre - Advanced functionality, fully AMP-compatible <- RealtyTab online portal?
https://niutech.github.io/amp-surface - Inspired by Material UI, a functional drop in replacement <- RealtyTab online portal?
https://ampstart.com/components - Components designed for internal apps that are shared with client sites will also have a third styling package for AMP Start

Landing Pages or CSS Templates for Client-Sites (one-off sites):
https://ampstart.com
For client sites, we use the following templates:
https://ampstart.com/templates
Components:
https://ampstart.com/components

App structure:
/server
  From sails.js docs:
  api
  assets
  config
  tasks
  views
  .editorconfig
  .eslintignore
  .eslintrc
  .gitignore
  .htmlhintrc
  .sailsrc
  app.js
  Gruntfile.js
  package.json
  README.md