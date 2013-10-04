fco-smartpay-skin
=================

Frontend styling of the Barclaycard smartpay system, currently only used by some FCO services.

Documentation for how to edit/update the skin used with FCO Smartpay payments can be found in the [SmartPay_SkinsGuide.pdf] provided by Barclaycard(https://github.com/alphagov/fco-smartpay-skin/blob/master/SmartPay_SkinsGuide.pdf).

The TL;DR version —
Brace yourself, this is not very nice to work with. I recommend tea + biscuits before you start and a deep breath...

* Make the edits you want to make in the skin folder (named with an ID like QM28ByLc)
* Zip up the folder
* [Login to Barclaycard Smartpay Backoffice](https://ca-test.barclaycardsmartpay.com/ca/ca/login.shtml).
* Go to Skins in the menu.
* Find the ID of the skin you want to edit (it should match the folder name in this repo).
* Click on the 90s floppy disk icon beneath 'Upload'
* Upload your zip.
* Scroll down and confirm once uploaded.
* To preview your changes, click the ID link, go to the 'Test' tab at the top of the page.
* Click Generate Payment Form
* Click Test Now!