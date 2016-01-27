boofw/weixin-emoji-php
=========================

微信消息中默认表情图片与对应字符相互替换

Installation
--------------

With composer :

``` json
{
    ...
    "require": {
        "boofw/weixin-emoji-php": "~1.0"
    }
}
```

or

```
composer require boofw/weixin-emoji-php:~1.0
```

Usage
------

将微信消息中的表情字符(如 `/::)`, `/::D` 等)替换为相应表情图片

```php
<?php

use Boofw\Weixin\Emoji\Emoji;

$content = Emoji::render($content);
```
