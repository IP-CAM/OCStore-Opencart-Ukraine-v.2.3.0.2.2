# OcStore 2 change log

## v2.3.0.2.2 (21/03/2017)
#### Fixed:
* Fixed bug with SessionHandler
* Fixed pagination error in file manager with a large number of images
* Fixed a bug with the name of the administrator in the admin panel
* Fixed bug with downloading sms library
* Translation correction

#### Changed:
* OCMOD sample with date sorting

#### Added:
* Payment module for Fondy. VISA / MC payments for individuals in Ukraine, Russia and the EU
* Add multilingual accounting to the manufacturer's name when creating / deleting a language

## v2.3.0.2.1 (20.02.2017)
#### Fixed
* Fixed bugs in the Yandex.Cashier payment module
* Fixed a bug in the Payeer payment module
* Fixed translation flaws
* Fixed category filter in admin
* Fixed a bug where the image was missing from the product
* Fixed file name search error in image manager
* Fixed Fraud protection error in order
* Return the missing search field by model in the list of products in the admin
* Removed inactive pagination from the list of categories in the admin
* Bug fixes in track_no-oc2.3.x.ocmod.xml
* Adjusted SSL verification on different hosts
* Correction of the values ​​of the incremental counter banner_image_id in the table oc_banner_image when filling with demo data
* Fixed a bug in arbitrary fields of the buyer
* Fixed a bug when installing and uninstalling control panel add-ons
* Fixed bug pagination of goods
* Fixed category search errors with CNC and Seo Pro enabled 

#### Changed
* When accessing the add-on, the modules will now be displayed by default

#### Updated
* Updated payment module W1
* Updated Unisender API to work with HTTPS

## v2.3.0.2 (22-11-16)
#### Fixed

* Fixed translation flaws
* Fixed sorting options in admin panel
* Fixed google recaptcha error when placing an order without registration and in the product card, added a change in the localization of the captcha when changing the language
* Fixed bug of not updating the order list page in case of order deletion.
* Fixed incorrect output of the og: image meta tag on the pages of categories, manufacturers and product cards.
* Fixed a bug in the mini-cart when buying on the product page
* Fixed a bug in the mailing list when using the SummerNote editor
* Fixed file manager
* Fixed a bug when removing the banner
* Fixed feedback form
* Fixed a bug with the output of the picture-stub when displaying options
* Fixed an error in displaying the main image of the product in its absence
* Fixed a bug when installing add-ons
* Fixed validation in system settings
* Fixing errors related to multilingualism in the template
* Fixed regions for Ukraine
* Added SSL certificate verification in catalog / controller / startup / startup.php
* Fixed a bug in the method of payment "Receipt of savings bank"
* Fixed a bug with localization in admin / controller / event / compatibility.php

#### Changed:

* For better usability, in the admin panel in the list of products filters of categories and models have changed places.
Minor visual change of the menu and the list of categories in the admin panel.

## V2.1.0.1.1 Ukrainian version (11.01.2016)
#### Fixed
* Fixed error adding manufacturer
* Fixed a bug when creating banners
* Corrections of incorrect translation
* Eliminate errors when sending mailings
* Fixed an issue with third-party modules that knew nothing about CKEditor in ocStore, if CKEditor was selected as the default editor.
* Correction of the title in the articles
* Correction of errors with the choice of manufacturer when editing the product
* Restore the delivery module
* Fixed minor bugs

#### Changed
* In the main category, you can select a category from all categories
* Removal of extra zeros in LxWxH and other places

#### Added
* Filter by category on the list of products in the admin
* Added Ukrainian language pack

