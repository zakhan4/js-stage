# JS Stage

## Description
This is a basic project template for creating and publishing an npm package. 

## Referenced article
https://itnext.io/step-by-step-building-and-publishing-an-npm-typescript-package-44fe7164964c

## Published public npm package
https://www.npmjs.com/package/js-stage

## Signup for an npm user account
https://www.npmjs.com/signup

## Test before publishing
`npm install full-path-to-package-directory`

## Login to your npm account
`npm login`

## Create a new version of the package
`npm version patch`

## Publish package
`npm publish`

## Unpublish package (only works within 72 hours of the initial publish)
`npm unpublish js-stage -f`

## How to install
`npm install js-stage`

## How to use:
 * Add `import {Greeter} from 'js-stage';` to the top of the file
 * Calling `Greeter("zakhan")` returns `"Hello zakhan4"`
