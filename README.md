#EduManage

## Getting Started
After cloning the repo take a look at the `gulpfile.js` and check out the tasks available:
* Run `npm install` and `bower install`
* `gulp` The default task will compile the LESS and JS into the `dist` directory and minify the output, and it will copy all vendor libraries from `bower_components` into the `vendor` directory
* `gulp dev` The dev task will serve up a local version of the template and will watch the LESS, JS, and HTML files for changes and reload the browser windo automatically

To update dependencies, run `bower update` and then run `gulp copy` to copy the updated dependencies into the `vendor` directory

## Copyright and License
Code released under the [MIT] license.