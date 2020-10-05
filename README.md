# uk.co.vedaconsulting.worldpay
Payment Processor setup for Worldpay


INSTALLATION
------------
For CiviCRM 4.7 & up:
1)  Your CiviCRM 'Resource URLs' must be set to the extensions directory
    relative to Drupal/CRM base.  Refer https://docs.civicrm.org/sysadmin/en/latest/customize/extensions/ for more information

2)  Install extension via CiviCRM's "Manage Extensions" page.


COPY IPN FILE
-------------
To handle the Worldpay IPN please copy the IPN file from this extensions "./extern/worldPayNotify.php" to "../civicrm/extern/worldPayNotify.php"


CONFIGURATION
-------------

To setup a new payment processor, click on Administer > System Settings > Payment Processors, Add Payment Processor.

1) Set Payment Processor Type -> 'Worldpay'
2) Enter the Payment Processor name Example: "Worldpay"
3) Set Financial Account Example "Payment Processor Account"

For the Payment Processor Details (Live/Test Payments), you must provide Username which is worldpay api user id. and site URL should be "https://secure.worldpay.com/wcc/purchase"


