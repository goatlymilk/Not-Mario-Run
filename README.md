
<html><head>
    <title>geniushour</title> 
    <link rel="stylesheet" type="text/css" href="./pencilrevived.css">
    <link rel="stylesheet" type="text/css" href="./style.css">
  </head>
  <body>
    <nav>
      <h1>Website</h1>
      <a href="./login.html" id="loginbtn" value="Login"></a>
    </nav>
    <blockquote>
      <img src="https://avatars3.githubusercontent.com/u/49005044?s=400&amp;u=7ea503ce448424ede022d5c558c1158fe9d6a152&amp;v=4" height="50" width="50">
      <h1>Initial Post</h1>
      <h6>by <a href="./user/admin.html">Admin</a></h6>
      <p>HELLO WORLD, check out <a href="./user/admin2.html">admin2</a></p>
    </blockquote>
    <script>
      loginButton = document.getElementById("loginbtn");
      loggedIn = sessionStorage.getItem("logged-in);
      if (loggedIn == "True") {
        loginButton.href="";
        loginButton.addEventListener("click", function(){
          sessionStorage.setItem("logged-in", "False");
          sessionStorage.setItem("username", "");
          sessionStorage.setItem("password", "");
          location.reload()
        });
      }
    </script>

</body></html>
<head>
    <title>geniushour</title> 
    <link rel="stylesheet" type="text/css" href="./pencilrevived.css">
    <link rel="stylesheet" type="text/css" href="./style.css">
  </head>
