Sri Lanka Dialog eZ Cash internet payment gateway for Opencart 2
================================================================

This is fully working solution for Sri Lanka Dialog ez Cash payment gateway
integration.

 

Instructions
------------

Just upload the contents in the upload directory. And install the payment
gateway through the admin interface.

If you are not clear then follow these instructions to upload and install.

1. upload opencart_ezcash_ipg-master\upload\admin\controller\extension\payment\ez_cash.php file into 
<your open cart installation>/admin/controller/extension/payment/ez_cash.php 

eg: https://files.000webhost.com/public_html/admin/controller/extension/payment/ez_cash.php 


2. upload opencart_ezcash_ipg-master\upload\admin\language\en-gb\extension\payment\ez_cash.php file into

 <your open cart installation>/admin/language/en-gb/extension/payment/ez_cash.php

...

same way upload the files inside model,view folders into your open cart installation.

once you completed the files in admin folder then you need to upload the files inside catalog folder also.
They need to be uploaded to  <your open cart installation>/catalog....

eg: https://files.000webhost.com/public_html/catalog/controller/extension/payment/ez_cash.php 


After that Go to your admin panel and on the left menu click Extensions>Extensions and select the Payments from the "Choose the extension type Drop" down menu.
Now the ez Cash should be listed in the Payments list. Now you can click Install button and then edit button to enable.

 

Test Mode
---------

You can test this with the dialog TESTMERCHANT. Put the mode to “Test”.

 

Live Mode
---------

After successfully registration as Dialog merchant paste the private key in the
“Private Key” field.

Put the mode to “Live”

That is it...!!!

 

For detailed checkout failure messages
--------------------------------------

Upload the contents in the “extra” folder for showing error message received
from the Dialog payment gateway when there is a transaction failure.

 

Enjoy... :)

 

### Support

Feel free to contact me for any support.

Email: induwarabas@gmail.com

Stackoverflow:
[http://stackoverflow.com/questions/38924112/](http://stackoverflow.com/questions/38924112/sri-lanka-dialog-ez-cash-payment-gateway-for-opencart-2)

 

### Note:

Your generated private key is a single lined key. You need to format the private
key as follows (64 character length lines and BEGIN/END tags.

 

\-----BEGIN PRIVATE KEY-----

RIIDdgIBADANBgkqhkiR9w0BAQEFAASCAmAwggJcAgEAAoGBAJuIUgSzNuWm3US8

ioyuSf/CSotPIC7YyNEnr+TK2Yt0N/EWzqNXoOCDxDTgoWLQxM3Nfr65tWtV2097

0brZr/5cMSPue9f0IwUrEhka1gLlW4uQon6QjQem4TWQ8anoMKYwfYgRnCGQsbrT

KwOApwTA4Bt6dg9jKXlIE6rXqqO6g2C/uD+G2p+W4k0ZI1isuqqjjkup5ZPkNaeW

R9/961Qx3CyrWDk6n0OkzDJ6UNzLAgMBAAECgYEAh+/dv73jfVUaj7l4lZct+2MY

BfWEtlXWvN1V051KnKaOqE8TOkGK0PVWcc6P0JhPrbmOu9hhAN3dMu+jd7ABFKgC

kA8grt7yvNGoP8j0xBLsxE7ltzkgClARBoBot9f4rUg0b3j0vWF59ZAbSDRpxJ2U

4b8EIlHA8bl8po8gwAECQQDliMBTAzzyhB55FMW/pVGq9TBo2oXQsyNOjEO+rZNJ

zIwJzFrFhvuvFj7/7FekDAKmWgqpuOIk0NSYfHCR54FLAkEArXc7pdPgn386ikOc

Nn3Eils1WuP5+evoZw01he4NSZ1uXNkoNTAk8OmPJPz3PrtB6l3DUh1U/DEZjIiI

7z5igQJAFXvFNH/bFn/TMlYFZDie+jdUvpultrE9nr52IMSyQngIq2obHN3TdMHK

jriUPNIAwnnHBgp0OXHMCHkSYX4AHpLr1cWjARw9IKB1lBmF7+YFgQJAFqUgYj11

R73hPhN5tAQ9d0E8uWFqZJNRHfbjHQJASY7pNV3Ov/QE0ALxqE3W3VDmJD/OjkOS

BjCbFfbui/IyUw==

\-----END PRIVATE KEY-----
