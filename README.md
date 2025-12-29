# REST API Filters for Magento 2

Adds whitelist filtering to Magento REST API via `?fields=` parameter.

> **⚠️ DEPRECATED - This module is only for Magento 2.2.x**
>
> Magento 2.3+ has native `?fields=` filtering built-in via `Magento\Framework\Webapi\Rest\Response\FieldsFilter`.

## Version Compatibility

| Magento Version | PHP Version | Status |
|-----------------|-------------|--------|
| 2.3.x - 2.4.x | 7.2 - 8.3 | ❌ Incompatible |
| **2.2.x** | **7.0 - 7.2** | **✅ Compatible** |

## Installation

```bash
composer require springimport/magento2-module-restapi-filters:^1.0
php bin/magento module:enable SpringImport_RestApiFilters
php bin/magento setup:upgrade
```
