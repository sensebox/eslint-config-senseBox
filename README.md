# @sensebox/eslint-config-senseBox

Use this package for consistent linting and formatting throughout all senseBox projects.

## Usage

Install the following packages:

Yarn

    yarn add --tilde --dev @sensebox/eslint-config-sensebox eslint@8.6.0

NPM

    npm install --save-dev @sensebox/eslint-config-sensebox eslint@8.6.0

Add a `.eslintrc.js` to your project where you specify this package in the `extends` key

    module.exports = {
      extends: ['@sensebox/eslint-config-sensebox']
    };

Add a `lint` script to your `package.json`

    {
      ...
      "scripts": {
        ...
        "lint": "eslint --fix \"{src,test,.scripts,whatever}/**/*.js\""
      }
    }

Run `yarn lint` or `npm run lint`
