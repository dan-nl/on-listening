## on-listening
[![Dependency Status][david-dm-image]][david-dm-url] [![Dev Dependency Status][david-dm-dev-image]][david-dm-dev-url] [![NSP Status][nsp-image]][nsp-url]

on-listening handler for express

## setup
```bash
npm install dan-nl/on-listening
```

## use
see [express-http-skeleton][skeleton-url] for an example of use in an application context.

```javascript
var app = express();
var server = http.createServer( app );
var onListening = require( 'on-listening' );

server.on( 'listening', onListening );
```

## license
[MIT License][mit-license]

[david-dm-image]: https://david-dm.org/dan-nl/on-listening.svg
[david-dm-url]: https://david-dm.org/dan-nl/on-listening
[david-dm-dev-image]: https://david-dm.org/dan-nl/on-listening/dev-status.svg
[david-dm-dev-url]: https://david-dm.org/dan-nl/on-listening?type=dev
[mit-license]: https://raw.githubusercontent.com/dan-nl/on-listening/master/license.txt
[nsp-image]: https://nodesecurity.io/orgs/githubdan-nl/projects/15f6b404-65ed-4613-b946-82fbbe13a411/badge
[nsp-url]: https://nodesecurity.io/orgs/githubdan-nl/projects/15f6b404-65ed-4613-b946-82fbbe13a411
[skeleton-url]: https://github.com/dan-nl/express-http-skeleton/blob/master/bin/www
