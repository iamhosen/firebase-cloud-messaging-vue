# Firebase cloud messaging 

This repository contains a simple starter kit for using Firebase Cloud Messaging in a Vue app.

<!-- ## Screenshots

![Weather App Screenshot](Screenshot.png) -->

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/iamhosen/firebase-cloud-messaging-vue

2. Navigate to the project directory:
   
   ```bash
   cd firebase-cloud-messaging-vue

3. Install dependencies

    ```bash
    npm install

4. Add your firebase project config to public/firebase-messaging-sw.js and /App.vue
    ```js
    /* /public/firebase-messaging-sw.js */
    firebase.initializeApp({
        apiKey: "",
        authDomain: "",
        projectId: "",
        storageBucket: "",
        messagingSenderId: "",
        appId: "",
    });

    /* /public/firebase-messaging-sw.js */
    const firebaseConfig = {
        apiKey: "",
        authDomain: "",
        projectId: "",
        storageBucket: "",
        messagingSenderId: "",
        appId: "",
    };

5. Add firebase FCM token to /App.vue
    ```js
    getToken(messaging, {
        vapidKey: "",
    })

6. Start the development server
   
    ```bash
    npm run dev

7. Open your browser and visit http://localhost:3000/ to view the app.

8. By clicking on 'Permission' button you will ask for  permission. by allow it you will get the device token on console.


## Credits

This Weather App is developed by Hossein Amirhosseini.

## License

This project is licensed under the [MIT License](LICENSE).