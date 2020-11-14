# abap-advent-2020-template
[Advent of Code](https://adventofcode.com) 2020 - ABAP Template

Let's do it the difficult way! By ABAP running on [NodeJS](https://nodejs.org)

## Prerequsites

NodeJS 12 installed

No ABAP system required

However, _a lot_ of patience is required to get the ABAP running in Node, this will involve debugging of javascript and typescript code!

## Initial Setup

After cloning this template repository, please rename all objects, this is done by changing the configuration in `abaplint.json` and then running `npm install && npm run rename`

Enable [abaplint.app](https://github.com/marketplace/abaplint) to get nice linter errors.

Adjust `abaplint.json` to match your preferences

## Commands

`npm install` to install dependencies, make sure to keep file `package.json` up to date with latest dependencies

`npm run lint` to run linter

`npm run downport` will downport the code to 702, into directory "downport"

`npm run unit` takes downported code, transpiles it, and runs unit tests

`npm test` does linting, downporting and unit testing in that sequence

`npm run input -- 01` to run day 01 with input from `/input/day01.txt`
