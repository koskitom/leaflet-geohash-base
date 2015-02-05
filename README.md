## Goal
![Goal map](https://raw.githubusercontent.com/rikukissa/leaflet-geohash-base/master/goal.png)

Our goal is to create a map with leaflet visualizing GeoHash data. This project contains a data file `src/js/data.js`, but you can also use data from somewhere else.

### Keywords
* Leaflet
* Leaflet-dvf (Leaflet data visualization framework)
* Geohash
* Dealing with flawed javascript libraries
* Modifying build steps to suit your needs

**Instructions for installing this environment below.**


# Project template for [gulp.js](http://gulpjs.com/)
<img width="114px" height="257px" align="right" src="https://raw.githubusercontent.com/gulpjs/artwork/master/gulp-2x.png"/>

### What it does
* Bundles all JavaScript with [browserify](http://browserify.org/)
* Minifies HTML and CSS
* Serves your static files to localhost:9001
* Reloads your browser with LiveReload when files change

## Getting things up and running
- Install [Node.js](http://nodejs.org)

```
 git clone git@github.com:koodiklinikka/gulp-project-template.git <your project name>
 cd <your project name>
 npm install
 npm start
 open http://localhost:9001 in your browser
```
### Enable LiveReload
Install [LiveReload for Chrome](https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei?hl=en)

## CLI Commands
* npm install
    * Installs server-side dependencies from NPM and client-side dependencies from Bower
* npm start
    * Compiles your files, starts watching files for changes, serves static files to port 9001
* npm test
    * Runs all tests
* npm run build
    * Builds everything

Minification, uglification and other tasks you're expected to run before deploying your product can be made by running the build command with env variable NODE_ENV set to "production"

    NODE_ENV=production npm run build

## Development guidelines
* **public** - directory should be dedicated only to compiled/copied files from **src** - directory.
  It should be possible to delete directory completely and after **npm start** or **npm run build** everything should be as they were before the deletion.
* All development dependencies should be installed with **npm**. Browser dependencies should be installed with **bower** or with **npm**.
