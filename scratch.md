If you don't use build tools, use this option to add and use the Firebase JS SDK. Use this option to get started, but it's not recommended for production apps. Learn more.

Copy and paste these scripts into the bottom of your <body> tag, but before you use any Firebase services:

<script type="module">
  // Import the functions you need from the SDKs you need
  import { initializeApp } from "https://www.gstatic.com/firebasejs/10.14.0/firebase-app.js";
  // TODO: Add SDKs for Firebase products that you want to use
  // https://firebase.google.com/docs/web/setup#available-libraries

  // Your web app's Firebase configuration
  const firebaseConfig = {
    apiKey: "AIzaSyAS7DhfKt1OiILVNd6Hrj2zUGOA0Dr2Xaw",
    authDomain: "controllability-8d2a8.firebaseapp.com",
    projectId: "controllability-8d2a8",
    storageBucket: "controllability-8d2a8.appspot.com",
    messagingSenderId: "251098270739",
    appId: "1:251098270739:web:eacc7a47a139bcc12b83e6"
  };

  // Initialize Firebase
  const app = initializeApp(firebaseConfig);
</script>