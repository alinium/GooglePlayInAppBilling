Google Play In-App Billing
======================

Android library to support Google Play In-App Billing API v3

This library is the `util` package from the `TrivialDrive` 
[sample app](http://developer.android.com/training/in-app-billing/preparing-iab-app.html#GetSample) 
with some custom modifications.

Proguard
--------
You might need this line if you are using ProGuard
  
    -keep class com.android.vending.billing.**

References
----------

- [In-App Billing Version 3](http://developer.android.com/google/play/billing/api.html)
- [TrivialDrive Sample Application](http://developer.android.com/training/in-app-billing/preparing-iab-app.html)

Tips
----
- [Help with testing purchases](http://stackoverflow.com/a/15821320/308757)
- [Developer Payload](http://stackoverflow.com/questions/15192184/what-to-use-as-the-developer-payload-in-google-in-app-billing-apis)