## V2.1.0.1 (16-10-15)
#### Fixed
* Fixed pagination (removed the first page duplicate, removed the duplication of the target) (https://github.com/myopencart/ocStore/commit/000464351be6bdceb1e7f6d1c312920430ac909b)

#### Changed
* The logo on the main page contains a link to itself (https://github.com/myopencart/ocStore/commit/000464351be6bdceb1e7f6d1c312920430ac909b)
* Fixed pagination (removed the first page duplicate, removed the duplication of the target) (https://github.com/myopencart/ocStore/commit/000464351be6bdceb1e7f6d1c312920430ac909b)
* Hidden Google Apps due to duplication of functionality (https://github.com/myopencart/ocStore/commit/8c69328587afed7314ccc16be2dd6c33825a97aa)
* Changed the organization of the output of categories in the admin (https://github.com/myopencart/ocStore/commit/ce3a87686f409bc27afbba93066948ab73ae66b2)
* Changed service for obtaining information about the IP address of customers from www.geoiptool.com to ipgeobase.ru
* In the order list, the edit button becomes inactive if there is no allowed IP in the API

#### Added
* Added Russian language pack
* Localization of the database (schemes, statuses, returns)
* Added multilingual calendar
* Added CKEditor editor, now you can choose an editor (https://github.com/myopencart/ocStore/commit/12133094f78ef255e8c54e284492514581e3fde9)
* Added multilingual editor summernote (https://github.com/myopencart/ocStore/commit/a3c9fc8ae3a276f3bc35b4a870051c05ac265141)
* Qiwi payment module (https://github.com/myopencart/ocStore/commit/6f3c823144f5177465c8392c4664444b8daf53e3)
* Module for creating mailings via the Unisender service (https://github.com/myopencart/ocStore/commit/6008dbe82466afd80fb9e461d705aa7442ef7403)
* Delivery module - delivery depending on the amount of the order (https://github.com/myopencart/ocStore/commit/94cdb34c5e6cc5ae16527d084044e7490f8579fc)
* Ability to enter a regular expression for email validation (https://github.com/myopencart/ocStore/commit/614b8ea91d0820835c5e8839542ae41bce754ce5) (https://github.com/myopencart/ocStore/commit0eff)
* Adding meta tags og: url, og: image, og: type, og: title (https://github.com/myopencart/ocStore/commit/000464351be6bdceb1e7f6d1c312920430ac909b)
* Adding a robots.txt file (https://github.com/myopencart/ocStore/commit/000464351be6bdceb1e7f6d1c312920430ac909b)
* Added title and h1 for products (https://github.com/myopencart/ocStore/commit/1fcdc182c0ec079a73ca97ac9bdb685cdbdab089)
* Added title and h1 for categories (https://github.com/myopencart/ocStore/commit/a653a171e03e111a423b4ddcec65607bacb49291)
* Title, h1, meta keywords and meta description have been added for articles; (https://github.com/myopencart/ocStore/commit/b01352a7e52f3faab7155a903a77576a75138cce)
* Multilingual names, title, h1, meta keywords, meta description and description have been added for manufacturers; (https://github.com/myopencart/ocStore/commit/6f3da8c5d059a08fb3ea07fd1dc3f555a6a24cbb)
* The added alternative method of CNC generation eliminates the formation of different links for one page; (https://github.com/myopencart/ocStore/commit/2bbb96c5ec2fd09821cf33c6b19e70ffb8fd303f) (https://github.com/myopencart/ocStore/commit/1bec354689300dfbd2dcf024)
* Added url alias for base pages
* Added SeoPro
* Додана відправка SMS повідомлень
* Додано корисні інструменти від OC Team (https://github.com/myopencart/ocStore/commit/6ad5ef1f9b33727e9d27ca16142036400770787f)
* Додана можливість видалення кеша системи і зображень
* Додано можливість приховування не часто використовуваних полів через настройки магазину (MPN, ISBN, JAN і т.д.) (https://github.com/myopencart/ocStore/commit/ae421d72af8545a9e7194cbe43c84330950f84e7)
* Додана можливість приховування що не використовуються модулів, методів оплат і доставок (https://github.com/myopencart/ocStore/commit/36a616f3cc613dcb4fd491772c41f7966cd0ea22)
* Added sending SMS messages
* Added useful tools from OC Team (https://github.com/myopencart/ocStore/commit/6ad5ef1f9b33727e9d27ca16142036400770787f)
* Added the ability to delete the system cache and images
* Added the ability to hide unused fields due to store settings (MPN, ISBN, JAN, etc.) (https://github.com/myopencart/ocStore/commit/ae421d72af8545a9e7194cbe43c84330950f84e7)
* Added the ability to hide unused modules, payment methods and delivery (https://github.com/myopencart/ocStore/commit/36a616f3cc613dcb4fd491772c41f7966cd0ea22) 
