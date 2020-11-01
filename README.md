It is front-end for [flaskchat](https://github.com/sanket7783/flaskChat). Its a telegram bot which connect with this screen and conversations are thrown on the screen by querying the firestore.
This app uses firestore for creating a chat application. Its a database in google cloud which support NoSQL.
Here is the quickstart guide for [firestore](https://firebase.google.com/docs/firestore/quickstart)
Steps to create this app:
1. Need to create a firestore app for storing and fetching the data. <strong>Quickstart</strong> can be help to create one. 
2. Use the config creds in the App.js to initialize app. Configs needed are:
  ```
  apiKey,authDomain,databaseURL,projectId,storageBucket,messagingSenderId,appId 
  ```
  
3. Once done can run <i>npm install</i> to install the dependencies.
4. Finally run <i>npm start</i> to start the app.
5. App will ask to login with google account if not already.
