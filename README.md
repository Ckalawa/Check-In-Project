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
    apiKey: "AIzaSyC4MPayJxGeAdbdXiSJmo4lN074aTCv5Ag",
    authDomain: "sf-check-in.firebaseapp.com",
    projectId: "sf-check-in",
    storageBucket: "sf-check-in.appspot.com",
    messagingSenderId: "229267091454",
    appId: "1:229267091454:web:be573d29acd89e5e951aaf",
    measurementId: "G-KZK1CMR29N"
  };

  // Initialize Firebase
  const app = initializeApp(firebaseConfig);
  const analytics = getAnalytics(app);
  </script>