# Transform Recline to Vega specifications

Simple library to transform recline graph specifications to vega graph specifcations.

See [Recline documentation](http://okfnlabs.org/recline/docs/tutorial-views.html) for more information about Recline graphs and it's specifications.

See [Vega documentation](https://github.com/vega/vega/wiki) for more information about Vega graphs abd it's specicifications


Example code for using library:
```
var transform = require('index');
var reclineSpec = {"graphType": "lines","group": "Date","series": ["Price"]};

var vegaSpec = transform(reclineSpec)
```
`Transform()` returns a simple JSON object that is ready for use to construct *Vega line graph* (in this example)


To ran tests:
```
$ mocha test
```
