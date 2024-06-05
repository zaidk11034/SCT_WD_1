<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Navigation Menu</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <nav class="navbar">
        <ul class="nav-menu">
            <li class="nav-item"><a href="landingPage.html" class="nav-link"><img src="homeE.png" alt="HomeLogo" height="30px" width="30px">Home</a></li>
            <li class="nav-item"><a href="about.html" class="nav-link"><img src="about.png" alt="AboutLogo" height="30px" width="30px">About</a></li>
            <li class="nav-item"><a href="service.html" class="nav-link"><img src="service.png" alt="serviceLogo" height="30px" width="30px">Services</a></li>
            <li class="nav-item"><a href="contact.html" class="nav-link"><img src="contact.png" alt="contactLogo" height="30px" width="30px">Contact</a></li>
        </ul>
    </nav>

    
    <div class="container">
        <form action="/action_page.php">
          <div class="row">
            <h2 style="text-align:center">Login with Social Media or Manually</h2>
            <div class="vl">
              <span class="vl-innertext">or</span>
            </div>
      
            <div class="col">
              <a href="#" class="fb btn">
                <i class="fa fa-facebook fa-fw"></i> Login with Facebook
              </a>
              <a href="#" class="twitter btn">
                <i class="fa fa-twitter fa-fw"></i> Login with Twitter
              </a>
              <a href="#" class="google btn">
                <i class="fa fa-google fa-fw"></i> Login with Google+
              </a>
            </div>
      
            <div class="col">
              <div class="hide-md-lg">
                <p>Or sign in manually:</p>
              </div>
      
              <input type="text" name="username" placeholder="Username" required>
              <input type="password" name="password" placeholder="Password" required>
              <input type="submit" value="Login">
            </div>
      
          </div>
        </form>
      </div>
      
      <div class="bottom-container">
        <div class="row">
          <div class="col">
            <a href="#" style="color:white" class="btn">Sign up</a>
          </div>
          <div class="col">
            <a href="#" style="color:white" class="btn">Forgot password?</a>
          </div>
        </div>
      </div>

    <script src="script.js"></script>
</body>
</html>


