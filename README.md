# psr3

php psr3的简单实现

## 安装

``` bash
composer require diggphp/psr3
```

## 用例

``` php
$logger = new \DiggPHP\Psr3\LocalLogger(__DIR__);
$logger->log($level, $message, $context);
$logger->log('alert', '这是一个警告');
```
