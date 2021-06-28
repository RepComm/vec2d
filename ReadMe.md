# vec2d
OOP Vector2 as extracted from repcomm/scenario2d

Split into a separate lib for the sake of supporting other projects in a way that reduced bloat.

## Using
To install with npm run<br>`npm install @repcomm/vec2d`<br><br>
This package comes with typescript definitions, and should work in both typescript and javascript.

## Example Usage
TODO

## Compiling
TS -> JS is done using babel.js<br>
You can check out [ts-esm-babel-template](https://github.com/RepComm/ts-esm-babel-template)<br>
Which shows esmodule + typescript w/ babel -> js output<br><br>

or [webpack-ts-template](https://github.com/RepComm/webpack-ts-template) <br>
Which shows esmodule + typescript w/ babel + npm package integration<br>
<br>

To build you'll want to clone the repo<br>
`git clone https://github.com/RepComm/vec2d.git`

Run `npm install` to get dependencies

Run `build.sh` (note: runs `npm run build`)
for compiling to javascript

----

For compiling ts defs you'll need [typescript](https://www.npmjs.com/package/typescript)<br>
Run `npm install -g typescript`

Run `build-types.sh`
