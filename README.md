# angular-es6-starter
Angular ES6 starter: Babel + Gulp + Browserify + SASS + live-server

> Faster builds for the lovers of ES6. No more TypeScript!

## SETTING UP

``` shell
$ npm install # init the package;
$ npm run serve # use this for live-reload mode;
$ npm run build # for single build;
$ npm run deploy # for uglify + SASS compressed outputs in the www folder
```

> Yes, you can customize the dist folder name!

Just edit the `gulpfile.js` in the project folder and find the `DIST_PATH` variable:

``` javascript
var DIST_PATH = './www'; // Default is www
```