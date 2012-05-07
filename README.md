NodeJS Merge 1.0.0
==================================================

What is this?
--------------------------------------

NodeJS Merge is used to merge multiple objects into one object.

Example
--------------------------------------

	var Merge = require('merge'),

		result = Merge({ one: 'hello' }, { two: 'world' });

	console.log(result); // {"one":"hello","two":"world"}