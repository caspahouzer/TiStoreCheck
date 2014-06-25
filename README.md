TiStoreCheck
============

# What?

With this library you are able to check for a new version of your app in the iOS App Store automatically

# Usage

    // require the module
    var store = require('lib/storecheck');

    // set app id
    var appId = '425218953'; // Feel free to download my app ;)

    // call update request method
    store.checkForAppUpdate(appId, function (version) {
        // see the example in the app.js
    }
