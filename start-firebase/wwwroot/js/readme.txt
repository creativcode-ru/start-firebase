Добавьте свой файл инициализации firebase-init.js - взять этот код из консоли firebase


// Initialize Firebase ()
var config = {
    apiKey: "...",
    authDomain: "....",
    databaseURL: "https://(...).firebaseio.com",
    projectId: "...",
    storageBucket: "(...).appspot.com",
    messagingSenderId: "..."
};
firebase.initializeApp(config);