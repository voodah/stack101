# Stack101 JS Starter #
=======================
# Directory Structure:
```
├── app/          // Your code here !
├── assets/       // All your static stuff goes here !
│   ├── css         // CSS assets pre-compile, pre-minify
│   ├── img         // Imgs pre-minified
│   └── js          // JS pre-compiled, pre-uglify
├── bin/            // http server startup + scripts
├── data/         // For text dbs or the like, contents ignored by Git
├── gulp/         // Gulp stuff
│   ├── tasks/      // Gulp tasks
│   └── index.js    // Gulp entry point
├── lib/          // Reusable/3rd party libs
├── node_modules  // Ignored by git
├── public/       // Build dirs
│   ├── css         // Gulp output dir for compiled and minified CSS
│   ├── img         // Gulp output dir for minified Imgs
│   └── js          // Gulp output dir for compiled and uglified JS
├── routes/       // Routes/Controllers
│   ├── ctrls/      // Throw your routes/controllers here. One file per site func recommended.
│   └── index.js    // Routes entry point
├── src/          // Pre-compiled JS
├── tasks/        // Gulp tasks (one per file!)
├── test/         // Tests
├── views/        // Templates and views
├── README.md
├── LICENSE
├── app.js        // App entry point
├── gulpfiles.js  // Gulp entry point, tasks go in ./tasks/
├── package.json
├── .gitignore    // Don't forget to customize this
└── .travis.yml   // Don't forget to customize this
```

# Packages:

```
+ APP
  + express
  + express-session
+ TEMPLATES
  + ejs
+ SERVER / SEC
  + helmet
+ UTIL
  + lodash
  + moment
  + q
  + request
  + saffy
  + validator
+ DEV / PROD
  + browserify
  + browserify-shim
  + browser-sync
  + del
  + gulp
    + gulp-jshint
    + gulp-nodemon
    + gulp-plumber
    + gulp-sequence
    + gulp-watch
  + tiny-lr (liveReload)
+ TESTS
  + jshint
    + jshint-stylish
  + karma
  + mocha
  + chai
  + sinon (fake endpoints)
  + istanbul (test coverage)
  + travis (just the .travis.yml file)
```