# JS Stage

## Description
This is a basic project template for creating and publishing an npm package. 

## Referenced Article
https://itnext.io/step-by-step-building-and-publishing-an-npm-typescript-package-44fe7164964c

## Published Public NPM Package
https://www.npmjs.com/package/js-stage

## Create a new version of the package
`npm version patch`

## Publish package
`npm publish`

## Unpublish Package (only works within 72 hours of the initial publish)
`npm unpublish js-stage -f`

## How to Install
`npm install js-stage`

## How to Use:
 * Add `import {Greeter} from 'js-stage';` to the top of the file
 * Calling `Greeter("zakhan")` returns `"Hello zakhan4"`
