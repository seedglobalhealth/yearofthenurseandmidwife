# Seed Global Health

> [nursesandmidwives2020.org](https://nursesandmidwives2020.org/)

## Overview

Build a splash page for **Year of the Nurse 2020** campaign. This is a static site hosted on Netlify. This project is built off the opinionated boilerplate for web development based on Google's [Web Starter Kit](https://github.com/google/web-starter-kit.git). 

## Netlify

Netlify is the static site hosting service used for this project. It features continuous deployment from Git allowing us to deploy changes to the site via git push. The Netlify instance for this project is: [https://app.netlify.com/teams/cmaddocks/sites](https://app.netlify.com/teams/cmaddocks/sites)

To commit changes to the site, jump down to the **Quickstart** section of the readme. For minor changes like updating text on the homepage, you can make these directly in Github in the <kbd>app/index.pug</kbd> file. As indicated in the file extension, the markup is written in [PUGjs](https://pugjs.org/) -- a shorthand form of writing HTML. A guide to using PUG can be found [in this article](https://codeburst.io/getting-started-with-pug-template-engine-e49cfa291e33). Once updates have been made, commit this change and the continuous deployment in Netlify will have this updated on the live site within minutes. Content changes can not be made directly in Netlify.

## Features

| Feature                                | Summary                                                                                                                                                                                                                                                     |
|----------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Sass support                           | Compile [Sass](http://sass-lang.com/) into CSS with ease, bringing support for variables, mixins and more. Run `gulp serve` or `gulp` for production                                                                                                      |
| Performance optimization               | Minify and concatenate JavaScript, CSS, HTML and images to help keep your pages lean. (Run `gulp` to create an optimised version of your project to `/dist`)                                                                                                |
| Code Linting               | JavaScript code linting is done using [ESLint](http://eslint.org) - a pluggable linter tool for identifying and reporting on patterns in JavaScript. Web Starter Kit uses ESLint with [eslint-config-google](https://github.com/google/eslint-config-google), which tries to follow the Google JavaScript style guide. Meanwhile, SASS is linted using [stylelint](https://github.com/stylelint/stylelint).                                                                                               |
| ES2015 via Babel 6.0                   | ES2015 support using [Babel](https://babeljs.io/). ES2015 source code and modules will be automatically transpiled to ES5 for wide browser support.  |
| PUG support                   | Write simplified, dynamic markup using the [Pug](https://pugjs.org) templating language. |
| SVG Sprites                   | Easily create and inline SVG sprites by dropping individual SVGs into the `app/images/_svg-sprite` directory. |
| Built-in HTTP Server                   | A built-in server for previewing your site locally while you develop and iterate                                                                                                                                                                            |
| Live Browser Reloading                 | Reload the browser in real-time anytime an edit is made without the need for an extension. (Run `gulp serve` and edit your files)                                                                                                                           |
| Cross-device Synchronization           | Synchronize clicks, scrolls, forms and live-reload across multiple devices as you edit your project. Powered by [BrowserSync](http://browsersync.io). (Run `gulp serve` and open up the IP provided on other devices on your network)                       |
| Offline support                     | Thanks to our baked in [Service Worker](http://www.html5rocks.com/en/tutorials/service-worker/introduction/) [pre-caching](https://github.com/bsd/static-starterkit/blob/master/gulpfile.babel.js#L226), sites deploying `dist` to a HTTPS domain will enjoy offline support. This is made possible by [sw-precache](https://github.com/GoogleChrome/sw-precache/).                                                                                                                                              |
| PageSpeed Insights                     | Web performance metrics showing how well your site performs on mobile and desktop (Run `gulp pagespeed`)                                                                                                                                                    |

## Quickstart

Clone this repository and `gulp serve` to spin up contents of the `app` directory. 

Be sure to look over the [installation docs](docs/install.md) to verify your environment is prepared to run this project locally.
Once you have verified that your system can run this repo, check out the [commands](docs/commands.md) available to get started.

## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

* Chrome
* Edge
* Firefox
* Safari
* Opera
* Internet Explorer 10+

This is not to say that Web Starter Kit cannot be used in browsers older than those reflected, but merely that our focus will be on ensuring our layouts work great in the above.

## Troubleshooting

If you find yourself running into issues during installation or running the tools, open an [issue](https://github.com/bsd/static-starterkit/issues).

## Docs and Recipes

* [File Appendix](https://github.com/bsd/static-starterkit/blob/master/docs/file-appendix.md) - What do the different files here do?
* [Deployment guides](https://github.com/bsd/static-starterkit/blob/master/docs/deploy.md) - available for Firebase, Google App Engine and other services.
* [Gulp recipes](https://github.com/gulpjs/gulp/tree/master/docs/recipes) - the official Gulp recipes directory includes a comprehensive list of guides for different workflows you can add to your project.
