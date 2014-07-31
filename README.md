PP-JS-Bridge
=========

PP-JS-Bridge contains example files for implementing the Java Script bridge that interfaces with the PayPal consumer app. 


Version
----
1.0

Installation 
------------

1. Include ppbridge.js and core.js in your HTML template 
2. Call interfaces as mentioned below. 

Note: Do not alter ppbridge.js. core.js can be modified to fit the enhanced checkin experience 

Example Screenshots
--------------------
http://covafeas.clarify-it.com/d/dql4xn


Interfaces 
-----------
Enable Back Button - PayPalApp.call("MerchantTitleBarBackToPP");

Disable Back Button - PayPalApp.call("MerchantTitleBarDisabledBack");

Dismiss Web View - PayPalApp.call({func:"DismissWebView"});


Questions 
----
covafeas@paypal.com 
