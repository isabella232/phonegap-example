PhoneGap example using the [Evernote SDK for JavaScript](https://github.com/evernote/evernote-sdk-js)
========================================================

You can find the Evernote SDK for JavaScript [here](https://github.com/evernote/evernote-sdk-js).

Required reading
----------------
Please check out the [Evernote Developers portal page](http://dev.evernote.com/documentation/cloud/).
Please see the Getting Started With iOS for PhoneGap guide [here](http://docs.phonegap.com/en/2.4.0/guide_getting-started_ios_index.md.html#Getting%20Started%20with%20iOS).


How to use
----------

1. In your index.js file, inside the scope of the 'app' object, make the following changes :

    consumerKey : 'your consumer key',
    consumerSecret : 'your consumer secret',

2. Run the app and go through the OAuth flow.

3. See the logs for the results of the API calls.

More information
----------------

1. We are using jsOAuth for OAuth which can be found [here](http://cloud.github.com/downloads/bytespider/jsOAuth/jsOAuth-1.3.6.min.js).
2. You can use the HTML/js code on any other platform supported by PhoneGap.
3. Make sure you hide your consumer secret.
4. This example requires the latest version of XCode.
5. Most of the relevant code lives in www/js/index.js. 
