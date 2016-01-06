# MochawesomePlusPlus
This is a fork of Mochawesome reporter for Mocha test runner with added functionality in order to produce more verbose test reports and display the expected result, the actual result and the differences between the two.

Installation of the module is fairly straight forward:
npm install mochawesomeplusplus


Usage remains the same as the Mocahwesome.

e.g. Programatically:

var Mocha = require('mocha');
// Instantiate a Mocha instance.

var mocha = new Mocha({
    ui: 'bdd',
    reporter: 'mochawesomeplusplus',
    reporterOptions: {
    reportDir: './',
    reportName: 'testResults_'
    },
    timeout: 60000
    });

or via Command line:
mocha test.js --reporter mochawesomeplusplus
