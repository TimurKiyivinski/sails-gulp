# sails-gulp

A [Sails](http://sailsjs.org) fork with gulp, jquery and sass integrated for future personal projects.
Remember to update your `.sailsrc` to reflect these changes.

# usage
Pull this repository and run `npm install`. After this, should you need a template `local.js`, it is available at `./node_modules/sails-generate-backend/templates/config/local.js`.

* `gulp` runs through all basic tasks.
* `gulp clean` removed all compiled JS and SASS.
* `gulp scripts` compiles all javascript files.
* `gulp watch` helps listen for changes.

Use `gulp lift` when developing to avoid having to restart Sails.

# .sailsrc

```
{
  "generators": {
    "modules": {}
  },
  "hooks": {
    "grunt": false
  }
}
```
