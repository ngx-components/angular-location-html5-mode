![angular-express-header](https://cloud.githubusercontent.com/assets/1859381/8266502/d94e93ce-1731-11e5-9b9d-9b9e58c5369f.png)

## Angular location HTML5 mode

[AngularJS Express](https://github.com/angular-express/angular-express) component to configure HTML5 mode in `$locationProvider`.

## Installation

To install the component:

```bash
$ ngx install angular-location-html5-mode
```

To install specific handlers, you can install multiple components:

```bash
$ ngx install angular-location-html5-mode
```

No clue what the `ngx` command line tool is? Learn more about [AngularJS Express](https://github.com/angular-express/angular-express).

## How to use

After installing the component:

- edit `_build/configure-html5-mode.js`

and import the component in your Angular application:

```javascript
// Angular main module
var ngModule = angular.module('app', []);

// Import component
import c from 'components/angular-location-html5-mode/_build/index';

// Instantiate component
c(ngModule, { baseUrl: 'components/angular-location-html5-mode' });
```

## Component options

- `baseUrl`: Base URL that component can use to construct links

## License

[MIT](LICENSE)

## Change log

### v0.1.0

- Initial version
