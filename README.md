## Magento 2 French Language Pack

**Install French pack**:

``` php
composer require aveadev/magento-2-french-language-pack:dev-main
php bin/magento setup:static-content:deploy fr_FR
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
```
