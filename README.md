[![Build Status](https://travis-ci.org/curtis-n/test-number-formatter.svg?branch=master)](https://travis-ci.org/curtis-n/test-number-formatter)

[![Coverage Status](https://coveralls.io/repos/github/curtis-n/test-number-formatter/badge.svg?branch=master)](https://coveralls.io/github/curtis-n/test-number-formatter?branch=master)

# test-number-formatter
Test from tutorial https://codeburst.io/how-to-create-and-publish-your-first-node-js-module-444e7585b738

Test Number Formatter
=========

A small library that adds commas to numbers

## Installation

  `npm install @jdaudier/number-formatter`

## Usage

    var numFormatter = require('@jdaudier/number-formatter');

    var formattedNum = numFormatter(35666);
  
  
  Output should be `35,666`
  
  


## Tests

  `npm test`

## Contributing

In lieu of a formal style guide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code.