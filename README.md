# Check-In-Project
A worker check-in at soldier field that shows employees where their stand is, and allows for our coordinators to have an all-in-one and easy to use website that allows for planning and on premise reports 

<script type="module">
  // Import the functions you need from the SDKs you need
  import { initializeApp } from "https://www.gstatic.com/firebasejs/10.8.0/firebase-app.js";
  import { getAnalytics } from "https://www.gstatic.com/firebasejs/10.8.0/firebase-analytics.js";
  // TODO: Add SDKs for Firebase products that you want to use
  // https://firebase.google.com/docs/web/setup#available-libraries

  // Your web app's Firebase configuration
  // For Firebase JS SDK v7.20.0 and later, measurementId is optional
  const firebaseConfig = {
    apiKey: "AIzaSyAE6-CRnUaAIc5Aw7EC-xsKYA6fsz4mvtw",
    authDomain: "sf-employee.firebaseapp.com",
    projectId: "sf-employee",
    storageBucket: "sf-employee.appspot.com",
    messagingSenderId: "603118537492",
    appId: "1:603118537492:web:e2675b97d0d727070a1001",
    measurementId: "G-P8J3MN4XLV"
  };
download npm
  npm install -g firebase-tools

  firebase login

  firebase init

  firebase deploy
  // Initialize Firebase
  const app = initializeApp(firebaseConfig);
  const analytics = getAnalytics(app);
</script>
