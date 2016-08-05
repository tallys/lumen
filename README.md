Lumen
=====

https://tallys.github.io/lumen/sassdoc/

Lumen is a
practical color-theory toolkit
for people who code.

Based on the [website](http://tallys.github.io/color-theory/)
by [Natalya Shelburne](https://twitter.com/natalyathree).


Development
-----------

`npm install` to intall
the testing, linting, and documentation dependencies.

`gulp sasslint` to lint changes in the Sass.

`gulp test` to run the tests with True.


Documentation
-------------

Clone the repo into an (ignored) sub-folder
named `gh-pages`,
and then make sure that sub-repo is on the `gh-pages` branch:

```
git clone git@github.com:tallys/lumen.git gh-pages
cd gh-pages
git checkout gh-pages
cd ../
```

Run `gulp sassdoc` to re-generate the documentation
in the `gh-pages` folder.
Then commit the changes
and push to the gh-pages branch on github:

```
cd gh-pages
git add --all
git commit -m 'Update documentation'
g push
cd ../
```
