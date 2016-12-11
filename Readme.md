# Assessment of Fair Housing for the State of GA - Code for Atlanta

## To Get Started:

* Fork this repo to your own repo.
* Clone your Fork down to your local machine.
* Run `npm install` to install all dependencies (see package.json), then `gulp start` to launch your local server and start developing with the included build tools.
* Once you've pushed code to your Fork, make a pull request to the master branch on the AFH-Atlanta/afh-front-end repo.

## Style guide

* Use ES6 JavaScript - (Use let, const, etc. instead of var).
* Make one JavaScript file for each view you work on, and import it and instantiate it into `main.js`. (i.e. break the code for each view into a module)
* Use Bootstrap and default Bootstrap styles for buttons, etc.
* Re-use the nav in `index.html` on each page, and place a class of `'active'` for the nav link that corresponds to the view you're working on.
* Use Semantic HTML
* Do a mobile-first design for each view you create, and be sure it is responsive from mobile thru desktop.
* Make one HTML document for each module in the survey. We are making a multi-page app (not a single page app).
* Use tabs, not spaces.
* RUN ```npm run lint``` in your terminal and fix all errors prior to making a pull request.

This project only uses jQuery and Lodash, because the idea is to keep the tech bar low for new people to get on the team. We want as many people to contribute as possible!


## Installation

#### Prerequisites

Make sure you have an up to date installation of `npm`
with `brew update` followed by either `brew install npm` or `brew upgrade npm`. (To do this, you will also need to install homebrew if you haven't already. [Install Homebrew here] (http://brew.sh/)) If you are not running Mac OS, you will need to update `npm` using whatever tool that corresponds to your Windows or other OS setup.

Then use npm to install the following apps with `npm install -g $APP_NAME`
* `gulp-cli`
* `surge`

Finally, I would strongly encourage you to install the `newapp` script from [here][newapp].

[newapp]: https://gist.github.com/kingcons/a25733c233faf10847cbb4ff557e6843

# Features

This template features a couple different tools. First it utilizes both NPM and Gulp for different tasks.

## Gulp Tasks

All tasks are listed below, but ideally you will just need to run `gulp start` and be done with it.

- `gulp start`: This is the primary task that will fire up the server and allow you to start building
- `gulp server`: This will start a Browsersync server with live-reload
- `gulp sass`: This will compile your SASS
- `gulp browserify`: This will transpile your JS from ES6 to ES5
- `gulp watch`: This will start a watcher for files

## NPM Scripts

- `npm run test`: This will launch Mocha in your terminal and run any tests
- `npm run deploy`: This will deploy your application to Surge.sh for you
- `npm run lint`: This will run ESLint on your `/src/js` folder
