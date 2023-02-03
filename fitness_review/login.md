<head>
    <style>
      h1 {
        color: lightblue;
      }
      input[type="text"], input[type="password"], input[type="email"] {
        color: lightblue;
      }
    </style>

<div id="login-form" style="text-align: center;">
  <h1>Welcome to DEJMO Fitness</h1>
  <div style="display: flex; justify-content: center;">
    <div class="form-group">
      <label for="email" style="color: lightblue;">Email:</label>
      <input type="email" id="email" name="email" style="width: 200px; height: 30px; padding:5px; margin:5px; color: lightblue;" required>
    </div>
    <div class="form-group">
      <label for="password" style="color: lightblue;">Password:</label>
      <input type="password" id="password" name="password" style="width: 200px; height: 30px; padding:5px; margin:5px; color: darkblue;" required>
    </div>
  </div>
  <div style="display: flex; justify-content: center; margin-top:10px;">
    <button type="submit" style="width: 80px; height: 30px; padding:5px; margin:5px;">Login</button>
  </div>
  <p>Don't have an account? <a href="#" id="toggle-register" style="color: darkblue;">Register here</a></p>
</div>

<div id="register-form" style="display: none;">
  <h1>Register</h1>
  <div class="form-group">
    <label for="name" style="color: darkblue;">Name:</label>
    <input type="text" id="name" name="name" style="width: 200px; height: 30px; padding:5px; margin:5px; color: darkblue;" required>
  </div>
  <div class="form-group">
    <label for="email" style="color: darkblue;">Email:</label>
    <input type="email" id="email" name="email" style="width: 200px; height: 30px; padding:5px; margin:5px; color: darkblue;" required>
  </div>
  <div class="form-group">
    <label for="password" style="color: darkblue;">Password:</label>
    <input type="password" id="password" name="password" style="width: 200px; height: 30px; padding:5px; margin:5px; color: darkblue;" required>
  </div>
  <div style="display: flex; justify-content: center; margin-top:10px;">
    <button type="submit" style="width: 80px; height: 30px; padding:5px; margin:5px;">Register</button>
  </div>
  <p>Already have an account? <a href="#" id="toggle-login" style="color: darkblue;
