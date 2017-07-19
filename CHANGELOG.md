## 2.3.0 - 2017-07-19
* Remove CURLOPT_CAINFO - path to Certificate Authority (CA) bundle
* Remove paymill.crt
* Change user agent info to "Paymill-Prestashop/2.3.0"

## 2.2.0 - 2015-07-21
* add ssl support for the payment form page
* Integration of PayFrame to enable use of SAQ A for easier PCI DSS 3.0 compliance
* transaction description initially set

## 2.1.0 - 2014-10-01
* added compatibility for EU-Legal(https://github.com/EU-Legal/modules)
* added refund within shop-administration
* added capture within shop-administration
* added preauth/capture feature for manually capture

## 2.0.1 - 2014-09-09
* Changed register url and added referrer

## 2.0.0 - 2014-08-29
* Core-Release

## 1.5.1 - 2014-06-23
* improved Design for Prestashop 1.6
* Transaction description limited to 128 charakters
* disabled autocompletation for inputfields

## 1.5.0 - 2014-06-23
* adjust code to cover up prestashop-standards

## 1.4.0 - 2014-05-22
* add new configuration: active creditcard brands
    - Visa
	- MasterCard
	- American Express
	- CartaSi
	- Carte Bleue
	- Diners Club
	- JCB
	- Maestro
	- China UnionPay
	- Discover Card
	- Dankort
* The two payment forms ELV and SEPA were merged to one form. Therefor the option SEPA was removed from the configuration.
* added Prenotification for SEPA (Day of Debit will be shown on the invoice and on the order confirmation mail)

## 1.3.0 - 2014-04-04
* added support for Presta 1.6
* added support for mobile theme

## 1.2.0 - 2014-03-11
* added iban validation
* added improved creditcard predetection and improved validation
* added webhook - change orderstate when a order is refunded via paymillcockpit

## 1.1.0 - 2013-10-17
* Updated Lib
* Reuse a Client instead of creating a new one for each order
* Added Source to Lib
* Added Feature: Hide payment when keys are invalid
* Added Feature: Detect and show creditcardbrand when entering a creditcardnumber
* Fixed Bug: wrong orderstate after successful order
* Fixed Redirect on error

## 1.0.4 - 2013-08-25
* Added Currency-checkbox for payments
* Fixed Redirect Link

## 1.0.3 - 2013-03-27
* Added Option to enable Creditcard-payments
* Added Feature: FastCheckout - saves an Id refering to the customers paymentdata and prefills the data for the customer for a quicker checkout.

## 1.0.2 - 2013-03-21
* Improved paymentvalidation
* Improved 3DSecure-handling
* Fixed Bug: Modul is missing configuration

## 1.0.1 - 2013-03-14
* Added Feature: Backend-log

## 1.0.0 - 2013-03-14
* initial Version
