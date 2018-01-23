# @sensebox/eslint-config-senseBox

Use this package for consistent linting and formatting throughout all senseBox projects.

## Usage

Install the following packages:

Yarn

    yarn add --tilde --dev @sensebox/eslint-config-sensebox eslint@4.16.0 eslint-config-prettier@2.9.0 eslint-plugin-prettier@2.5.0 prettier@1.10.2

NPM

    npm install --save-dev @sensebox/eslint-config-sensebox eslint@4.16.0 eslint-config-prettier@2.9.0 eslint-plugin-prettier@2.5.0 prettier@1.10.2

Add a `.eslintrc.js` to your project where you specify this package in the `extends` key

    module.exports = {
      extends: ['@sensebox/eslint-config-sensebox']
    };