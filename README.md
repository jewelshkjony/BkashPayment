# BkashPayment Extension
An extension to make bKash merchant payment from your android application. Just import the extension and setup your credentials.

### What is bKash?
**bKash** is a mobile financial service in Bangladesh. As a mobile financial service (MFS) provider in Bangladesh through bKash users can deposit money into their mobile accounts and then access a range of services, in particular transferring and receiving money domestically, making payments. Services like mobile recharge or paying utility bills. A user can receive money from overseas on bKash.

<img src="https://github.com/jewelshkjony/BkashPayment/blob/main/images/bkash_payment_gateway.png?raw=true"/>

Bkash payment gateway integration in android with PHP web server.

<img src="https://raw.githubusercontent.com/jewelshkjony/BkashPayment/main/images/bKash_Checkout.jpg"/>

Keep API file on your hosting & change the credential.

Open bKash merchant account: https://www.bkash.com/bn/i-want-register/send-registration-request

### How to setup extension with credentials?
1. Upload PHP files on your hosting. (You'll get this files with extension.)
2. Set the payment.php file link as HostLink on extension block. Example: https://www.hosting.com/api/payment.php
> <img src="https://github.com/jewelshkjony/BkashPayment/blob/main/images/HostLink.png?raw=true"/>
3. Edit and change config_live.php file from hosting with your merchant account credentials.
4. Now set the amount to start payment flow. A popup bKash payment flow will be open.
> <img src="https://github.com/jewelshkjony/BkashPayment/blob/main/images/Payment.png?raw=true"/>
5. PageStarted means the extension is starting the payment flow.
> <img src="https://github.com/jewelshkjony/BkashPayment/blob/main/images/Page-Started.png?raw=true"/>
6. PageFinished means the extension is finished it's loading.
> <img src="https://github.com/jewelshkjony/BkashPayment/blob/main/images/Page-Finished.png?raw=true"/>
7. PaymentSuccess means the payment process is completed. Also it's return payment id, transaction id, amount and json response as string.
> <img src="https://github.com/jewelshkjony/BkashPayment/blob/main/images/Payment-Success.png?raw=true"/>
8. PaymentError means the extension got any error. It's return the error reason as string.
> <img src="https://github.com/jewelshkjony/BkashPayment/blob/main/images/Payment-Error.png?raw=true"/>

## Extension specifications:
![image](https://user-images.githubusercontent.com/75406851/177278269-e83740d7-ff1d-4224-9da4-8afeb3034b86.png)\
<img src="https://raw.githubusercontent.com/jewelshkjony/ShakeDetector/main/app-inventor-aix-download-icon.png"/> <a href="https://community.appinventor.mit.edu/t/bkashpayment-extension-integrate-bkash-payment-flow-1-0-1-beta/61375">com.jewel.bkashpayment</a>(296 KB)\
Version: 1.0.1-beta\
Price: $25 USD (2000 Taka only for Bangladeshi)\
Last amendment: 07 July 2022\
Supported builder: Kodular, Niotron, App Inventor and it's other distributions.
  
#### Learn more details: https://developer.bka.sh/

## 📫 How to reach me: ...

<a href="https://t.me/jewelshkjony">Telegram</a> - <a href="https://wa.me/8801775668913">WhatsApp</a> - <a href="https://fb.com/jewelshkjony">Facebook</a> - <a href="https://m.me/jewelshkjony">Messenger</a>

## Payment Gateway
Use this phone number to pay me from Bangladesh.

````java
+8801775668913
````
Bangladeshi user can send money using bkash, Nagad and Rocket. Remember accounts are personal.


## License [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
    Copyright (c) 2022 Jewel Shikder Jony
    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.
