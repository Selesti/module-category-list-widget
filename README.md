[![Packagist](https://img.shields.io/packagist/v/magekey/module-category-list-widget.svg)](https://packagist.org/packages/magekey/module-category-list-widget) [![Packagist](https://img.shields.io/packagist/dt/magekey/module-category-list-widget.svg)](https://packagist.org/packages/magekey/module-category-list-widget)

# Magento 2 Category List Widget

![alt text](https://raw.githubusercontent.com/magekey/module-category-list-widget/master/docs/images/preview.png)

## Features:

- "Category List" widget.

## Installing the Extension

    composer require magekey/module-category-list-widget

## Deployment

    php bin/magento maintenance:enable                  #Enable maintenance mode
    php bin/magento setup:upgrade                       #Updates the Magento software
    php bin/magento setup:di:compile                    #Compile dependencies
    php bin/magento setup:static-content:deploy         #Deploys static view files
    php bin/magento cache:flush                         #Flush cache
    php bin/magento maintenance:disable                 #Disable maintenance mode

## Versions tested

> 2.2.5
