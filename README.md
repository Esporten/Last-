<!DOCTYPE html>
<html lang="en">
<head>
  <title>Firebase Login</title>
  <script src="https://www.gstatic.com/firebasejs/10.3.1/firebase-app.js"></script>
  <script src="https://www.gstatic.com/firebasejs/10.3.1/firebase-auth.js"></script>
  <script>
    const firebaseConfig = {
      apiKey: "AIzaSyBAK5GCJrOQkPmQtq6vbnI0yDBAhCh39-M",
      authDomain: "esporten-accda.firebaseapp.com",
      projectId: "esporten-accda",
      storageBucket: "esporten-accda.appspot.com",
      messagingSenderId: "1078999099184",
      appId: "1:1078999099184:web:0f696f591aff630f9e4af5"
    };
    const app = firebase.initializeApp(firebaseConfig);
    const auth = firebase.auth();
  </script>
</head>
<body>
  <h1>Firebase is connected!</h1>
</body>
</html>
