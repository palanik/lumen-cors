# lumen-cors
CORS Middleware for Lumen 

Lumen-CORS
==========

[Cross-origin resource sharing](https://developer.mozilla.org/en-US/docs/Web/HTTP/Access_control_CORS) (CORS) Middleware for [Lumen micro-framework](http://lumen.laravel.com/).

[![Latest Stable Version](https://poser.pugx.org/palanik/lumen-cors/v/stable.svg)](https://packagist.org/packages/palanik/lumen-cors)
[![License](https://poser.pugx.org/palanik/lumen-cors/license.svg)](https://github.com/palanik/lumen-cors/blob/master/LICENSE)

## Usage ##

1. Copy the file LumenCors.php into `app/Http/Middleware` directory.
2. List the middleware class `App\Http\Middleware\LumenCors` in the `$app->middleware()` call of your `bootstrap/app.php` file. 

More info. - http://lumen.laravel.com/docs/middleware#registering-middleware

## License ##

[MIT](LICENSE)
