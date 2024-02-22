## Changelog

# Package: softcommerce/module-core

### Version 1.4.6
- **Fix**: TypeError returned at vendor/softcommerce/module-core/Model/Eav/GetEavAttributeOptionValueData.php:170. https://github.com/softcommerceltd/mage2plenty-os/issues/13: [#13]

### Version 1.4.5
- **Enhancement**: Compatibility with magento commerce staging [#6]

### version 1.4.4
- **Enhancement**: New method to build DB metadata for insert request. [#5]

### Version 1.4.3
- **Enhancement**: An option to retrieve attribute source options in \SoftCommerce\Core\Model\Eav\GetEavAttributeOptionValueData [#4]

### Version 1.4.2
- **Enhancement**: Improvements to data storage framework [#3]

### Version 1.4.1
- **Enhancement**: Add new methods to `\SoftCommerce\Core\Model\Catalog\MediaManagementInterface`

### Version 1.4.0
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7
- **Feature**: Improvements and new functionality [#2]

### Version 1.3.7
- **Enhancement**: Add a custom field heading for system configuration. [#1]

### Version 1.3.6
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1 #2

### Version 1.3.5
- **Feature**: Added new CLI to clean up the static view files from `pub/static` and `var/vew_processed` directories.
- **Compatibility**: Compatibility with Magento 2.4.6 [CE|EC|ECE].

### Version 1.3.4
- **Enhancement**: Added improvements and compatibility with php 8.[0.1] to `SoftCommerce\Core\Framework\DataStorageInterface`.

### Version 1.3.3
- **Enhancement**: Added json content renderer to UI listing columns component.

### Version 1.3.2
- **Enhancement**: Minor improvements to DataStorage functionality.

### Version 1.3.1
- **Enhancement**: Added an option to SKU storage to retrieve data by `entity_id`.

### Version 1.3.0
- **Enhancement**: Added an option to provide custom database columns in `SoftCommerce\Core\Model\Utils\SkuStorageInterface`
model that's used to retrieve product entity data in array format.

### Version 1.2.9
- **Fix**: Applied a fix to license compatibility.

### Version 1.2.8
- **Compatibility**: Compatibility with Magento [OS/AC] 2.4.5 and PHP 8

### Version 1.2.7
- **Enhancement**: Added option to store multidimensional data to `SoftCommerce\Core\Framework\DataStorageInterface::setData`.

### Version 1.2.6
- **Enhancement**: Improvements to `SkuStorage` functionality.

### Version 1.2.5
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.4
- **Compatibility**: Compatibility with Magento Extension Quality Program (EQP).

### Version 1.2.3
- **Fix**: JQMIGRATE: HTML tags must be properly nested and closed.

### Version 1.2.2
- **Enhancement**: Changes to PDT.

### Version 1.2.1
- **Enhancement**: [M2P-7] Add support for sequence entity ID generation to `\SoftCommerce\Core\Model\Utils\GetEntityMetadata`.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.3
- **Feature**: New module to handle Log services. [#3]
- **Compatibility**: Compatibility with Magento Open Source 2.3.5 - 2.4.3 [#2]
- **Enhancement**: Integration Tests [#1]

### Version 1.0.2
- **Feature**: Added new entity data storage for request and response queries.
- **Compatibility**: Compatibility with removed \Laminas\Log\Loger package.

### Version 1.0.1
- **Feature**: Added data storage including output filters to framework.

### Version 1.0.0
- **Feature**: [SCMC-1] New module to global functionality for dependant modules.

# Package: softcommerce/module-plenty-attribute

### Version 1.3.1
- **Enhancement** Implement queue message to handle data collection process upon completion of attribute export. [#4]

### Version 1.3.0
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7
- **Enhancement**: Improvements to attribute export [#3]
- **Fix**: Operator is not allowed in this criteria class [#2]

### Version 1.2.7
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 [#1]

### Version 1.2.6
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1

### Version 1.2.5
- **Compatibility**: Added compatibility PHP 8.[0,1] and Magento 2.4.6.

### Version 1.2.4
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.3
- **Compatibility**: Added compatibility with earlier magento versions: 2.4.0 - 2.4.3

### Version 1.2.2
- **Enhancement**: Added ability to collect client data using CLI.

### Version 1.2.1
- **Fix**: Changes to module.xml where dependence `SoftCommerce_PlentyCore` was replaced with `SoftCommerce_PlentyClient`.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.0
- **Feature**: [M2PA-1] New module to handle Plenty Attribute entity.

# Package: softcommerce/module-plenty-attribute-rest-api

### Version 1.2.5
- **Enhancement** Compatibility with PlentyAttribute module version 1.3.1

### Version 1.2.4
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7

### Version 1.2.3
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1 #2

### Version 1.2.2
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.1
- **Enhancement**: Minor changes to code style.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.0
- **Feature**: [M2PA-1] New module to handle Plenty Attribute REST API client.

# Package: softcommerce/module-plenty-category

### Version 1.2.8
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7

### Version 1.2.7
- **Enhancement**: Add an event observer `catalog_category_delete_after` to handle deleted categories [#1]

### Version 1.2.6
- **Enhancement**: Changed console command names for better reading.

### Version 1.2.5
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1 #2

### Version 1.2.4
- **Compatibility**: Added compatibility with `SoftCommerce_PlentyCategoryProfileStaging` module that covers extended functionality with Adobe Commerce EE and ECE.
- **Compatibility**: Compatibility with PHP 8.

### Version 1.2.3
- **Enhancement**: Added schedule and history modal view to category import / export queue list pages.
- **Enhancement**: Added timestamp history to collect process.

### Version 1.2.2
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.1
- **Enhancement**: Added ability to collect client data using CLI.
- **Enhancement**: Minor changes to code style.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.0
- **Feature**: [M2PCAT-1] New module to handle category entity.

# Package: softcommerce/module-plenty-category-profile

### Version 1.3.9
- **Enhancement**: General code improvements. 

### Version 1.3.8
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7

### Version 1.3.7
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 [#5]

### Version 1.3.6
- **Fix**: Fix category path for category import with profiles that have no category mapping defined. [#4]
- **Fix**: Add category URL Key to the import if one doesn't exist in the reqeust data. [#3]
- **Fix**: Add category name to the import if one doesn't exist in the request data. [#2]
- **Fix**: Retrieve a correct locale category name during data collection [#1]

### Version 1.3.5
- **Enhancement**: Changed console command names for better reading.

### Version 1.3.4
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1

### Version 1.3.3
- **Compatibility**: Added compatibility PHP 8.1.

### Version 1.3.2
- **Compatibility**: Added compatibility with `SoftCommerce_PlentyCategoryProfileStaging` module that covers extended functionality with Adobe Commerce EE and ECE.

### Version 1.3.1
- **Compatibility**: Compatibility with Magento [OS/AC] 2.4.5 and PHP 8

### Version 1.3.0
- **Fix**: Applied a fix to category attribute mapping, where required attributes, such as name, were added to mapping programmatically.
- **Enhancement**: Added schedule and history modal view to category import / export queue list pages.
- **Enhancement**: Added an option to collect and import categories from category import queue list page.
- **Enhancement**: Added timestamp history to collect process.

### Version 1.2.9
- **Enhancement**: Added schedule and history modal view to category import / export queue list pages.

### Version 1.2.8
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.7
- **Enhancement**: Added ability to collect client data using CLI.
- **Enhancement**: Minor changes to code style.

### Version 1.2.6
- **Fix**: Applied a fix to category export.

### Version 1.2.5
- **Enhancement**: Added profile input option parameter to profile console commands.

### Version 1.2.4
- **Fix**: Applied a fix to root category mapping for category path build: `\SoftCommerce\PlentyCategoryProfile\Model\CategoryTreeManagement::buildPath`

### Version 1.2.3
- **Enhancement**: Changes to PDT.

### Version 1.2.2
- **Enhancement**: Disable the DynamicRowsDragAndDrop component on the DynamicRows components.

### Version 1.2.1
- **Fix**: [M2P-9] Warning: class_implements(): Class SoftCommerce\PlentyCategoryProfile\UI\Component\Form\AttributeMapping does not exist and could not be loaded.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.1
- **Feature**: New module to handle Plenty Log services. [#3]
- **Compatibility**: Compatibility with Magento Open Source 2.3.5 - 2.4.3 [#2]
- **Enhancement**: Integration Tests [#1]

### Version 1.0.0
- **Feature**: [M2PCAT-1] New module to handle category profile entity.

# Package: softcommerce/module-plenty-category-profile-schedule

### Version 1.2.4
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1 #2

### Version 1.2.3
- **Enhancement**: Added timestamp history to collect process.

### Version 1.2.2
- **Enhancement**: Minor changes to code style.

### Version 1.2.1
- **Enhancement**: Allow collect client data when import scheduler is inactive.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.0
- **Feature**: [M2PCAT-1] New module to handle category profile schedule entity.

# Package: softcommerce/module-plenty-category-profile-staging

### Version 1.0.2
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7

### Version 1.0.1
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1 #2

### Version 1.0.0
- **Feature**: New module to handle Catalog Staging.

# Package: softcommerce/module-plenty-category-rest-api

### Version 1.2.3
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1 #2

### Version 1.2.2
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.1
- **Enhancement**: Minor changes to code style.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.0
- **Feature**: [M2PCAT-1] New module to handle category REST API requests.

# Package: softcommerce/module-plenty-client

### Version 1.3.1
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7

### Version 1.3.0
- **Enhancement**: New functionality to manage client tokens via CLI [#1]

### Version 1.2.9
- **Enhancement**: Changed console command names for better reading.

### Version 1.2.8
- **Enhancement**: Added new abstract controller for collect configuration data services.

### Version 1.2.7
- **Enhancement**: Added pagination to HTTP client data request.
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.5 and PHP 8

### Version 1.2.6
- **Fix**: Applied a fix to `Invalid Form Key. Please refresh the page.` during saving client connection configuration
in `SoftCommerce > PlentyMarkets > Manage Client Connection`
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.5 and PHP 8

### Version 1.2.5
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.4
- **Enhancement**: Introduce pagination for client data collect process.

### Version 1.2.3
- **Compatibility**: Added compatibility with earlier magento versions: 2.4.0 - 2.4.3
- **Enhancement**: Handle empty HTTP response.

### Version 1.2.2
- **Enhancement**: Added ability to collect client data using CLI.
- **Enhancement**: Minor changes to code style.

### Version 1.2.1
- **Compatibility**: JS Modal: IE9 break script loading and avoid execution on iframe [#5]

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.1.0
- **Feature**: New module to handle Plenty Log services. [#3]
- **Compatibility**: Compatibility with Magento Open Source 2.4.3 [#2]
- **Enhancement**: Integration Tests [#1]

### Version 1.0.1
- **Compatibility**: Compatibility with Magento Open Source 2.3.5 - 2.4.2 [#6]

### Version 1.0.0
- **Feature**: [M2PM2-96] New module to handle client entity.

# Package: softcommerce/module-plenty-client-rest-api

### Version 1.2.6
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1 #2

### Version 1.2.5
- **Enhancement**: Added pagination to HTTP client data request.
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.5 and PHP 8

### Version 1.2.4
- **Fix**: Applied a fix to URI document arguments to address the error: Could not download external invoice. [Order ###, Plenty Order: ###, Document ID: ### Reason: Response body is empty.]

### Version 1.2.3
- **Enhancement**: Minor changes to code style.

### Version 1.2.2
- **Fix**: Changes to module.xml where dependence `SoftCommerce_PlentyCore` was replaced with `SoftCommerce_PlentyClient`.

### Version 1.2.1
- **Fix**: Replace WebstoreInterface with WebStoreInterface implement interface in `\SoftCommerce\PlentyClientRestApi\Model\Uri\WebStore`

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.1.0
- **Feature**: New module to handle Plenty Log services. [#3]
- **Compatibility**: Compatibility with Magento Open Source 2.4.3 [#2]
- **Enhancement**: Integration Tests [#1]

### Version 1.0.1
- **Compatibility**: Compatibility with Magento Open Source 2.3.5 - 2.4.2 [#6]

### Version 1.0.0
- **Feature**: [M2PM2-97] New module to handle client REST API entity.

# Package: softcommerce/module-plenty-customer

### Version 1.2.9
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7

### Version 1.2.8
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1 #2

### Version 1.2.7
- **Feature**: Added new, custom address option types.

### Version 1.2.6
- **Compatibility**: Added compatibility PHP 8.[0,1].
- **Enhancement**: Moved profile services over to new module `SoftCommerce_CustomerProfile`.

### Version 1.2.5
- **Enhancement**: Added changes to message storage during customer import / export process to include processor ID in the message identity.

### Version 1.2.4
- **Feature**: Created new profile to manage customer import.
- **Enhancement**: Added new methods to `SoftCommerce\PlentyCustomer\Api\Data\AddressInterface`.

### Version 1.2.3
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.2
- **Enhancement**: Minor changes to code style.

### Version 1.2.1
- **Fix**: Changes to module.xml where dependence `SoftCommerce_PlentyCore` was replaced with `SoftCommerce_PlentyClient`.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.0
- **Improvement**: [M2PC-24] New module to handle customer entity.
- **Improvement**: [M2PC-20] Add customer title / gender to contact export.
- **Feature**: [M2PI-49] Introduce customer group pricing functionality.
- **Fix**: [M2PC-20] Add customer title to contact export. - reopened - fixed and closed.
- **Improvement**: Minor contextual improvements.
- **Feature**: [M2PC-20] Add customer title to contact export.
- **Fix**: [M2PC-19] Customer title not exporting.
- **Compatibility**: PSR-1 and PSR-2 compliance.
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]
- **Fix**: Remove unnecessary comma from select statement in `SoftCommerce\PlentyCustomer\Model\ResourceModel\Customer\Address\Collection::_initSelect`.
- **Feature**: Added address and relation entities to store and manage both customer and order address data.
- **Compatibility**: PSR-1 and PSR-2 compliance.
- **Compatibility**: Changes to composer.json
- **Feature**: Added client configuration sources.
- **Feature**: Added customer import
- **Feature**: Added customer export
- **Feature**: Created `CUSTOMER` module
- **Feature**: Added customer account entity.
- **Feature**: Added customer address entity.
- **Compatibility**: Added compatibility with mysql 8.

# Package: softcommerce/module-plenty-customer-client

### Version 1.2.5
- **Feature**: Added new functionality to collect, created and manage address option types.

### Version 1.2.4
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.5 and PHP 8

### Version 1.2.3
- **Fix**: Fix pagination for client data collect process.

### Version 1.2.2
- **Enhancement**: Introduce pagination for client data collect process.

### Version 1.2.1
- **Enhancement**: Minor changes to code style.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.1
- **Feature**: New module to handle Plenty Log services. [#3]
- **Compatibility**: Compatibility with Magento Open Source 2.3.5 - 2.4.3 [#2]
- **Enhancement**: Integration Tests [#1]

### Version 1.0.0
- **Feature**: [M2PC-25] New module to handle customer client entity.

# Package: softcommerce/module-plenty-customer-profile

### Version 1.0.11
- **Enhancement**: Add scoped config to SoftCommerce\PlentyCustomerProfile\Model\Config [#6]
- **Fix**: TypeError: SoftCommerce\PlentyOrderClient\Model\ShippingCountry::getStateByName(): Argument #1 ($stateName) must be of type string, null given [#5]

### Version 1.0.10
- **Fix**: Applied a fix to message output in `SoftCommerce\PlentyCustomerProfile\Observer\Backend\ProfileSaveAfterControllerAction::execute`

### Version 1.0.9
- **Fix**: Argument #1 ($websiteId) must be of type array|int, string given, called in SoftCommerce/PlentyCustomerProfile/.../Generator/Customer.php [#5]

### Version 1.0.8
- **Enhancement**: General code improvements.

### Version 1.0.7
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7

### Version 1.0.6
- **Enhancement**: Handle contacts that are not found during contact address relation export. [#4]

### Version 1.0.5
- **Fix**: Could not process order. [Order: ****, Reason: Invalid data for insert] [#3]
- **Fix**: Apply a fix to contact deletion process when entities are not found on the system. [#2]

### Version 1.0.4
- **Fix**: Wrong address email being sent to PM [#1]

### Version 1.0.3
- **Enhancement**: Converted protected methods to public to allow interception of `SoftCommerce\PlentyCustomerProfile\Model\CustomerExportService\Generator\Address` by other vendors.

### Version 1.0.2
- **Enhancement**: Added improvements to customer address export.
- **Feature**: Added new functionality to collect, created and manage address option types.

### Version 1.0.1
- **Enhancement**: Improved error logging for the address export.

### Version 1.0.0
- **Feature**: Created a new module to handle customer profile services.

# Package: softcommerce/module-plenty-customer-rest-api

### Version 1.2.5
- **Feature**: Added new functionality to collect, created and manage address option types.

### Version 1.2.4
- **Enhancement**: Added an option to collect address data as part of contact collect process.

### Version 1.2.3
- **Enhancement**: Added new REST API route to create new or edit existing customer address.

### Version 1.2.2
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.1
- **Enhancement**: Minor changes to code style.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.0
- **Feature**: [M2PC-26] New module to handle customer REST API requests.

# Package: softcommerce/module-plenty-item

### Version 1.4.4
- **Enhancement**: Compatibility with magento commerce staging [#8]
- **Fix**: Apply a fix to Item Export Queue listing, where product ID doesn't match the SKU [#7]

### Version 1.4.3
- **Enhancement**: Codebase improvements to \SoftCommerce\PlentyItem\Model\GetVariationIdBySku::executeMultiple [#6]

### Version 1.4.2
- **Enhancement**: Improvements to product export [#5]

### Version 1.4.1
- **Enhancement**: General code improvements.

### Version 1.4.0
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7
- **Feature**: New functionality and improvements to product export. [#4]

### Version 1.3.8
- **Enhancement**: Remove deleted constant PROCESSED_AT from SoftCommerce\PlentyItem\Model\ResourceModel\Item\Collection [#3]

### Version 1.3.7
- **Enhancement**: Changed console command names for better reading.

### Version 1.3.6
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1 #2

### Version 1.3.5
- **Fix**: Invalid parameter number: number of bound variables does not match number of tokens. [#2]

### Version 1.3.4
- **Fix**: Argument #1 ($parentId) must be of type int, null given, called in softcommerce/module-plenty-item/Model/Variation.php on line 894 [#1]

### Version 1.3.4
- **Enhancement**: Added new methods to `SoftCommerce\PlentyItem\Model\ResourceModel\Variation`.
- **Enhancement**: Added new class `SoftCommerce\PlentyItem\Model\GetMainItemIdByVariationId` to retrieve main item by variation ID.

### Version 1.3.3
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.5 and PHP 8

### Version 1.3.2
- **Fix**: Applied a fix to catalog URL rewrite, where URLs with category paths were not generated per store request.

### Version 1.3.1
- **Enhancement**: Added functionality to flush temporary media storage from admin UI.

### Version 1.3.0
- **Enhancement**: Added schedule and history modal view to item import / export queue list pages.

### Version 1.2.9
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.8
- **Fix**: Fix item export, where products have no category assignment that leads to error during export process.

### Version 1.2.7
- **Enhancement**: Handle empty HTTP response.

### Version 1.2.6
- **Fix**: TypeError: current() expects parameter 1 to be array, null given in vendor/softcommerce/module-plenty-item/Model/GetVariationIdBySku.php:139

### Version 1.2.5
- **Enhancement**: Minor changes to code style.

### Version 1.2.4
- **Enhancement**: Added item export queue management.

### Version 1.2.3
- **Enhancement**: Remove old product eav attribute: `plenty_item_variation_id`.

### Version 1.2.2
- **Feature**: Added Compatibility with add-on module: `SoftCommerce_PlentyScommerceCanonical`.

### Version 1.2.1
- **Compatibility**: [M2P-8] Compatibility with Magento Adobe Commerce: Catalog Staging

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.2
- **Enhancement**: Remove old plenty_item_entity data.
- **Feature**: New module to handle Plenty Log services. [#3]
- **Compatibility**: Compatibility with Magento Open Source 2.3.5 - 2.4.3 [#2]
- **Enhancement**: Integration Tests [#1]

### Version 1.0.1
- **Feature**: [M2PM2-101] New module to handle Plenty Log services.
- **Fix**: [M2PI-79] Roll back image update as md5_file() is causing SSL connection reset by peer. Relay on PM image data instead.
- **Fix**: [M2PI-79] Fix image upload for images that are replaced with the same name and different image content.
- **Fix**: Added a fix to category path assigment during product import.
- **Fix**: Added a fix to product import URL 301 redirect.
- **Improvement**: Improvements to REST API category response data builder.
- **Improvement**: Implementation of default category import.
- **Fix**: [M2PI-78] Allow import of empty property values as well as properties with zero values.
- **Improvement**: [M2PI-77] Make images available per variation.
- **Fix**: [M2PI-76] Notice: Array to string conversion in vendor/plenty/module-item/Profile/Import/Service/Product/Generator/Attribute.php on line 128.
- **Fix**: [M2PI-75] Target category "default/example-path" is not within store root category. [SKU: ***, Variation: ***]
- **Improvement**: Improvements to multi-store / multi client import.
- **Feature**: [M2PI-74] Product video import feature.
- **Fix**: [M2PI-73] Group pricing issue with class assignment
- **Fix**: [M2PI-71] Category is not assigned to products with multiple root categories during import.
- **Improvement**: Improvements to multi-store / multi client import.
- **Improvement**: [M2PI-69] Image names, labels, and alternative tags are not imported.
- **Improvement**: [M2PI-56] Implement REST API response and request data builder.
- **Improvement**: [M2PI-54] Implement client configuration repository to include interface for each configuration.
- **Feature**: [M2PI-49] Introduce customer group pricing functionality.
- **Fix**: [M2PI-55] Category REST API using PIM does not return requested IDs specified by search criteria.
- **Improvement**: [M2PI-66] Allow property export for configurable associated products.
- **Fix**: [M2PI-65] Configurable attribute mapping not working.
- **Improvement**: Product export pre-improvement compatibility stage.
- **Fix**: [M2PI-63] SQLSTATE[23000]: Integrity constraint violation: 1452 Cannot add or update a child row: a foreign key constraint fails (plenty_variation_stock).
- **Compatibility**: Magento 2.4.3 compatibility and general code improvement.
- **Compatibility**: [M2PI-61] Properties V2 compatibility adjustments for product export.
- **Improvement**: [M2PM2-95] Create DateTime method for current locale.
- **Compatibility**: [M2PI-60] Properties V2 compatibility adjustments for product import.
- **Fix**: [M2PI-59] Fix API search criteria filter for enquiries performed by profile scheduler.
- **Feature**: [M2PI-49] Introduce customer group pricing functionality.
- **Fix**: [M2PM2-88] Integration tests failure.
- **Fix**: [M2PI-53] Product category links are deleted in Magento after import. -- Could not reproduce.
- **Improvement**: Minor contextual improvements.
- **Compatibility**: [M2PS-12] Stock reservation compatibility for Magento 2.3.5 and earlier.

### Version 1.0.0
- **Fix**: [M2PI-18] Fix to product import / export split button actions within catalog product view.
- **Feature**: [M2PI-17] Implement client configuration interface and repository.
- **Feature**: [M2PI-16] Create public interface to retrieve variation ID by product SKU.
- **Feature**: [M2PI-15] Create public interface to retrieve product SKU by variation ID.
- **Compatibility**: PSR-1 and PSR-2 compliance and general code cleanup.
- **Improvement**: [M2PI-44] An option to import products without the need of data collection.
- **Improvement**: [M2PI-36] Collect properties as part of variation collection process.
- **Improvement**: [M2PI-14] Disable API search criteria filters for inactive entities (e.g., media, stock, price).
- **Fix**: [M2PI-37] Assign attribute set to simple associated products during configurable product import / export.
- **Feature**: [M2PI-13] Convert bundle to simple product.
- **Fix**: [M2PI-24] Fix attribute restriction for product import.
- **Fix**: [M2PI-28] Required attribute "price" is missing for configurable attribute.
- **Improvement**: Removed default category fallback assignment to product import when category import is inactive.
- **Improvement**: Improvements to product stock import.
- **Improvement**: Added an option to enable/disable category import during product import.
- **Improvement**: Added an option to enable/disable stock import during product import.
- **Improvement**: Added an option to enable/disable media import during product import.
- **Improvement**: Added an option to enable/disable website relation import during product import.
- **Fix**: Fixed Json.parse error which failed to parse data within product export chooser grid due to data having accents and double quotes.
- **Fix**: Fixed product composite name within product import since composite name options were duplicated on each import.
- **Fix**: [M2PI-50] Fix property group assignment during product export.
- **Improvement**: [M2PI-43] Introduce attribute set prediction for product import.
- **Improvement**: Updates to profile entity.
- **Improvement**: [M2PM2-46] Order Import ::: Cancel order
- **Improvement**: [M2PM2-47 Order export]::: Discount amount tax calculation
- **Improvement**: [M2PI-42] Implement validation for product import with items that have required attribute values.
- **Improvement**: [M2PI-30] Implement MSI for product import.
- **Fix**: [M2PI-12] Crossells not importing.
- **Improvement**: Removed default stock assignment during product import.
- **Compatibility**: PSR-1 and PSR-2 compliance.
- **Feature**: [M2PI-33] Implement warehouse import / export.
- **Feature**: [M2PI-31] Add Shipping Profile to product export/import.
- **Compatibility**: Changes to composer.json
- **Feature**: [M2PM2-38] Order Export ::: Create shipment document
- **Fix**: [M2PI-41] Flush attribute data not working within product import / export profiles.
- **Feature**: [M2PI-32] Add image support for variation entities.
- **Fix**: Added a fix to database schema setup, where foreign keys failed to remove from tables which were subject to deletion.
- **Fix**: Added a fix to configurable product import where associated item import failed due to being created after initial import.
- **Fix**: Added a fix to property selection values where values with "0" content where not exported due to bing considered as false value ("0"). 
- **Feature**: Added media image filter for product import. Filter includes client store, referrers and listing.
- **Feature**: Added product relation links, such as: `Cross Sells`, `Up Sells` and `Related items`;
- **Feature**: [M2PI-40] Collect items after initial profile installation.
- **Feature**: Added an option to specify weight fallback for products that have weight values missing and that are required for product import.
- **Improvement**: Added an option to accept attribute set IDs during product import.
- **Improvement**: Added an option to generate URL based on PM text fields as well as a combination of attributes.
- **Improvement**: Added an option to use SKU as url suffix in case of URL duplicates.
- **Compatibility**: Added compatibility for Magento Commerce.
- **Fix**: [M2PI-46] Download item / variation images during data collection.
- **Fix**: [M2PI-39] Collect Items ::: QLSTATE[23000]: Integrity constraint violation: 1452 Cannot add or update a child row: a foreign key constraint fails (`xxx`.`plenty_item_import_item_variation`, CONSTRAINT `FK_5C04937B1E12EC4...
- **Fix**: [M2PI-38] All products fail if one fails within import schedule.

### Version 0.1.0
- **Fix**: Added a fix to product property export of attribute_set attribute.
- **Improvement**: Added history management for improved process tracking.
- **Improvement**: Added queue processor.
- **Improvement**: Added md5 check sum for import of images as an alternative solution since PM does not always provide this data.
- **Fix**: Added a fix to property mapping during product export.
- **Fix**: Added a fix to property mapping during product import.
- **Feature**: Added a link between variation and warehouse to item export.
- **Feature**: Added Multi stock inventory support.
- **Feature**: Added a warehouse to stock source mapping.
- **Feature**: Added ability to manually collect PlentyMarket's configuration data.
- **Fix**: Added a fix to item data collection dates.
- **Fix**: Added a fix to product export collection search criteria page filter.
- **Improvement**: Added ability to import / export images for simple associated products.
- **Improvement**: Simple associated images can now be assigned to product variation values to work as swatches on front-end.
- **Improvement**: Added Multi Source Inventory
- **Improvement**: Added improved product import.
- **Improvement**: Added improved output messages to product import. It's now easier to trace errors for failed import items.
- **Fix**: Added a fix for simple associated product name during product import. Simple associated product's name now consists of title + configurable option attribute values in order to make those unique.
- **Fix**: Added a fix for product image label during product export. Empty label values returned errors by PlentyMarkets. A workaround is to use product name if image alt tag is absent.
- **Improvement**: Added functionality to download image to media import directory during item data collection. This fixes native magento product import, where image upload occasionally fails with the following message: `"Imported resource (image) could not be downloaded from external resource due to timeout or access permissions."`
- **Fix**: Added a fix to allow import of products with empty attribute values that are required by the system.
- **Fix**: Added a fix to attribute value provider `SoftCommerce\PlentyItem\Model\ResourceModel\Import\Attribute::getAttributeByCode()`, where `attribute_id` should have been used instead of `entity_id` to retrieve values.
- **Improvement**: Add attribute value table entity. Values used to be stored inside attribute table as serialized value. This may cause issues with table size in future, when attribute values gradually build up.
- **Fix**: Added a fix to attribute creation method, where new attribute entity failed registration process.
- **Fix**: Apply an alternative means of retrieving array key in favour of array_key_first.
- **Fix**: Added a fix to property group assignment.
- **Feature**: Added ability to export property type `price` (float).
- **Fix**: Added a fix to `product image export` by employing md5_checksum to all images saved outside of PM connector (that is by 3rd party extensions or within Magento admin).  
- **Improvement**: Added `weight conversion` to product import / export.
- **Fix**: Added a fix to `product price export`. A website ID is added to price mapping.
- **Improvement**: Added `md5_checksum` column to `catalog_product_entity_media_gallery` in order to sign existing images and fix duplicate image issue during product import.
- **Feature**: Added ability to import and export products via Command Line Interface (CLI);
- **Fix**: Added a fix to `Plenty\Core\Model\PropertyManagement::collectPropertyRelationsAfter()`. Product property relation value failed to update during collection process.
- **Feature**: Added root `category` mapping. This enables to map root categories between the two systems.
- **Feature**: Added `category export` during product export process.
- **Feature**: Added `product export` via command line.
- **Feature**: Added ability to add property group options to support attribute set and its groups.
- **Feature**: Added `category` import.
- **Feature**: Added product `attribute value` import.
- **Feature**: Added `manufacturer` export.
- **Feature**: Added new `property export / import` that supports attributes defined for all product types including simple associated product and their store scope.
- **Feature**: Created item module

# Package: softcommerce/module-plenty-item-client

### Version 1.2.7
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7

### Version 1.2.6
- **Enhancement**: Changed console command names for better reading.

### Version 1.2.5
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1 #2

### Version 1.2.4
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.5 and PHP 8

### Version 1.2.3
- **Fix**: Fix pagination for client data collect process.

### Version 1.2.2
- **Enhancement**: Introduce pagination for client data collect process.

### Version 1.2.1
- **Enhancement**: Minor changes to code style.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.1
- **Feature**: New module to handle Plenty Log services. [#3]
- **Compatibility**: Compatibility with Magento Open Source 2.3.5 - 2.4.3 [#2]
- **Enhancement**: Integration Tests [#1]

### Version 1.0.0
- **Feature**: [M2PO-55] New module to handle item client entity.

# Package: softcommerce/module-plenty-item-profile

### Version 1.6.8
- **Enhancement**: Compatibility with new stock functionality. https://github.com/softcommerceltd/mage2plenty-os: [#12]

### Version 1.6.7
- **Enhancement**: Compatibility with magento commerce staging [#25]

### Version 1.6.6
- **Feature**: Introduce onetime schedule to collect items at specified times as part of cron job process [#24]

### Version 1.6.5
- **Enhancement**: Add price rounding option for product import [#23]

### Version 1.6.4
- **Feature**: Add attribute restriction to product import functionality [#22]

### Version 1.6.3
- **Fix**: Argument #1 ($sku) must be of type string, int given, called in .../Pim.php on line 183 [#21]
- **Enhancement**: Improvements to product export [#20]

### Version 1.6.2
- **Enhancement**: Improvements to item export. [#19]
- **Enhancement**: Implement queue message to handle data collection process upon completion of product export [#18]
- **Fix**: Item image names are not updating in PM [#17]

### Version 1.6.1
- **Feature**: Added image export functionality. [#16]

### Version 1.6.0
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7
- **Feature**: New functionality and improvements to product export [#15]

### Version 1.5.11
- **Fix**: Validation error found: attribute values do not match the other variations [#13]
- **Fix**: Validation error found: The variation categories field is required [#12]
- **Fix**: Argument #1 ($filePath) must be of type string, null given in SoftCommerce\PlentyItemProfile\Model\Utils\FileImageManagement::getImageMd5Checksum() [#10]

### Version 1.5.10
- **Fix**: SoftCommerce\PlentyItemProfile\Model\Utils\MediaManagement::getLastMediaPosition(): Argument #1 ($productId) must be of type int, null given [#9]

### Version 1.5.9
- **Enhancement**: Video won't import since property not found due to code having whitespaces. [#8]

### Version 1.5.8
- **Compatibility**: Added compatibility PHP 8.2.0 and Magento 2.4.6-p1

### Version 1.5.7
- **Compatibility**: Added compatibility PHP 8.[0,1].
- **Feature**: Added CLI functionality to map item and variation IDs to products.
- **Fix**: Argument #1 ($targetId) must be of type int, null given, called in vendor/softcommerce/module-plenty-item-profile/Model/ItemImportService/Generator/Property.php on line 99 #7
- **Fix**: Argument #2 ($string) must be of type string, array given in vendor/softcommerce/module-plenty-item-profile/Model/ItemImportService/Generator/MediaVideo.php #6

### Version 1.5.6
- **Feature**: [#5] Added support for external product video import.
- **Fix**: [#2 reopened] Applied a fix to product price import.

### Version 1.5.5
- **Fix**: [#1] Applied a fix to product import `yes/no` attribute where value `0` couldn't be imported due to incorrect validation.

### Version 1.5.4
- **Enhancement**: [#4] Added support for product type ID conversion from bundle to simple if bundle import is disabled.

### Version 1.5.3
- **Enhancement**: [#3] Added support for default attribute values for items that are not assigned to the default client/website scope.

### Version 1.5.2
- **Enhancement**: Added support for static attribute import.

### Version 1.5.1
- **Fix**: Applied a fix to product websites during import where products failed to be assigned to websites on initial import phase.

### Version 1.5.0
- **Fix**: [Reopened] Applied a fix to import of attribute values that are based on multi-store / multi-lang relations,
  where identical values from default scope were used in other stores, resulting in values having "Use Default Value" box unticked.

### Version 1.4.9
- **Enhancement**: Changes to attribute set ID generation during product import,
where attribute set ID is pulled from existing product if one exists,
alternatively the attribute set ID is retrieved from attribute set mapping.
- **Fix**: Applied a fix to import of attribute values that are based on multi-store / multi-lang relations,
where identical values from default scope were used in other stores, resulting in values having "Use Default Value" box unticked.
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.5 and PHP 8

### Version 1.4.8
- **Fix**: Applied a fix to tier price import.

### Version 1.4.7
- **Fix**: Reopened: Applied a fix to catalog URL rewrite, where URLs with category paths were not generated per store request.

### Version 1.4.6
- **Fix**: Applied a fix to catalog URL rewrite, where URLs with category paths were not generated per store request.

### Version 1.4.5
- **Enhancement**: Added an option to filter product import by flag value that can be used to exclude items from import.

### Version 1.4.4
- **Feature**: Added functionality to import catalog product links (related, cross-sells and upsells);

### Version 1.4.3
- **Enhancement**: Added an option to delete deference of product attribute values.
- **Enhancement**: Improvements to item content import, where attributes with the same values are left unchecked throughout store scopes.

### Version 1.4.2
- **Enhancement**: Improvements to item messages, where attributes with longtext values are truncated to save DB resources.
- **Enhancement**: Improvements to indexing, where indexing is now processed during batch process rather than at the end of execution.

### Version 1.4.1
- **Enhancement**: Improvements to `SkuStorage` functionality.
- **Enhancement**: Added an option to allow / disallow deleting the difference of assigned categories during product import.
- **Enhancement**: Added an option to allow / disallow deleting the difference of product relation assignment (cross-sells) during product import.

### Version 1.4.0
- **Enhancement**: Added an option to add item ID to image filenames to address issue for items with duplicate image names.
- **Enhancement**: Added functionality to flush temporary media storage filesystem on profile save event.

### Version 1.3.9
- **Enhancement**: Added schedule and history modal view to item import / export queue list pages.
- **Enhancement**: Added timestamp history to collect process.
- **Enhancement**: Implemented initial collect timestamp to allow collect data since specified datetime on initial data collect process.
- **Fix**: Removed `collected_at` timestamp from item export save request data to avoid conflict with item collect process.
- **Enhancement**: Added an option to collect and import items from item import queue list page.
- **Enhancement**: Added an option to collect and export items from item export queue list page.

### Version 1.3.8
- **Fix**: Applied a fix to tire price deletion, where absence of tier prices in PM triggers price removal in Magento.
- **Enhancement**: Improvements to ACL rules.
- **Enhancement**: Allow absence of price for parent bundle product during import validation process.
- **Enhancement**: Added a fix to tier price export, where existing tier prices were removed due to absent tier price in Plenty.
- **Enhancement**: Added timestamp history to collect process.

### Version 1.3.7
- **Enhancement**: Added an option to import all item images that are not assigned to variation(s).
- **Fix**: Fix product import, where property type decimal failed to import due to mapping error.

### Version 1.3.6
- **Enhancement**: Added weight attribute mapping to allow map weight to custom attributes.

### Version 1.3.5
- **Fix**: Fix attribute set ID assignment during product import.

### Version 1.3.4
- **Enhancement**: Implement item / variation PIM collect service scrolled by cursor in order to overcome item / variation result limit.

### Version 1.3.3
- **Fix**: Fix item content export.

### Version 1.3.2
- **Enhancement**: An option to allow / disallow deleting the difference of images between the two systems.

### Version 1.3.1
- **Enhancement**: Allow absence of price for parent variations.
- **Enhancement**: Handle empty HTTP response.

### Version 1.3.0
- **Fix**: [M2PI-82] Fix tier price default quantity.
- **Enhancement**: Added ability to collect client data using CLI.
- **Enhancement**: Minor changes to code style.

### Version 1.2.9
- **Feature**: Ability to add products to export queue using CLI.

### Version 1.2.8
- **Enhancement**: Add categories to export queue during product export.
- **Enhancement**: Remove old product eav attribute: `plenty_item_variation_id`.
- **Fix**: Product export: cast product weight attribute value to integer as PM does not accept float type.

### Version 1.2.7
- **Fix**: Applied a fix to property `attribute_set_id` upon creation.

### Version 1.2.6
- **Enhancement**: Changes to PDT.

### Version 1.2.5
- **Fix**: Added a fix to former property type `attribute_set_code`, where property name was changed to `attribute_set_id`. Issue resulted in wrong product attribute set group.
- **Enhancement**: Added additional `timestamp filters` to item collect in order to fetch updated item / variation and its relational data.
- **Enhancement**: Added detailed information to collection response message that includes applied filters to search criteria.
- **Enhancement**: Use main variation name if one does not exist for associated variation.

### Version 1.2.4
- **Enhancement**: Disable the DynamicRowsDragAndDrop component on the DynamicRows components.
- **Fix**: Applied a fix to directory spelling and all of its Classes in `\SoftCommerce\PlentyProfile\Ui\*`
- **Fix**: Notice: Undefined index: code in `softcommerce/module-plenty-item-profile/Model/ItemImportService/Generator/Barcode.php` on line 54.
- **Fix**: Applied a fix to price mapping configuration.

### Version 1.2.3
- **Compatibility**: [M2P-8] Reopened: Compatibility with Magento Adobe Commerce: Catalog Staging

### Version 1.2.2
- **Compatibility**: [M2P-8] Compatibility with Magento Adobe Commerce: Catalog Staging

### Version 1.2.1
- **Compatibility**: [M2P-6] Error: Argument 2 passed to \SoftCommerce\PlentyItemProfile\Model\ItemImportService\Generator\TierPrice::generateRequest()

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.1.0
- **Feature**: New module to handle Plenty Log services. [#3]
- **Compatibility**: Compatibility with Magento Open Source 2.4.3 [#2]
- **Enhancement**: Integration Tests [#1]

### Version 1.0.3
- **Fix**: [M2P-3] Error: Notice: Undefined index: epid in SoftCommerce/PlentyItemProfile/Model/ItemImportService/Generator/MarketIdentNumber.php on line 100.

### Version 1.0.2
- **Compatibility**: [M2P-2] Compatibility with Magento Open Source 2.3.5 - 2.4.2

### Version 1.0.1
- **Fix**: [M2PI-81] Error: Required attributes are missing. [name]. [Item: ###, Variation: ###, SKU: Test Product SKU ###]

### Version 1.0.0
- **Feature**: [M2P-1] New module to handle Plenty Log services.

# Package: softcommerce/module-plenty-item-profile-schedule

### Version 1.2.11
- **Feature**: Introduce onetime schedule to collect items at specified times as part of cron job process [#2]

### Version 1.2.10
- **Enhancement**: General code improvements.

### Version 1.2.9
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7

### Version 1.2.8
- **Fix**: Remove date filter from property REST API request route as it doesn't seem to work well.

### Version 1.2.7
- **Fix**: Applied a fix for item collect process to reduce the number of IDs proved for search criteria due to the following error:
`414 Request-URI Too Large /rest/pim/variations` [#1]

### Version 1.2.6
- **Compatibility**: Compatibility with Magento [OS/AC] 2.4.5 and PHP 8

### Version 1.2.5
- **Enhancement**: Added timestamp history to collect process.

### Version 1.2.4
- **Enhancement**: Implement item / variation PIM collect service scrolled by cursor in order to overcome item / variation result limit.

### Version 1.2.3
- **Enhancement**: Minor changes to code style.

### Version 1.2.2
- **Enhancement**: Allow collect client data when import scheduler is inactive.

### Version 1.2.1
- **Enhancement**: Added additional `timestamp filters` to item collect in order to fetch updated item / variation and its relational data.
- **Enhancement**: Added detailed information to collection response message that includes applied filters to search criteria.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.1
- **Usability**: [M2PI-80] Collect data using combination of PIM and standard item / variation collect API routes.

### Version 1.0.0
- **Feature**: [M2PO-57] New module to handle item profile schedule entity.

# Package: softcommerce/module-plenty-item-profile-staging

### Version 1.0.3
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1 #2

### Version 1.0.2
- **Compatibility**: Compatibility with Magento [OS/AC] 2.4.5 and PHP 8

### Version 1.0.1
- **Enhancement**: Minor changes to code style.

### Version 1.0.0
- **Feature**: New module to handle Catalog Staging.

# Package: softcommerce/module-plenty-item-rest-api

### Version 1.2.11
- **Enhancement**: General code improvements.

### Version 1.2.10
- **Enhancement**: Added new API Routes to item image. 

### Version 1.2.9
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7

### Version 1.2.8
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1 #2

### Version 1.2.7
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.6
- **Enhancement**: Implement item / variation PIM collect service scrolled by cursor in order to overcome item / variation result limit.

### Version 1.2.5
- **Fix**: Fix item content export.

### Version 1.2.4
- **Enhancement**: Handle empty HTTP response.

### Version 1.2.3
- **Enhancement**: Minor changes to code style.

### Version 1.2.2
- **Enhancement**: Added additional `timestamp filters` to item collect in order to fetch updated item / variation and its relational data.
- **Enhancement**: Added detailed information to collection response message that includes applied filters to search criteria.

### Version 1.2.1
- **Enhancement**: Improvement to \SoftCommerce\PlentyItemRestApi\Model\Request\Pim\VariationSearchCriteriaInterface::getWithSearchCriteria

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.0
- **Feature**: [M2PO-58] New module to handle Item REST API requests.

# Package: softcommerce/module-plenty-log

### Version 1.2.6
- **Enhancement**: General code improvements.

### Version 1.2.5
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7

### Version 1.2.4
- **Enhancement**: Changed console command names for better reading.

### Version 1.2.3
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1 #2

### Version 1.2.2
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.1
- **Enhancement**: Minor changes to code style.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.1
- **Improvement**: [M2PM2-102] Add new option to update table fields. E.g. update `catalog_product_entity.plenty_item_id`.

### Version 1.0.0
- **Feature**: [M2PM2-102] New module to handle Plenty Log services.

# Package: softcommerce/module-plenty-order

### Version 1.3.9
- **Fix**: Order export - duplicate payment. https://github.com/softcommerceltd/mage2plenty-os/issues/14: [#14]

### Version 1.3.8
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7

### Version 1.3.7
- **Feature**: New method in SoftCommerce\PlentyOrder\Api\Data\OrderInterface to check if an order has child orders with Type ID: Delivery. [#5]
- **Feature**: New method in SoftCommerce\PlentyOrder\Api\Data\OrderInterface to retrieve order item by a property value. [#4]

### Version 1.3.6
- **Feature**: Add custom payment method for internal payment import used for external orders that have no payments. [#3]

### Version 1.3.5
- **Enhancement**: Changed console command names for better reading.

### Version 1.3.4
- **Fix**: Apply a fix to cached data in \SoftCommerce\PlentyOrder\Model\GetSalesOrderEntityIdByIncrementIdInterface::execute #2

### Version 1.3.3
- **Enhancement**: Remove Plenty Order ID reference from sales_order.plenty_order_id when client orders are deleted. #1

### Version 1.3.2
- **Feature**: Added new functionality to collect, created and manage address option types.

### Version 1.3.1
- **Compatibility**: Added compatibility PHP 8.[0,1] and Magento 2.4.6.

### Version 1.3.0
- **Fix**: Applied a fix to database declarative schema setup, where column type xsi="json" is not support in MySQL 8 engine. Error trace: Module 'Magento_SalesArchive':
Running schema recurring...Warning: Undefined array key "" in vendor/magento/framework/Setup/SchemaListener.php on line 137

### Version 1.2.9
- **Feature**: Added an option to create a credit note from a parent order in PlentyMarkets (order export). [#3]

### Version 1.2.8
- **Enhancement**: Added new methods to `SoftCommerce\PlentyOrder\Api\Data\OrderInterface`.

### Version 1.2.7
- **Fix**: Applied a fix to `\SoftCommerce\PlentyOrder\Model\GetSalesOrderIncrementIdByEntityId::execute`, where entity ID was returned instead of increment ID.

### Version 1.2.6
- **Enhancement**: Added improvements to sales order reservation repository `SoftCommerce\PlentyOrder\Model\SalesOrderReservationRepository`.

### Version 1.2.5
- **Enhancement**: Added improvements to mass-actions for client order list.

### Version 1.2.4
- **Enhancement**: New methods added to `\SoftCommerce\PlentyOrder\Model\Order::class`.

### Version 1.2.3
- **Fix**: Applied a fix to massaction status change in `Order Import / Export Queue` page.

### Version 1.2.2
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.1
- **Enhancement**: Minor changes to code style.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.1
- **Feature**: New module to handle Plenty Log services. [#3]
- **Compatibility**: Compatibility with Magento Open Source 2.3.5 - 2.4.3 [#2]
- **Enhancement**: Integration Tests [#1]

### Version 1.0.0
- **Feature**: [M2PO-61] Implement PlentyMarkets' shipping countries configuration data storage.
- **Fix**: [M2PO-60] Error: Argument 1 passed to Plenty\\Stock\\Profile\\Config\\StockSource::getStockIdByWarehouseId() must be of the type int.
- **Fix:** [M2PO-20] Order shipment tracking numbers.
- **Improvement**: [M2PO-59] Add transaction ID to payment booking text property.
- **Fix**: [M2PSR-4] Error when running profile schedule. [Profile ID: *, Error: Argument 1 passed to Plenty\Order\Model\Order::setCustomerId() must be of type int or null, string given, called in Plenty\Order\Profile\Service\OrderImport on line 311]
- **Fix:** [M2PO-53] Could not create order. [Order ***, Reason: validation error found, the order items1.orderItemName must be a string.]
- **Fix:** [M2PO-52] Permission issue for order export / import actions within sales order operations
- **Fix:** [M2PO-20] Added a fix to shipment tracks creation where cached track number was added to wrong shipments.
- **Feature:** New module to handle category entity.
- **Feature:** [M2PO-51] Multiple order referrer filter not working
- **Feature:** [M2PO-20] Order shipment tracking numbers.
- **Feature:** [M2PO-50] An option to create order referrer in Magento.
- **Fix:** [M2PO-46] Duplicate coupon discount applied to both order and order items. Issue reopened and fixed.
- **Compatibility**: [M2PO-47] `Amasty Special Promotions Pro` compatibility.
- **Fix**: [M2PO-48] Could not create order. [Order: ****, Reason: Notice: Trying to access array offset on value of type bool in vendor/plenty/module-stock/Profile/Config/StockSource.php on line 141.
- **Compatibility**: Magento 2.4.3 compatibility and general code improvement.
- **Fix:** [M2PO-46] Duplicate coupon discount applied to both order and order items.
- **Fix:** [M2PO-45] Fix order address / contact title mapping.
- **Feature:** [M2PO-37] Create a feature to cancel an order in PM.
- **Improvement**: [M2PO-35] Implement a way of adding different types of order items to order export request data generator.
- **Improvement**: [M2PO-34] Implement locking mechanism for order export entity.
- **Improvement**: [M2PC-20] Add customer title / gender to contact and address export.
- **Improvement**: Improvements to tax rate in order item export generator.
- **Improvement**: Remove empty value from mandatory order referrer drop-down list. #4
- **Fix**: [M2PO-33] Could not update contact data. [Order ***, Reason: {"error":{"message":"validation error found"},"validation_errors":{"title":["The title must be a string."]}}]
- **Fix**: [M2PO-32] Array to string conversion in vendor/plenty/module-order/Profile/Service/OrderExport/Generator/Payment.php on line 79
- **Fix**: [M2PO-31] Argument 1 passed to SoftCommerce\PlentyOrder\Profile\Service\OrderImport::getSalesOrderByEntity() must be of the type int, string given, called in app/code/Plenty/Order/Profile/Service/OrderImport.php on line 480
- **Fix**: [M2PC-20] Add customer title to contact export. - reopened again - fixed and closed.
- **Fix**: [M2PC-20] Add customer title to contact export. - reopened - fixed and closed.
- **Fix**: [M2PM2-88] Integration tests failure.
- **Improvement**: [M2PO-23] Implement client configuration repository to include interface for each configuration.
- **Improvement**: Minor contextual improvements.
- **Fix**: [M2PO-26] Could not create order. [Order: xxx, Reason: Notice: Undefined index: source_code in vendor/plenty/module-order/Profile/Service/OrderExport/Generator/Order/Item.php on line 674]
- **Compatibility**: [M2PS-12] Stock reservation compatibility for Magento 2.3.5 and earlier.
- **Improvement**: [M2PO-24] Performance impact on loading sales order grid while joining plenty_order_entity table that adds custom columns.
- **Feature**: [M2PO-5] Add functionality to delete client orders from within backend.
- **Fix**: [M2PO-4] Duplicate order item during order export.
- **Fix**: [M2PC-19] Customer title not exporting.
- **Fix**: [M2PO-8] Deprecated Functionality: Cannot use "parent" when current class  scope has no parent in /app/vendor/plenty/module-order/Profile/Service/OrderExportManagement.php on line 178
- **Feature**: [M2PO-11] Order Export / Import ::: Add event dispatch after data save.
- **Feature**: Added an option to assign order items to stock sources and warehouses by source selection algorithm (SSA), which accepts automatic assignment by source priority or destination.
- **Feature**: [M2PO-23] Implement client order configuration repositories to include payment methods, properties, referrers, shipping profiles and order statuses.
- **Compatibility**: PSR-1 and PSR-2 compliance.
- **Fix**: [M2PO-9] Could not create order. [Order: xxx, Reason: Notice: Undefined offset: 9 in vendor/plenty/module-order/Profile/Service/OrderExport/Generator/Order.php on line 114]
- **Fix**: [M2PM2-68] Deprecated Functionality: Cannot use "parent" when current class scope has no parent in /app/vendor/plenty/module-order/Profile/Service/OrderExportManagement
- **Fix**: [M2PO-13] Argument 1 passed to SoftCommerce\PlentyOrder\Model\Order::setCustomerId() must be of the type int or null
- **Fix**: [M2PO-12] Order export throws exception: Undefined variable: existingItem in vendor/plenty/module-order/Profile/Service/OrderExport/Generator/Order/Item.php on line 413
- **Improvement**: [M2PO-15] Order Export ::: Add order item properties
- **Fix**: [M2PO-10] Order Export ::: Could not create order. [Order: XXX, Reason: Unique constraint violation found]
- **Feature**: [M2PO-18] Add billing / shipping address flags to order export.
- **Fix**: [M2PO-2] Discount amount tax calculation issues in order export.
- **Feature**: [M2PO-1] Introduce shipment document export for order export.
- **Feature**: Added client order status name to sales order grid.
- **Improvement**: Added store language to properties within order export request parameters in order to enable document language setting for orders in PlentyMarkets.
- **Improvement**: Changed private method `SoftCommerce\PlentyOrder\Profile\Service\OrderExport\Generator\Order\Item::getPlentyVariationId()` to public in order to allow substitution.
- **Feature**: Added date filter to order export CLI command.
- **Feature**: Added `updatedAtTo` and `createdAtTo` filters to REST API search criteria.
- **Feature**: Added an import, export and remove mass-actions to client order grid within profile.
- **Fix**: Applied a fix to order export status prediction.
- **Improvement**: Added extra validation rules to order payment export.
- **Improvement**: Added functionality to search client orders, which are registered with sales order but do not exist within records, externally. For example, when order was exported to PM but is removed from plenty_order_entity record table is now searched externally to prevent duplicate order export.
- **Improvement**: [M2PO-14] Order import - missed schedules for order import
- **Feature**: [M2PO-17] Shipping profile mapping.
- **Feature**: [M2PO-3] Implement order cancellation functionality for order import / export.
- **Fix**: Applied a fix to manual order import since wrong argument was passed to search criteria. 
- **Fix**: Applied a fix to order locking to allow import / export with search criteria applied.
- **Fix**: Removed `DateTimeLocaleInterfaceFactory` instance initialization at constructor level and moved over to `SoftCommerce\PlentyOrder\Console\Command\AbstractCommand::executeBefore`.

### Version 0.1.0
- **Fix**: Added a fix to `SoftCommerce\PlentyOrder\Console\Command\AbstractCommand` to incorporate factory class `DateTimeLocaleInterfaceFactory` in order to make it installable during Magento initial installation.
- **Fix**: Remove an unnecessary comma from within `unset()` function in `SoftCommerce\PlentyOrder\Profile\Service\OrderExport\Processor\Address::getIsShippingSameAsBilling`.
- **Improvement**: Introduced locking for orders in processing state.
- **Feature**: Added date filter to order import on the profile configuration level. 
- **Compatibility**: Added compatibility with Magento 2.4.2
- **Improvement**: Added mass import option from sales order grid to import orders in bulk.
- **Improvement**: Changed logics of order import. Orders are now collected to DB first and processed from therein afterwards. This ensures no missed orders from client end.
- **Improvement**: New order document CRUD model inc. repository and management. Order document data storage is now moved from `plenty_order_entity` to `plenty_order_document`.
- **Improvement**: New order payment CRUD model inc. repository and management. Order payment data storage is now moved from `plenty_order_entity` to `plenty_order_payment`.
- **Improvement**: New order property CRUD model inc. repository and management. Order property data storage is now moved from `plenty_order_entity` to `plenty_order_property`.
- **Improvement**: New customer CRUD model inc. repository and management. Order contacts are now moved from `plenty_order_entity` to `plenty_customer_entity`.
- **Improvement**: New address CRUD models inc. repository and management. Order address data is now moved from `plenty_order_entity` to `plenty_address_entity` and `plenty_address_relation`.
- **Improvement**: Added store filter to order import / export.
- **Improvement**: Changed order DB column names for future upgrade compatibility.
- **Improvement**: Changed order referrer ID to multiselect field within profile configuration to allow filter order import by multiple referrer IDs.
- **Improvement**: Added an order referrer ID to order import filters to avoid foreign orders being registered in DB.
- **Fix**: Applied a fix to credit memo import rules.
- **Fix**: Added a fix to order contact export since error `Could not create contact data. [Order xxx, Reason: Resource not found.]` was throw due to contact ID query having integer value instead of null for new contacts.
- **Fix**: Added a fix to order import item where `order_id` value was required for foreign order entries.
- **Improvement**: Remove unused database fields from plenty_order_item table.
- **Fix**: [M2PO-22] Shipping Profiles issue during order export.
- **Improvement**: Added an improvement to order import conditional rules for creation of invoices.
- **Compatibility**: PSR-1 and PSR-2 compliance.
- **Feature**: Added order hold, unhold and cancel actions to order import.
- **Improvement**: Added tax option to discount and shipping.
- **Improvement**: Improved comparison between shipping and billing address data used for order address export.
- **Improvement**: Improved order import history messages.
- **Improvement**: Added an option to choose invoice capture cases for invoice import.
- **Improvement**: Changes to order export filter configuration.
- **Compatibility**: Changes to composer.json
- **Feature**: Added condition to create order invoices by document presence.
- **Fix**: Added a fix to database schema setup, where foreign keys failed to remove from tables which were subject to deletion.
- **Fix**: Applied a fix to date filter for order import collection; 
- **Compatibility**: Added compatibility for Magento Commerce.
- **Feature**: Added coupon promotion to order export.
- **Feature**: Added an option to create order property.
- **Feature**: Added an option to map order properties.
- **Fix**: Added a fix to order import, where stock was deducted before shipment creation.
- **Improvement**: Added history management for improved process tracking.
- **Improvement**: Added queue processor.
- **Feature**: Added CLI for order export / import.
- **Improvement**: Added client order information within sales order view page.
- **Feature**: Added functionality to create `invoice document` in PlentyMarkets.
- **Improvement**: Added order `documents` to order entity.
- **Improvement**: Added clear descriptions of entity tables.
- **Improvement**: Added order `properties, amounts, relations and address relation` to order entity.
- **Feature**: Added `date filter` to order export search criteria.
- **Feature**: Added `Multi stock inventory` support.
- **Feature**: Added `warehouse mapping` to stock source mapping.
- **Feature**: Added shipment creation based on stock source priority.
- **Feature**: Added ability to manually collect PlentyMarket's configuration data.
- **Compatibility**: Removed order item property image. This is now handled as separate route. Needs to be implemented in next version.
- **Compatibility**: Removed order property payment status. This is now handled as separate route. Needs to be implemented in next version.
- **Fix**: Apply alternative means of retrieving array key in favour of array_key_first.
- **Fix**: Removed migration option from declarative schema install script.
- **Feature**: Added `discount amount` to order item export data.
- **Feature**: Added `item name` to order export when item / variation ID is unknown.
- **Feature**: Created `ORDER` module

# Package: softcommerce/module-plenty-order-client

### Version 1.2.8
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1 #2

### Version 1.2.7
- **Compatibility**: Added compatibility PHP 8.[0,1] and Magento 2.4.6.

### Version 1.2.6
- **Compatibility**: Compatibility with `SoftCommerce_PlentyOrderProfile` version 1.4.2.

### Version 1.2.5
- **Enhancement**: Added new methods to `SoftCommerce\PlentyOrderClient\Model\ShippingCountry`.

### Version 1.2.4
- **Compatibility**: Compatibility with Magento [CE/EE/ECE] 2.4.5 and PHP 8

### Version 1.2.3
- **Fix**: Fix pagination for client data collect process.

### Version 1.2.2
- **Enhancement**: Introduce pagination for client data collect process.

### Version 1.2.1
- **Enhancement**: Minor changes to code style.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.1
- **Feature**: New module to handle Plenty Log services. [#3]
- **Compatibility**: Compatibility with Magento Open Source 2.3.5 - 2.4.3 [#2]
- **Enhancement**: Integration Tests [#1]

### Version 1.0.0
- **Feature**: [M2PO-55] New module to handle order client entity.

# Package: softcommerce/module-plenty-order-profile

### Version 1.6.14
- **Fix**: The website with id ### that was requested wasn't found. Verify the website and try again. [#15]

### Version 1.6.13
- **Fix**: Order export - duplicate payment. https://github.com/softcommerceltd/mage2plenty-os/issues/14: [#14]

### Version 1.6.12
- **Enhancement**: Add scoped config to \SoftCommerce\PlentyOrderProfile\Model\Utils\IsShippingAddressSameAsBillingInterface [#33]

### Version 1.6.11
- **Feature** Create new queue messaging for order collect process [#32]

### Version 1.6.10
- **Fix**: PM Order Status not updated in Magento order grid. [#30]

### Version 1.6.9
- **Enhancement**: General code improvements.

### Version 1.6.8
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7

## Version 1.6.7
- **Enhancement**: Improvements to SoftCommerce\PlentyOrderProfile\Model\OrderExportService\Generator\Order\Items\Item::isSimpleLineItem [#31]

## Version 1.6.6
- **Enhancement**: Improvements to SoftCommerce\PlentyOrderProfile\Model\OrderImportService\Generator::Shipment [#29]
- **Enhancement**: Improved cache storage for SoftCommerce\PlentyOrderProfile\Model\Utils\OrderItemVariationDataStorage::getVariationId [#28]
- **Enhancement**: Order item variation ID isn't assigned to order line item upon request. Create a workaround to use item property to assign Magento's item ID. [#26]

## Version 1.6.5
- **Fix**: Fix order line item discount where discount should by divided by qty [#27]

## Version 1.6.4
- **Enhancement**: Improve messages for shipment import from PM to Magento [#25]
- **Enhancement**: Handle order and contact relations for existing payments. [#24]

## Version 1.6.3
- **Enhancement**: Handle duplicate client payment hash while re-creating payments in PM [#23]
- **Feature**: New CLI functionality to delete client order payments externally [#22]
- **Feature**: New CLI functionality to delete client orders externally [#21]

## Version 1.6.2
- **Fix**: Could not process order: validation_errors: {"discount":["Not a (strict) numeric value."]} [#20]

## Version 1.6.1
- **Fix**: Apply a fix to the setup of data patch for SoftCommerce\PlentyOrderProfile\Setup\Patch\Data\ChangeOrderLineItemConfigPath [#19]

### Version 1.6.0
- **Enhancement**: An option to allow applying promotion discount to order line items. [#18]

### Version 1.5.9
- **Fix**: Fix order item export for configurable products with no children items. #17

### Version 1.5.8
- **Fix**: Order export line item has price 0.00 [#16]

### Version 1.5.7
- **Enhancement**: Change sort number for virtual order processor from 100 to 1000 in order to allow more items within the process. #15

### Version 1.5.6
- **Enhancement**: Configuration options to allow exporting order line items for bundle components #13

### Version 1.5.5
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1 #12

### Version 1.5.4
- **Enhancement**: Include all bundle items for order export. #11
- **Enhancement**: Interface \SoftCommerce\PlentyOrderProfile\Model\Utils\OrderItemVariationDataStorageInterface returns wrong variation ID from bundle product #10

### Version 1.5.3
- **Fix**: Wrong order address email being sent to PM. #9
- **Fix**: Array to string conversion in vendor/softcommerce/module-plenty-order-profile/Model/OrderExportService/Generator/Payment.php on line 81] #8

### Version 1.5.2
- **Enhancement**: Provide configure the shipping title to be taken from either Magento or PM system #7

### Version 1.5.1
- **Enhancement**: Changes to the logic of invoice import conditions within the configuration. #6

### Version 1.5.0
- **Enhancement**: Converted protected methods to public to allow interception of `SoftCommerce\PlentyOrderProfile\Model\OrderExportService\Generator\OrderAddress` by other vendors.

### Version 1.4.9
- **Fix**: Added a fix to customer address relation export.
- **Feature**: Added new functionality to collect, created and manage address option types.

### Version 1.4.8
- **Fix**: Added a fix to item tax amounts for order import.

### Version 1.4.7
- **Enhancement**: Added improvements to order address relation export.

### Version 1.4.6
- **Fix**: Call to a member function setBasePrice() on string#0 `vendor/softcommerce/module-plenty-order-profile/Model/OrderImportService/Generator/QuoteItem.php(263)`,
since adding product to quote returns string in case of an error.

### Version 1.4.5
- **Enhancement**: Added new process chain validation to exclude order export by store mapping.
- **Enhancement**: Added new payment properties to REST API search criteria.

### Version 1.4.4
- **Compatibility**: Added compatibility PHP 8.[0,1] and Magento 2.4.6.
- **Enhancement**: Improvements to order import services.

### Version 1.4.3
- **Fix**: Cannot access offset of type string on string at `SoftCommerce\PlentyOrderProfile\Model\OrderExportService\PostProcessor\SaveSalesCreditmemoHistory::excecute`. [#5]

### Version 1.4.2
- **Feature**: Added an option to create a credit note artifact in PlentyMarkets (order export) [#4]
- **Feature**: Added an option to create a credit note from a parent order in PlentyMarkets (order export). [#3]

### Version 1.4.1
- **Fix**: Argument #2 ($storeId) must be of type int, null given, called in softcommerce/module-plenty-order-profile/Model/OrderExportService/Generator/Address.php on line 421 [#2]

### Version 1.4.0
- **Fix**: Argument #2 ($storeId) must be of type int, null given, called in softcommerce/module-plenty-order-profile/Model/OrderExportService/Generator/Contact.php on line 185 [#1]

### Version 1.3.9
- **Feature**: Added an option to import foreign orders from 3rd party channels.

### Version 1.3.8
- **Enhancement**: Converted private method to public: `\SoftCommerce\PlentyOrderProfile\Model\OrderExportService\Generator\Order\Items\Item::getPlentyVariationId()`
in order to allow interception by other modules.

### Version 1.3.7
- **Enhancement**: Improvements to shipping import, where new public methods were added to allow extending
the behavior of public methods for `SoftCommerce\PlentyOrderProfile\Model\OrderImportService\Processor\Shipment` class.

### Version 1.3.6
- **Compatibility**: Compatibility with the latest updates to `SoftCommerce_PlentyProfile`

### Version 1.3.5
- **Compatibility**: Compatibility with Magento 2.4.5 & PHP 8.
- **Fix**: Applied a fix to order export, where duplicate orders were created due to empty response from PM server which resulted in re-submission of orders upon error.
- **Fix**: Applied a fix to order property for payment method ID that resulted in wrong payment method being re-assigned to order upon update.
- **Fix**: Applied a fix to payment export, where payment wasn't assigned an ID for contact_relation_id. 

### Version 1.3.4
- **Fix**: Applied a fix to missing item name. Ref: main.ERROR: {"error":{"message":"validation error found"},"validation_errors":{"orderItems.1.orderItemName":["The order items.1.order item name must be a string."]}}
- **Fix**: Applied a fix for TypeError: Return value of SoftCommerce\PlentyOrderProfile\Model\OrderExportService\Processor\Order::getClientOrderExternally() must implement interface SoftCommerce\PlentyOrder\Api\Data\OrderInterface or be null, instance of Magento\Framework\DataObject returned in vendor/softcommerce/module-plenty-order-profile/Model/OrderExportService/Processor/Order.php:185
- **Enhancement**: Added adjustments to payment export to include transaction ID within booking text property payment.

### Version 1.3.3
- **Enhancement**: Added item collect schedule processor.

### Version 1.3.2
- **Enhancement**: Added new mass-action option to delete orders externally in client order list.

### Version 1.3.1
- **Fix**: Applied a fix for duplicate `order_id` in `plenty_order_entity` table, where credit-notes were matched to existing orders in Magento that resulted in duplicate order ID values.

### Version 1.3.0
- **Enhancement**: Improvements to order export shipping profiles.

### Version 1.2.9
- **Fix**: Applied a fix for possible order duplicate due to empty response from PM server during order export.

### Version 1.2.8
- **Enhancement**: Implemented initial collect timestamp to allow collect data since specified datetime on initial data collect process.
- **Fix**: Removed `collected_at` timestamp from order export save request data to avoid conflict with order collect process.
- **Fix**: Could not retrieve shipment source assignment. Fallback warehouse ID has been assigned. [SKU ###, Warehouse ID: ###]
- **Enhancement**: Added an option to collect orders by referrer ID.
- **Enhancement**: Added an option to collect and import orders from order import list page.
- **Enhancement**: Added functionality to remove old orders from import queue. E.g. orders such as cancelled, on hold, waiting payment are stuck with `pending` queue status.

### Version 1.2.7
- **Fix**: Call to a member function getWarehouseId() on null#0, since order item could not be found.
- **Enhancement**: Improvements to ACL rules.
- **Enhancement**: Added datetime filter for order import via CLI.
- **Enhancement**: Added an option allow individual payment export per mapping method.
- **Enhancement**: Added an option export unconfirmed payments during order export.
- **Enhancement**: Added an option to change order queue schedule status from sales order list and view pages.
- **Enhancement**: Added an option to collect orders from sales order list and view pages.

### Version 1.2.6
- **Fix**: Applied a fix to payment status export, where order payment status did not update during export.
- **Enhancement**: Added a list of all payment methods to order profile configuration.

### Version 1.2.5
- **Enhancement**: Minor changes to code style.
- **Enhancement**: Minor updates to profile xml configs.

### Version 1.2.4
- **Fix**: Applied a fix to language request data for create contact.

### Version 1.2.3
- **Fix**: Added a fix to discount amounts.

### Version 1.2.2
- **Enhancement**: Changes to PDT.

### Version 1.2.1
- **Enhancement**: Disable the DynamicRowsDragAndDrop component on the DynamicRows components.
- **Fix**: Applied a fix to directory spelling and all of its Classes in `\SoftCommerce\PlentyProfile\Ui\*`

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.1
- **Feature**: New module to handle Plenty Log services. [#3]
- **Compatibility**: Compatibility with Magento Open Source 2.3.5 - 2.4.3 [#2]
- **Enhancement**: Integration Tests [#1]

### Version 1.0.0
- **Feature**: [M2PO-56] New module to handle order profile entity.

# Package: softcommerce/module-plenty-order-profile-schedule

### Version 1.2.11
- **Compatibility** Phaseout profile queue collect process in favour of message queue [#2]

### Version 1.2.10
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7

### Version 1.2.9
- **Compatibility**: Added compatibility PHP 8.[0,1] and Magento 2.4.6.
- **Enhancement**: Added new cron tasks to handle locked orders.

### Version 1.2.8
- **Enhancement**: Added sales channel information to order entity to identify orders from other channels, such as: Amazon, eBay etc.

### Version 1.2.7
- **Enhancement**: Added an option to schedule order collect process via admin UI. Order IDs are saved in a queue and then processed by scheduler.
- **Compatibility**: Compatibility with `SoftCommerce_PlentyOrderProfile` version 1.4.2.

### Version 1.2.6
- **Compatibility**: Compatibility with Magento [OS/AC] 2.4.5 and PHP 8

### Version 1.2.5
- **Fix**: Applied a fix to dateUpdatedAtFrom filter for collect order process, where timestamp filter was ignored due to a bug.

### Version 1.2.4
- **Enhancement**: Added process batch size to limit collection size for order export / import cron schedule runs.

### Version 1.2.3
- **Enhancement**: Added `referrer ID` filter to order collect process.

### Version 1.2.2
- **Enhancement**: Minor changes to code style.

### Version 1.2.1
- **Enhancement**: Allow collect client data when import / export scheduler is inactive.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.0
- **Feature**: [M2PO-57] New module to handle order profile schedule entity.

# Package: softcommerce/module-plenty-order-rest-api

### Version 1.2.8
- **Fix**: Order export - duplicate payment. https://github.com/softcommerceltd/mage2plenty-os/issues/14: [#14]

### Version 1.2.7
- **Enhancement**: Handle empty response for SoftCommerce\PlentyOrderRestApi\Model\Payment\RelationInterface [#5]
- **Enhancement**: Handle empty response for \SoftCommerce\PlentyOrderRestApi\Model\PaymentInterface::delete [#4]
- **Enhancement**: Add ID search criteria to SoftCommerce\PlentyOrderRestApi\Model\PaymentInterface::getList [#3]
- **Enhancement**: Add bulk payment URI for SoftCommerce\PlentyOrderRestApi\Model\Uri\Payment [#2]
- **Enhancement**: Handle empty response for SoftCommerce\PlentyOrderRestApi\Model\OrderInterface::delete [#1]

### Version 1.2.6
- **Enhancement**: Added new payment properties to REST API search criteria.

### Version 1.2.5
- **Enhancement**: Added new routes to handle credit notes.
- **Compatibility**: Compatibility with `SoftCommerce_PlentyOrderProfile` version 1.4.2.

### Version 1.2.4
- **Enhancement**: Added additional metadata to `SoftCommerce\PlentyOrderRestApi\Model\OrderInterface`.

### Version 1.2.3
- **Enhancement**: Improvements to error handling on empty response from PM server.

### Version 1.2.2
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.1
- **Enhancement**: Minor changes to code style.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.0
- **Feature**: [M2PO-58] New module to handle order REST API requests.

# Package: softcommerce/module-plenty-profile

### Version 1.3.3
- **Enhancement**: Added a method to filter stores by unique locals in `\SoftCommerce\PlentyProfile\Model\Config\StoreConfigInterface`

### Version 1.3.2
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7

### Version 1.3.1
- **Compatibility**: Added compatibility PHP 8.[0,1] and Magento 2.4.6.

### Version 1.3.0
- **Enhancement**: Added store name to response data in `SoftCommerce\PlentyProfile\Model\Config\StoreConfigInterface::getStoreMapping`.

### Version 1.2.9
- **Enhancement**: Removed unused interface `SoftCommerce\PlentyProfile\Model\Config\GeneralInterface` and its class `SoftCommerce\PlentyProfile\Model\Config\General`.

### Version 1.2.8
- **Compatibility**: Compatibility with Magento [OS/AC] 2.4.5 and PHP 8

### Version 1.2.7
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.6
- **Enhancement**: Handle empty HTTP response from PM server.

### Version 1.2.5
- **Enhancement**: Minor changes to code style.

### Version 1.2.4
- **Enhancement**: Added additional `timestamp filters` to item collect in order to fetch updated item / variation and its relational data.
- **Enhancement**: Added detailed information to collection response message that includes applied filters to search criteria.
- **Fix**: Changes to module.xml where dependence `SoftCommerce_PlentyCore` was replaced with `SoftCommerce_PlentyClient`.

### Version 1.2.3
- **Fix**: Applied a fix to directory spelling and all of its Classes in `\SoftCommerce\PlentyProfile\Ui\*`

### Version 1.2.2
- **Compatibility**: [M2P-5] JS Error: Uncaught TypeError: this.disableComponent is not a function create-external-entity-button.js:28

### Version 1.2.1
- **Compatibility**: JS Modal: IE9 break script loading and avoid execution on iframe [#5]

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.1
- **Feature**: New module to handle Plenty Log services. [#3]
- **Compatibility**: Compatibility with Magento Open Source 2.3.5 - 2.4.3 [#2]
- **Enhancement**: Integration Tests [#1]

### Version 1.0.0
- **Feature**: [M2PM2-98] New module to handle profile entity.

# Package: softcommerce/module-plenty-property

### Version 1.3.1
- **Enhancement**: Improvements to property export [#3]
- **Enhancement**: Implement queue message to handle data collection process upon completion of property export [#2]

### Version 1.3.0
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7
- **Feature**: New functionality and improvements to property export [#1]

### Version 1.2.5
- **Enhancement**: Changed console command names for better reading.

### Version 1.2.4
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1

### Version 1.2.3
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.2
- **Enhancement**: Added ability to collect client data using CLI.
- **Enhancement**: Minor changes to code style.

### Version 1.2.1
- **Fix**: Added a fix to former property type `attribute_set_code`, where property name was changed to `attribute_set_id`. Issue resulted in wrong product attribute set group.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.0
- **Feature**: [M2PP-1] New module to handle property entity.

# Package: softcommerce/module-plenty-property-rest-api

### Version 1.2.5
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7

### Version 1.2.4
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1

### Version 1.2.3
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.2
- **Enhancement**: Minor changes to code style.

### Version 1.2.1
- **Fix**: Added a fix to former property type `attribute_set_code`, where property name was changed to `attribute_set_id`. Issue resulted in wrong product attribute set group.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.0
- **Feature**: [M2PP-1] New module to handle property REST API requests.

# Package: softcommerce/module-plenty-rest-api

### Version 1.3.5
- **Enhancement**: General code improvements.

### Version 1.3.4
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7

### Version 1.3.3
- **Enhancement**: Add public constants for client HTTP query messages. 

### Version 1.3.2
- **Enhancement**: Handle empty client response for \SoftCommerce\PlentyRestApi\Model\HttpClient\Curl::unserializeData [#1]

### Version 1.3.1
- **Compatibility**: Added compatibility with Magento [CE|EE|ECE] 2.4.6.

### Version 1.3.0
- **Compatibility**: Added compatibility PHP 8.[0,1] and Magento 2.4.6.

### Version 1.2.9
- **Enhancement**: Improvements to error logging.

### Version 1.2.8
- **Compatibility**: Compatibility with Magento [OS/AC] 2.4.5 and PHP 8

### Version 1.2.7
- **Enhancement**: Improvements to error handling on empty response from PM server.

### Version 1.2.6
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.5
- **Fix**: Handle throttling, when short period read call is exhausted. 

### Version 1.2.4
- **Enhancement**: Implement item / variation PIM collect service scrolled by cursor in order to overcome item / variation result limit.

### Version 1.2.3
- **Enhancement**: Handle empty HTTP response.

### Version 1.2.2
- **Enhancement**: Minor changes to code style.

### Version 1.2.1
- **Enhancement**: Added additional `timestamp filters` to item collect in order to fetch updated item / variation and its relational data.
- **Enhancement**: Added detailed information to collection response message that includes applied filters to search criteria.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.0
- **Feature**: [M2PM2-99] New module to handle client REST API.

# Package: softcommerce/module-plenty-stock

### Version 1.3.5
- **Enhancement**: Compatibility with new stock functionality. https://github.com/softcommerceltd/mage2plenty-os: [#12]

### Version 1.3.4
- **Feature**: Introduce onetime schedule to collect stock at specified times as part of cron job process [#6]
- **Enhancement**: Remove deprecated functionality for stock collect message queue [#5]

### Version 1.3.3
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7

### Version 1.3.2
- **Enhancement**: Removed deprecated class SoftCommerce\PlentyStock\Model\QueueManagement [#4]
- **Enhancement**: Removed class SoftCommerce\PlentyStock\Model\Queue [#3]

### Version 1.3.1
- **Enhancement**: CLI option to retrieve product saleable qty per stock and/or source code. [#2]

### Version 1.3.0
- **Fix**: Could not process order. [Order: ***, Reason: No destination address was provided in the request] #1

### Version 1.2.9
- **Enhancement**: Changed console command names for better reading.

### Version 1.2.8
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1

### Version 1.2.7
- **Compatibility**: Compatibility with the latest updates to `SoftCommerce_PlentyClient`

### Version 1.2.6
- **Compatibility**: Compatibility with Magento [OS/AC] 2.4.5 and PHP 8

### Version 1.2.5
- **Enhancement**: Adjustment to stock client reservation management.

### Version 1.2.4
- **Enhancement**: Removed stock item scheduler in favour of queue management `SoftCommerce\ProfileQueue\Model\QueueManagementInterface`.

### Version 1.2.3
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.2
- **Enhancement**: Allow import stock items with 0 quantities.

### Version 1.2.1
- **Enhancement**: Minor changes to code style.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.0
- **Feature**: [M2PS-19] New module to handle stock entity.
- **Fix**: [M2PSR-4] Error when running profile schedule. [Profile ID: *, Error: Argument 1 passed to Plenty\Stock\Profile\Config\StockSource::getStockIdBySourceCode() must be of type string, null given, called in Plenty\StockReservation\Profile\Service\OrderExport\Processor\InventoryReservation on line 151]
- **Fix**: [M2PO-48] Could not create order. [Order: ****, Reason: Notice: Trying to access array offset on value of type bool in vendor/plenty/module-stock/Profile/Config/StockSource.php on line 141.
- **Fix**: [M2PS-17] Stock item not applicable for management. [Variation ID: ***, Warehouse ID: ***]
- **Coding Standards**: PSR-1 and PSR-2 compliance.
- **Feature**: [M2PI-49] Introduce customer group pricing functionality.
- **Compatibility**: php 7.2 compatibility.
- **Fix**: [M2PM2-88] Integration tests failure.
- **Improvement**: Minor contextual improvements.
- **Compatibility**: [M2PS-12] Stock reservation compatibility for Magento 2.3.5 and earlier.
- **Feature**: [M2PS-9] Add stock import action to catalog product edit split button actions.
- **Feature**: [M2PS-5] Add search criteria filters to REST API routes.
- **Feature**: [M2PS-3] Add SKU filter to inventory grid.
- **Feature**: [M2PS-2] Implement stock item scheduler using message queue.
- **Feature**: [M2PS-1] Create profile entity configuration for stock.
- **Improvement**: [M2PS-6] Stock reservation improvement.    
- **Improvement**: [M2PS-4] Stock Import ::: Stock improvement.
- **Improvement**: Added item `source_code` to inventory_reservation.metadata in order to manage reservations by a warehouse and its source.
- **Coding Standards**: PSR-1 and PSR-2 compliance.
- **Compatibility**: Updates include changes to `Plenty_Order`.

### Version 0.1.0
- **Improvement**: Updates to profile entity.
- **Coding Standards**: PSR-1 and PSR-2 compliance.
- **Compatibility**: Changes to composer.json
- **Fix**: Added a fix to `Unknown column 'cpev_tb.entity_id' in catalog_product_entity_varchar` due to EE using row_id instead of entity_id fields.
- **Compatibility**: Added compatibility for Magento Commerce.
- **Fix**: Fixed wrong sku assignment to stock item caused by SKU cache pool during stock import.
- **Improvement**: Added history management for improved process tracking.
- **Improvement**: Added queue processor.
- **Feature**: Added stock reservation.
- **Feature**: Added CLI for stock import.
- **Feature**: Added Warehouse location details.
- **Feature**: Added Warehouse dimension details.
- **Feature**: Added Multi stock inventory support.
- **Feature**: Added warehouse to stock source mapping.
- **Feature**: Added ability to manually collect PlentyMarket's configuration data.
- **Improvement**: Added product `entity id` and `sku` to stock import table in order to create a link to product page from grid.
- **Feature**: Created stock synchronisation module

# Package: softcommerce/module-plenty-stock-client

### Version 1.2.6
- **Enhancement**: Changed console command names for better reading.

### Version 1.2.5
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1

### Version 1.2.4
- **Compatibility**: Compatibility with Magento [OS/AC] 2.4.5 and PHP 8

### Version 1.2.3
- **Fix**: Fix pagination for client data collect process.

### Version 1.2.2
- **Enhancement**: Introduce pagination for client data collect process.

### Version 1.2.1
- **Enhancement**: Minor changes to code style.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.1
- **Feature**: New module to handle Plenty Log services. [#3]
- **Compatibility**: Compatibility with Magento Open Source 2.3.5 - 2.4.3 [#2]
- **Enhancement**: Integration Tests [#1]

### Version 1.0.0
- **Feature**: [M2PO-55] New module to handle stock client entity.

# Package: softcommerce/module-plenty-stock-profile

### Version 1.4.0
- **Enhancement**: Move softcommerce/module-plenty-stock-reservation module to softcommerce/module-plenty-stock-profile. https://github.com/softcommerceltd/mage2plenty-os/issues/12: [#12]

### Version 1.3.9
- **Fix**: Apply a fix for Type Error occurred when creating object: SoftCommerce\PlentyStockProfile|Model|Mq|CollectStockProcessor\RequestDataProvider, Cannot assign null to property $profile of type int [13]

### Version 1.3.8
- **Fix**: Adjustment to profile_plenty_stock_import_form.xml action sort order

### Version 1.3.7
- **Fix**: Undefined array key "default" in SoftCommerce/PlentyStockProfile/Model/Config/StockConfig.php on line 134 [#11]
- **Feature**: New functionality to export stock using stock correction routes [#10]
- **Feature**: Introduce onetime schedule to collect stock at specified times as part of cron job process [#8]
- **Feature**: Create new queue messaging for stock collect process [#7]
- **Feature**: New stock export functionality [#6]

### Version 1.3.6
- **Fix**: Applied a fix to message output in `SoftCommerce\PlentyStockProfile\Observer\Backend\ProfileSaveAfterControllerAction::execute`

### Version 1.3.5
- **Fix** Applied a fix to item indexing and cache clearance after source item import. [#5]

### Version 1.3.4
- **Enhancement**: General code improvements.

### Version 1.3.3
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7

### Version 1.3.2
- **Enhancement**: Changed console command names for better reading.

### Version 1.3.1
- **Compatibility**: Added compatibility PHP 8.[0,1] and Magento 2.4.6.

### Version 1.3.0
- **Compatibility**: Compatibility with the latest updates to `SoftCommerce_PlentyProfile`

### Version 1.2.9
- **Enhancement**: Added a filter to disallow collecting stock for warehouse with ID 0 (that is global stock calculation).
- **Compatibility**: Compatibility with Magento [OS/AC] 2.4.5 and PHP 8

### Version 1.2.8
- **Enhancement**: Adjustment to stock client reservation management.

### Version 1.2.7
- **Enhancement**: Added profile queue listing modal to stock item import queue listing page.

### Version 1.2.6
- **Enhancement**: Added schedule and history modal view to stock item import queue list page.
- **Enhancement**: Added timestamp history to collect process.
- **Enhancement**: Added an option to collect and import stock items from import queue list page.

### Version 1.2.5
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.4
- **Enhancement**: Allow import stock items with 0 quantities.

### Version 1.2.3
- **Enhancement**: Added ability to collect client data using CLI.
- **Enhancement**: Minor changes to code style.
- **Enhancement**: Minor updates to profile xml configs.

### Version 1.2.2
- **Enhancement**: Changes to PDT.

### Version 1.2.1
- **Enhancement**: Disable the DynamicRowsDragAndDrop component on the DynamicRows components.
- **Fix**: Applied a fix to directory spelling and all of its Classes in `\SoftCommerce\PlentyProfile\Ui\*`

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.1
- **Feature**: New module to handle Plenty Log services. [#3]
- **Compatibility**: Compatibility with Magento Open Source 2.3.5 - 2.4.3 [#2]
- **Enhancement**: Integration Tests [#1]

### Version 1.0.0
- **Feature**: [M2PS-19] New module to handle stock profile services.

# Package: softcommerce/module-plenty-stock-profile-schedule

### Version 1.2.8
- **Feature**: Introduce onetime schedule to collect stock at specified times as part of cron job process [#3]
- **Compatibility** Phaseout profile queue collect process in favour of message queue [#2]

### Version 1.2.7
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1

### Version 1.2.6
- **Enhancement**: Minor cosmetic changes to codebase.

### Version 1.2.5
- **Compatibility**: Compatibility with Magento [OS/AC] 2.4.5 and PHP 8

### Version 1.2.4
- **Enhancement**: Added item collect schedule processor.

### Version 1.2.3
- **Enhancement**: Added timestamp history to collect process.

### Version 1.2.2
- **Enhancement**: Minor changes to code style.

### Version 1.2.1
- **Enhancement**: Allow collect client data when import scheduler is inactive.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.0
- **Feature**: [M2PS-19] New module to handle stock profile schedule services.

# Package: softcommerce/module-plenty-stock-rest-api

### Version 1.2.6
- **Feature**: New functionality to create stock corrections [#1].

### Version 1.2.5
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1

### Version 1.2.4
- **Compatibility**: Compatibility with Magento [OS/AC] 2.4.5 and PHP 8.

### Version 1.2.3
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.2
- **Enhancement**: Added pagination for client HTTP requests.

### Version 1.2.1
- **Enhancement**: Minor changes to code style.

### Version 1.1.0
- **Feature**: New module to handle Plenty Log services. [#3]
- **Compatibility**: Compatibility with Magento Open Source 2.4.3 [#2]
- **Enhancement**: Integration Tests [#1]

### Version 1.0.1
- **Compatibility**: Compatibility with Magento Open Source 2.3.5 - 2.4.2 [#6]

### Version 1.0.0
- **Feature**: [M2PO-55] New module to handle stock rest api entity.

# Package: softcommerce/module-profile

### Version 1.3.6
- **Compatibility**: Apply a fix to compilation errors for modules that use type declaration with union types. [#11] https://github.com/softcommerceltd/mage2plenty-os/issues/11

### Version 1.3.5
- **Enhancement**: General code improvements.

### Version 1.3.4
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7

### Version 1.3.3
- **Enhancement**: Applied changes to the styles for message text colours. [#1]

### Version 1.3.2
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1

### Version 1.3.1
- **Enhancement**: Added process validation chain to allow simpler profile process interception.

### Version 1.3.0
- **Enhancement**: Added an option to enable / disable history logging per profile.
- **Enhancement**: [M2P-10] Added a performance improvement to profile history where messages are now saved in batches.

### Version 1.2.9
- **Enhancement**: Moved mass status action for schedules from `SoftCommerce_Profile` to `SoftCommerce_ProfileSchedule`

### Version 1.2.8
- **Compatibility**: Compatibility with Magento [OS/AC] 2.4.5 and PHP 8

### Version 1.2.7
- **Fix**: Applied a fix to `isDataSerialized` UI select argument, where element type select failed to retrieve values for serialised data type.

### Version 1.2.6
- **Enhancement**: Added new event `softcommerce_profile_config_save_before` to profile save action.

### Version 1.2.5
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.4
- **Compatibility**: Compatibility with Magento Extension Quality Program (EQP).

### Version 1.2.3
- **Enhancement**: Changes to PDT.

### Version 1.2.2
- **Enhancement**: Added ability to change profile schedule within profile list page.

### Version 1.2.1
- **Compatibility**: Compatibility with PHP 8.x

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.1
- **Feature**: New module to handle Plenty Log services. [#3]
- **Compatibility**: Compatibility with Magento Open Source 2.3.5 - 2.4.3 [#2]
- **Enhancement**: Integration Tests [#1]

### Version 1.0.0
- **Feature**: [SCP-1] New module to handle multiple profile entities.

# Package: softcommerce/module-profile-config

### Version 1.2.10
- **Enhancement**: General codebase improvements [#3]

### Version 1.2.9
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7

### Version 1.2.8
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1 [#2]
- **Enhancement**: Ability to export / import profile config data. [#1]

### Version 1.2.7
- **Fix**: Applied a fix to `SoftCommerce\ProfileConfig\Model\AbstractConfig::getConfigDataSerialized` where return type must be an array.

### Version 1.2.6
- **Fix**: Applied a fix to composer.json license compatibility.

### Version 1.2.5
- **Compatibility**: Compatibility with Magento [OS/AC] 2.4.5 and PHP 8

### Version 1.2.4
- **Enhancement**: Changed `SoftCommerce\ProfileConfig\Model\AbstractConfig::getTypeId` to public to allow other modules access this method.

### Version 1.2.3
- **Enhancement**: Improvements to config data provider.

### Version 1.2.2
- **Compatibility**: Compatibility with Magento Extension Quality Program (EQP).

### Version 1.2.1
- **Enhancement**: Changes to PDT.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.0
- **Feature**: [SCP-2] New module used to handle profile configuration.

# Package: softcommerce/module-profile-history

### Version 1.2.7
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7

### Version 1.2.6
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1

### Version 1.2.5
- **Fix**: Applied a fix to composer.json license compatibility.

### Version 1.2.4
- **Compatibility**: Compatibility with Magento [OS/AC] 2.4.5 and PHP 8.
- **Enhancement**: Added batch size limit to history data insert per statement.

### Version 1.2.3
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.2
- **Compatibility**: Compatibility with Magento Extension Quality Program (EQP).

### Version 1.2.1
- **Enhancement**: Changes to PDT.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.0.0
- **Feature**: [SCP-3] New module used to handle profile history.

# Package: softcommerce/module-profile-queue

### Version 1.1.0
- **Enhancement**: Changes to queue functionality [#1]

### Version 1.0.7
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7

### Version 1.0.6
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1

### Version 1.0.5
- **Fix**: Applied a fix to composer.json license compatibility.

### Version 1.0.4
- **Compatibility**: Compatibility with Magento [OS/AC] 2.4.5 and PHP 8.

### Version 1.0.3
- **Fix**: Added a fix to updated_at timestamp.

### Version 1.0.2
- **Enhancement**: Added ability to specify batch size, when adding entries to queue.

### Version 1.0.1
- **Compatibility**: Compatibility with Magento Extension Quality Program (EQP).

### Version 1.0.0
- **Feature**: New module to handle profile queue entity.

# Package: softcommerce/module-profile-schedule

### Version 1.3.5
- **Fix**: Fix onetime schedule cache identifier [#3]

### Version 1.3.4
- **Feature**: Introduce onetime schedule to run at specified times as part of cron job process. [#2]

### Version 1.3.3
- **Fix**: No callbacks found for cron job plenty_customer_export. [#1]

### Version 1.3.2
- **Compatibility**: Add compatibility for Magento 2.4.6-p3 and Magento 2.4.7

### Version 1.3.1
- **Compatibility**: Add compatibility for PHP 8.2 and Magento 2.4.6-p1

### Version 1.3.0
- **Fix**: Applied a fix to composer.json license compatibility.

### Version 1.2.9
- **Enhancement**: Moved mass status action for schedules from `SoftCommerce_Profile` to `SoftCommerce_ProfileSchedule`

### Version 1.2.8
- **Compatibility**: Compatibility with Magento [OS/AC] 2.4.5 and PHP 8.

### Version 1.2.7
- **Enhancement**: Added profile type ID filter to cron_schedule collection.

### Version 1.2.6
- **Enhancement**: Improvements to ACL rules.

### Version 1.2.5
- **Compatibility**: Compatibility with Magento Extension Quality Program (EQP).

### Version 1.2.4
- **Enhancement**: Allow inactive schedule process in order to collect profile data. Move `active/inactive` condition to each profile instead.

### Version 1.2.3
- **Enhancement**: Changes to PDT.

### Version 1.2.2
- **Improvement**: [M2P-4] Re-initialise config cache after saving new schedule cron task.

### Version 1.2.1
- **Compatibility**: JS Modal: IE9 break script loading and avoid execution on iframe [#5]

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.4 [#4]

### Version 1.1.0
- **Compatibility**: Compatibility with Magento Open Source 2.4.3 [#2]
- **Enhancement**: Integration Tests [#1]

### Version 1.0.2
- **Compatibility**: JS backward compatibility for script rendering 2.3.5 - 2.4.2

### Version 1.0.1
- **Compatibility**: Compatibility with Magento Open Source 2.3.5 - 2.4.2 [#6]

### Version 1.0.0
- **Feature**: [SCP-4] New schedule module used to handle profile schedules.
