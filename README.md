# Magento Livechat Module

This module adds [Livechat](https://www.livechatinc.com/) to your Magento 2 site.

### Installation

* `composer require livechat/module-magento-livechat:dev-master`
* `php bin/magento module:enable Livechat_Livechat`
* `php bin/magento setup:upgrade`
* `php bin/magento setup:static-content:deploy`
* `php bin/magento cache:clean`

### Features

* Connecting existing Livechat account,
* Creating new Livechat account,
* Injecting Livechat JS snippet,
* Sending customers details to Livechat,
* Sending customers cart details to Livechat,
* Sending customers last order details to Livechat,
* Sending customers last order details to Livechat,
* Set-up [goal](https://www.livechatinc.com/kb/goals-set-up-and-use/) for order placed event.
