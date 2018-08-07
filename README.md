# om-vignarajaya-namaha
Riding the [pwa](https://developers.google.com/web/progressive-web-apps)-ve...

Checkout the live preview at https://bit.ly/2LYSWER
... on your phone.

## Setup and Installation
1. Clone the repository. 
2. Make sure a recent version of [nodejs](https://nodejs.org) is installed. 
3. Then run,

```
npm install -g firebase-tools
```

This will install firebase tools. 

Now you can use following commands (from the om-vignarajaya-namaha directory):
* `firebase serve` - serve the site locally
* `firebase deploy` - deploy to firebase. This requires the user to be authenticated to firebase. If you intend to develop on top of this see [extending](#extending)
* `firebase login` - authenticate to firebase server

## Extending

As soon as you clone/ fork the repository, change the firebase config information in `src/index.html` to match your project configuration. Check out [the docs](https://firebase.google.com/docs/web/setup) on obtaining this information.

After updating that information to reflect credentials of your firebase project, use `firebase deploy` or `firebase serve` to run the application.
