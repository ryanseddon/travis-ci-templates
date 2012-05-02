Travis-ci templates
===================

### A collection (right now only node.js) of travis-ci templates to get you started in your own projects

The nodejs example is heavily skewed towards client-side testing, running qunit tests through phantomjs, but can easily be modified to run server side tests.

### Getting started

1. First you'll need to follow the [getting started guide](http://about.travis-ci.org/docs/user/getting-started/) to hook up your github repository with travis-ci.

2. Next copy the contents of the node folder into your repository, so in the root you should have the `.travis.yml` and 'test' folder.

3. Modify the `test/js/tests.js` to include your own tests for your project.

4. Commit and watch travis-ci run your test suite like magic.

Check out [Modernizr](https://github.com/Modernizr/Modernizr) which uses this exact template to run the test suite on commit.

### Contributing

If you want to add a template for another language to help people getting started I will love you forever. Just fork this repo create a folder with the language name and add the necessary files within that folder and then send a pull request.

Licensed under MIT.