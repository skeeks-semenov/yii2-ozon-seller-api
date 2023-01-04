Ozon seller api client
===================================

Info
------------
* https://docs.ozon.ru/api/seller/

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist skeeks/yii2-ozon-seller-api "*"
```

or add

```
"skeeks/yii2-ozon-seller-api": "*"
```

How to use
----------

```php
//App config
[
    'components'    =>
    [
    //....
        'ozoenSellerApi' =>
        [
            'class'                 => 'skeeks\yii2\ozonsellerapi\OzonSellerApiClient',
            'client_id'   => '688772',
            'api_key'   => '0793c579-09aa-4fe1-bd7f-98ddd779a162',
            'timeout'               => 12,
        ],
    //....
    ]
]

```

Examples
----------

### Адресные подсказки
```php
$response = \Yii::$app->ozoenSellerApi->;
print_r($response); //Array response data
```

___

> [![skeeks!](https://skeeks.com/img/logo/logo-no-title-80px.png)](https://skeeks.com)  
<i>SkeekS CMS (Yii2) — quickly, easily and effectively!</i>  
[skeeks.com](https://skeeks.com) | [cms.skeeks.com](https://cms.skeeks.com)
