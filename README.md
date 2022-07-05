# BkashPayment Extension
An extension to make bKash merchant payment from your android application. Just import the extension and setup your credentials.

<img src="https://github.com/jewelshkjony/BkashPayment/blob/main/images/bkash_payment_logo.png?raw=true"/>

Bkash payment gateway integration in android with PHP web server.

Keep API file on your hosting & change the credential.

Open bKash merchant account: https://www.bkash.com/bn/i-want-register/send-registration-request

### How to setup extension with credentials?
1. Download PHP files and upload on your hosting. File link -> https://github.com/jewelshkjony/BkashPayment/blob/main/BkashApiFile.zip
2. Set the payment.php file link as HostLink on extension block. Example: https://www.hosting.com/api/payment.php
> <img src="https://github.com/jewelshkjony/BkashPayment/blob/main/images/HostLink.png?raw=true"/>
3. Edit and change config_live.php file from hosting with your merchant account credentials.
4. Now set the amount to start payment flow. A popup bKash payment flow will be open.
> <img src="https://github.com/jewelshkjony/BkashPayment/blob/main/images/Payment.png?raw=true"/>
5. PageStarted means the webview is starting the payment flow.
> <img src="https://github.com/jewelshkjony/BkashPayment/blob/main/images/Page-Started.png?raw=true"/>
6. PageFinished means the webview is finished it's loading.
> <img src="https://github.com/jewelshkjony/BkashPayment/blob/main/images/Page-Finished.png?raw=true"/>
7. PaymentSuccess means the payment process is completed. Also it's return payment id, transaction id, amount and json response as string.
> <img src="https://github.com/jewelshkjony/BkashPayment/blob/main/images/Payment-Success.png?raw=true"/>
8. PaymentError means the extension got any error. It's return the error reason as string.
> <img src="https://github.com/jewelshkjony/BkashPayment/blob/main/images/Payment-Error.png?raw=true"/>

### Extension specifications:
com.jewel.bkashpayment (295.0 kb)\
Version: 1.0.1-beta\
Price: $25 USD (2000 Taka only for Bangladeshi)\
Last amendment: 07 July 2022\
Supported builder: Kodular, Niotron, App Inventor and it's other distributions.
  
#### Learn more details: https://developer.bka.sh/

### Contact with me ---------------------
1. Facebook: https://fb.com/jewelshkjony/
2. Telegram: https://t.me/jewelshkjony/
3. WhatsApp: https://wa.me/8801775668913/
4. Messenger: https://m.me/jewelshkjony/
