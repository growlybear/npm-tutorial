npm-tutorial
============

[Tutorial for creating and publishing a new Node.js module](http://www.adaltas.com/blog/2013/07/04/tutorial-create-publish-new-nodejs-module/)

Test coverage for this tutorial uses [JSCoverage](http://siliconforks.com/jscoverage/),
which could likely benefit from integration with [Plato](https://github.com/es-analysis/plato).
Alternatives like [Istanbul](http://gotwarlost.github.io/istanbul/1) or
[blanket.js](http://blanketjs.org/) could certainly be considered. In particular, Blanket's
visualisation of [what percentage of included 3rd party libraries](https://github.com/alex-seville/blanket/blob/master/docs/compatibility_and_features.md#how-much-jquery-does-bootstrap-use)
your code consumes looks like it would be extremely useful in determining how and where to
optimise dependencies.
