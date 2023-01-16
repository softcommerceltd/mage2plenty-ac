## Changelog

### Version 1.2.1
- **Enhancement**: Added json content renderer to UI listing columns component.
- **Fix**: [#1] Applied a fix to product import `yes/no` attribute where value `0` couldn't be imported due to incorrect validation.
- **Enhancement**: Converted private method to public: `\SoftCommerce\PlentyOrderProfile\Model\OrderExportService\Generator\Order\Items\Item::getPlentyVariationId()`
  in order to allow interception by other modules.

### Version 1.2.0
- **Compatibility**: Compatibility with Magento Open Source 2.3.5 - 2.4.2
