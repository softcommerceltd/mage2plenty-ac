# Magento - PlentyMarkets integration
Metapackage of bundled modules.

## Requirements
* [Magento 2.4.0 - 2.4.3](https://magento.com/tech-resources/download).
* PHP 7.3.0 or later

## Installation

#### Install using composer
Add your private repository to the composer.json and setup authenticate to access the required packages.
Add using composer config command:

`composer config repositories.private-packagist composer https://softcommerce.repo.packagist.com/repository-name/`

Or manually edit the `composer.json` file.
Add the following custom repository to your project's composer.json:

```
{
    "repositories": [
        {"type": "composer", "url": "https://softcommerce.repo.packagist.com/repository-name/"}
    ]
}
```

#### Setup Authentication
Setup authentication in the following three ways:

1. Store the authentication credentials in your global Composer auth.json with the command below.

`composer config --global --auth http-basic.softcommerce.repo.packagist.com token you-access-token`

2. Store the authentication credentials using the environment variable:

`COMPOSER_AUTH='{"http-basic": {"softcommerce.repo.packagist.com": {"username": "token", "password": "you-access-token"}}}'`

3. Interactively during composer command. Composer will automatically prompt you to enter authentication credentials
   once you run a Composer command that tries to access Private Packagist if no authentication is configured.
   This will then store the credentials in your global Composer auth.json.

```
Authentication required (softcommerce.repo.packagist.com):
Username: your-order-number
Password: you-access-token
```

#### Install Extension Filesystem
Magento Open Source:

`composer require softcommerce/mage2plenty-os`

Adobe Commerce:

`composer require softcommerce/mage2plenty-ac`

To install extension compatible with specific Magento version, append appropriate version constraint.
For example:

`composer require softcommerce/mage2plenty-os ~1.1.0`

Referrer to [Magento Version Compatibility](https://devdocs-m2.mage2plenty.com/docs/getting-started/magento-version-compatibility/) for a list of compatible Magento versions.

#### Post Installation
In production mode:

```
bin/magento maintenance:enable
bin/magento setup:upgrade
bin/magento deploy:mode:set production
bin/magento maintenance:disable
```

In development mode:

```
php bin/magento setup:upgrade
php bin/magento setup:di:compile
```

## Thanks for dropping by
<p align="center">
    <a href="https://magento.com">
        <img src="https://softcommerce.co.uk/pub/media/banner/logo.svg" width="200" alt="Soft Commerce Ltd" />
    </a>
    <br />
    <a href="https://softcommerce.co.uk/">
        https://softcommerce.co.uk/
    </a>
</p>
