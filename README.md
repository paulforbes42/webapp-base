Have a working AngularJS application up and running in minutes.


## Technologies

* AngularJS
* Bootstrap
* Less
* Grunt

## AngularJS Best Practices

This project is intended to adhere to the best practices defined in the John Papa Style Guide.

https://github.com/johnpapa/angular-styleguide/blob/master/a1/README.md

## Setup Instructions
```
// Install the NodeJS dependencies
npm install

// Download the Client-side dependencies
bower install

// Run the build, start the server, watch file changes
grunt
```

Now, direct your browser to http://localhost:3000/

## Grunt targets

* `grunt`
* `grunt build`
* `grunt deploy`
* `grunt clean`
* `grunt test`
* `grunt ngdocs`

## Code Quality and Unit Tests

`grunt test`

* eslint
* jshint
* karma / jasmine

## Generating Views

To generate all the files for a new view, run the following command replacing `{viewName}` with the name of the page you would like to create.

`grunt yo:view:{viewName}`
