# ng-daia [![Build Status](https://travis-ci.org/gbv/ng-daia.png?branch=master)](https://travis-ci.org/gbv/ng-daia)

> [AngularJS](http://angularjs.org/) module to facilitate access to DAIA services

## Usage and documentation
 
See <http://gbv.github.io/ng-daia/>.

## Requirements

AngularJS >= 1.2

## Development

First, **clone** the repository from <https://github.com/gbv/ng-daia>.

Second, install Node.js unless it is already installed. Node.js includes `npm`
to install additional packages. Locally **install all required packages**
listed in `package.json` (for global installation call `npm` via `sudo -H`):

    npm install -g grunt-cli
    npm install

Testing is configured in `karma.conf.js` and **unit tests** are located in
directory `test` written with [Jasmine](http://pivotal.github.io/jasmine/). 

To execute of all unit tests call:

    grunt test

For contious testing (tests are re-run on changes), call:

    grunt watch

As configured in `.travis.yml` the tests are automatically 
[executed at travis-ci](https://travis-ci.org/gbv/ng-daia)
when pushed to GitHub.

To build the **documentation**, written using
[ngdoc](https://github.com/angular/angular.js/wiki/Writing-AngularJS-Documentation),
call

    grunt docs

