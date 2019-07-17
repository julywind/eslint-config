# Tdlist ESLint

For backend/node javascript

Extended from [Airbnb's base style guide](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb-base)

To use:

1. Install peer deps:

`npm install --save-dev eslint eslint-config-airbnb-base eslint-plugin-import`

2. Install package

if you have it locally, you can do:

`npm link [relative-path-to-folder]`

or

`npm install --save-dev tdlist/eslint-config-tdlist`

3. create an .eslintrc file

````yml
root: true
env:
  node: true
extends: tdlist
````
