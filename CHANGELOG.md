# Changelog

## 4.1.0
**Feature**

* New payment methods
    * Invoice with payment gurantee
    * Amazon Pay
* Allow quote as parameter in Payone_Core_Model_Payment_Method_Abstract
* Add functionality for recurring payment
* Improve the handling of external payment providers

**Bug**
* Set correct correct model for default mapping
* Correctly handle payment fee calculation
* Fixed default payment titles for giropay & idl
* Payone_Core_Model_Mapper_ApiRequest_Payment_Authorize_Abstract getCustomerIp() will no return the last ip like described in the comment
* Fix php notice because array key does not exist
* Payone_Core_Model_Observer_Sales_Order paymentPlaceEnd() will now validate if the user exists