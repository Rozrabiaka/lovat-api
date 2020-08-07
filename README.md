# Lovat_Api

## Description
Magento 2 REST API Lovat Api

## Установка плагина

Загрузите расширение в виде ZIP-файла из этого репозитория или установите наш модуль с [Composer](https://getcomposer.org/), используя следующую команду:

```composer require lovat/module-lovat:dev-master```

далее выполните следующие команды
```
bin/magento setup:upgrade OR php bin/magento setup:di:update
bin/magento setup:di:compile OR php bin/magento setup:di:compile
bin/magento cache:clean OR php bin/magento cache:clean
```

ИЛИ

```
php bin/magento setup:di:update
php bin/magento setup:di:compile
php bin/magento cache:clean
```