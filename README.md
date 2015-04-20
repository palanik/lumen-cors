Lumen-CORS
==========

[Cross-origin resource sharing](https://developer.mozilla.org/en-US/docs/Web/HTTP/Access_control_CORS) (CORS) Middleware for [Lumen micro-framework](http://lumen.laravel.com/).

[![Latest Stable Version](https://poser.pugx.org/palanik/lumen-cors/v/stable.svg)](https://packagist.org/packages/palanik/lumen-cors)
[![License](https://poser.pugx.org/palanik/lumen-cors/license.svg)](https://github.com/palanik/lumen-cors/blob/master/LICENSE)

## Installation & Usage ##

After you install lumen as per [lumen docs](http://lumen.laravel.com/docs/installation#install-lumen), install lumen-cors from `lumen` folder.

### Install with [Composer](https://packagist.org/packages/palanik/lumen-cors) ###
1. Run `composer require "palanik/lumen-cors:dev-master"` to install lumen-cors.
2. List the middleware class `palanik\lumen\Middleware\LumenCors` in the `$app->middleware()` call of your `bootstrap/app.php` file. 

More info. - http://lumen.laravel.com/docs/middleware#registering-middleware

### Manual Installation ###

1. Copy the file LumenCors.php into `app/Http/Middleware` directory.
2. List the middleware class `palanik\lumen\Middleware\LumenCors` in the `$app->middleware()` call of your `bootstrap/app.php` file. 

More info. - http://lumen.laravel.com/docs/middleware#registering-middleware

## License ##

[MIT](LICENSE)
