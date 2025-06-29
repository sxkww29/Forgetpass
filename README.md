<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Facebook Login Mockup</title>
  <style>
    body {
      background: #f0f2f5;
      font-family: Arial, sans-serif;
      margin: 0;
    }
    .container {
      width: 100vw;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    .login-box {
      background: #fff;
      padding: 24px 28px 20px 28px;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      width: 350px;
    }
    .login-box h1 {
      color: #1877f2;
      font-size: 32px;
      margin-bottom: 12px;
      text-align: center;
      font-weight: bold;
      letter-spacing: -1px;
    }
    .login-box form {
      display: flex;
      flex-direction: column;
      gap: 12px;
    }
    .login-box input[type="text"],
    .login-box input[type="password"] {
      padding: 12px;
      border: 1px solid #dddfe2;
      border-radius: 6px;
      font-size: 16px;
    }
    .login-box button {
      background: #1877f2;
      color: #fff;
      border: none;
      border-radius: 6px;
      padding: 12px 0;
      font-size: 18px;
      font-weight: bold;
      cursor: pointer;
      margin-top: 6px;
    }
    .login-box .forgot {
      color: #1877f2;
      text-align: center;
      margin-top: 10px;
      font-size: 14px;
      text-decoration: none;
      display: block;
    }
    .login-box hr {
      margin: 18px 0;
      border: none;
      border-top: 1px solid #dddfe2;
    }
    .login-box .create-account {
      background: #42b72a;
      color: #fff;
      border: none;
      border-radius: 6px;
      padding: 12px 0;
      font-size: 16px;
      font-weight: bold;
      cursor: pointer;
      margin-top: 6px;
      width: 100%;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="login-box">
      <h1>facebook</h1>
      <form>
        <input type="text" placeholder="Email or phone number" required>
        <input type="password" placeholder="Password" required>
        <button type="submit">Log In</button>
      </form>
      <a href="#" class="forgot">Forgotten password?</a>
      <hr>
      <button class="create-account">Create New Account</button>
    </div>
  </div>
</body>
</html>
