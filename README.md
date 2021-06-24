# Jack's React Native Starter

The react native starter I use for all client work and personal projects! Should work on expo and expo web :) This is based on the starter [here!](https://github.com/expo-community/expo-firebase-starter).


## Built with!

- Firebase
- Expo
- @Shopify/restyle
- Moti (for animations)
- Lotti 
- Expo Fonts


### Installation

1. Create a new project using the firebase starter template.
2. Rename the file `example.firebaseConfig.js` to `firebaseConfig.js`
3. Update `firebaseConfig.js` with your own configuration, e.g.:

```js
// Rename this file to "firebaseConfig.js" before use
// Replace all Xs with real Firebase API keys

export default {
  apiKey: 'XXXX',
  authDomain: 'XXXX',
  databaseURL: 'XXXX',
  projectId: 'XXXX',
  storageBucket: 'XXXX',
  messagingSenderId: 'XXXX',
  appId: 'XXXX'
};
```

4. Start the project:
  - `yarn ios` -- open on iOS
  - `yarn android` -- open on Android
