# AngularGM

AngularGM is a set of directives for embedding Google Maps in your application using the Google Maps Javascript API.


## Documentation and examples

TODO


## Using

* Include the required libraries (cdn/local)

>
``` html
<script src="//maps.googleapis.com/maps/api/js?sensor=false"></script>
<script src="//ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
<script src="//ajax.googleapis.com/ajax/libs/angularjs/1.0.5/angular.min.js"></script>
angular-gm
```

* Declare a dependency on the `googleMaps` module

>
``` javascript
var app = angular.module('angularjs-starter', ['googleMaps']);
```

## Development

Clone the repo, `git clone git://github.com/dylanfprice/angular-gm.git`

AngularGM is tested with `karma`

>
	$ sudo npm install grunt-cli --global
	$ npm install --dev
	$ grunt karma:server

You can build the latest version using `grunt`.

>
	$ grunt build


## Author

**Dylan Price**

* http://github.com/dylanfprice

