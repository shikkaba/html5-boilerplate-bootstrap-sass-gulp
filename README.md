# HTML5 Boilerplate Bootstrap SASS Gulp

### Requirements

$ # Install gulp globally
$ npm install -g gulp

### Start

$ Run `npm install` to install all dependencies

### Gulp API

Default task is `$ gulp`, which will run all the following commands. Or, you can use them individually as needed.

```
$ gulp copy-assets // copy bootstrap4 assets from node_module folder

$ gulp build:css // only processes Sass to CSS once

$ gulp sass:watch // run Sass watcher for updated files

$ gulp serve // starts browser-sync server

$ gulp build:dist // moves processed files from src/ to dist/
```

### BrowserSync Support
It's there. Simply run `$ gulp` from the CLI and you will get all the things you need to get started. Server, watcher, browserSync.
