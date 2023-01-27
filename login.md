<head>
    <style>
      h1 {
        color: darkblue;
      }
    </style>


<div id="login-form" style="text-align: center;">
  <h1>Welcome to DEJMO Fitness</h1>
  <div style="display: flex; justify-content: center;">
    <div class="form-group">
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" style="width: 200px; height: 30px; padding:5px; margin:5px;" required>
    </div>
    <div class="form-group">
      <label for="password">Password:</label>
      <input type="password" id="password" name="password" style="width: 200px; height: 30px; padding:5px; margin:5px;" required>
    </div>
  </div>
  <div style="display: flex; justify-content: center; margin-top:10px;">
    <button type="submit" style="width: 80px; height: 30px; padding:5px; margin:5px;">Login</button>
  </div>
  <p>Don't have an account? <a href="#" id="toggle-register">Register here</a></p>
</div>

<div id="register-form" style="display: none;">
  <h1>Register</h1>
  <div class="form-group">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" style="width: 200px; height: 30px; padding:5px; margin:5px;" required>
  </div>
  <div class="form-group">
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" style="width: 200px; height: 30px; padding:5px; margin:5px;" required>
  </div>
  <div class="form-group">
    <label for="password">Password:</label>
    <input type="password" id="password" name="password" style="width: 200px; height: 30px; padding:5px; margin:5px;" required>
  </div>
  <div style="display: flex; justify-content: center; margin-top:10px;">
    <button type="submit" style="width: 80px; height: 30px; padding:5px; margin:5px;">Register</button>
  </div>
  <p>Already have an account? <a href="#" id="toggle-login">Login here</a></p>
</div>
