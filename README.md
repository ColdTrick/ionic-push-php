# Ionic push php sdk

This package may be helpful for sending ionic push notifications

## Install

Via Composer

``` bash
$ composer require dmitrovskiy/ionic-push-php
```

## Usage

``` php
$pusher = new Dmitrovskiy\IonicPush\PushProcessor(
    'PROFILE',
    'AUTHORIZATION_TOKEN'
);

$devices = array(
    //...
);

$notification = array(
    //...
);

$pusher->notify($devices, $notification);
```

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
