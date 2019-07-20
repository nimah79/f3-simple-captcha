# F3 Simple CAPTCHA
This is a CPATHCA plugin for the [PHP Fat-Free Framework](https://github.com/bcosca/fatfree).

## Installation
### Using [Composer](https://getcomposer.org)
    composer require nimah79/f3-simplecaptcha 

## Quick Start
```php
$captcha = new SimpleCaptcha();

// Change configuration
$captcha->session_var = 'SESSION.session_var';

$captcha->render();
```

## Demo
![https://raw.githubusercontent.com/nimah79/f3-simplecaptcha/master/demo.png](https://raw.githubusercontent.com/nimah79/f3-simplecaptcha/master/demo.png)

