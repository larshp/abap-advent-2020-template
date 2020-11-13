# abap-advent-2020-template
[Advent of Code](https://adventofcode.com) 2020 - ABAP Template

Lets do it the difficult way! In ABAP running on [NodeJS](https://nodejs.org)

## Prerequsites

NodeJS 12 installed

No ABAP system required, but a lot of patience is a prerequsite

## Initial Setup

After cloning this template repository, please rename all objects.

This is done by changing the configuration in `abaplint.json` and then running `npm install && npm run rename`

Enable [abaplint.app](https://github.com/marketplace/abaplint) to get nice linter errors.

Adjust `abaplint.json` to your liking

## Commands

`npm install` to install dependencies, make sure to keep file `package.json` up to date with latest dependencies

`npm run lint` to run linter

`npm run downport` will downport the code to 702, into directory "downport"

`npm run unit` takes downported code and runs unit tests, js code is output to folder "output"

`npm test` does linting, downporting and unit testing in that sequence

`./run 01` todo