Commerce Alipay
===============

Implements [Alipay](http://www.alipay.com) payment services for use with
[Drupal Commerce](http://drupal.org/project/commerce).


Features
--------
Currently supports the following Alipay service types:
- Direct Pay (tested and supported)

More work and testing to be done on:
- Escrow Pay
@TODO: [Commerce Delivery](http://drupal.org/project/commerce)
- Dual Function
- Send Goods Confirm

Module currently supports "Direct Pay" service account types.
Other service types could be supported to some extent with some customization
through the hook_commerce_alipay_parameter_alter (see API document).

Debug module:
It is possible to active a debugging mode, to override all transactions to a
total of 0.01 CNY, which is very useful for testing everything has been
correctly setup and ensuring payments could effectively be received.


Useful Resources
----------------
For any questions and problems, you may find some help on the Alipay official site:
1 - Merchant Help Center:
https://b.alipay.com/support/helperApply.htm?action=consultationApply
Apply for integration consultation, and you could expect a professional
technician to contact you.
2 - User Help Center:
http://help.alipay.com/support/232511-16307/0-16307.htm?sh=Y&info_type=9
3 - Alipay Forum:
http://club.alipay.com/read-htm-tid-8681712.html


Bugs/Features/Patches
---------------------
If you want to report bugs, feature requests, or submit a patch, please do so
at the project page on the Drupal web site.
http://drupal.org/project/commerce_alipay


Contributions are welcome!!
---------------------------
Feel free to follow up in the issue queue for any contributions, 
bug reports, feature requests.
Tests, feedback or comments in general are highly appreciated.
