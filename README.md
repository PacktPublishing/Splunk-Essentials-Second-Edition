## $5 Tech Unlocked 2021!
[Buy and download this product for only $5 on PacktPub.com](https://www.packtpub.com/)
-----
*The $5 campaign         runs from __December 15th 2020__ to __January 13th 2021.__*

# Splunk Essentials Second Edition

This repository contains code for the book, [Splunk Essentials Second Edition](https://www.packtpub.com/big-data-and-business-intelligence/splunk-essentials-second-edition?utm_source=GitHub&utm_medium=repository&utm_campaign=9781785889462), by Packt.

## Instructions and Navigations

All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, chapter02.

The code will look like the following:
```
var styles = (function () {
	var ret = {};

	Object.keys(ansiStyles).forEach(function (key) {
		ansiStyles[key].closeRe = new RegExp(escapeStringRegexp(ansiStyles[key].close), 'g');

		ret[key] = {
			get: function () {
				return build.call(this, this._styles.concat(key));
			}
		};
	});

	return ret;
})();
```
Code files are available only for chapters 1 and 7.

## References

* [Splunk Essentials](https://www.packtpub.com/big-data-and-business-intelligence/splunk-essentials?utm_source=GitHub&utm_medium=repository&utm_campaign=9781784398385)
* [Mastering Splunk](https://www.packtpub.com/big-data-and-business-intelligence/mastering-splunk?utm_source=GitHub&utm_medium=repository&utm_campaign=9781782173830)
* [Advanced Splunk](https://www.packtpub.com/big-data-and-business-intelligence/advanced-splunk?utm_source=GitHub&utm_medium=repository&utm_campaign=9781785884351)

### Suggestions and Feedbacks

[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) for any feedbacks or suggestions.

