<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Box Cricket</title>
     <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
    <link rel="stylesheet" href="you.css">
</head>
<body>
    <header>
        <h2 class="logo">BCT</h2>
        <nav class="navigation">
            <a href="#" style="text-decoration:none;">Home</a>
            <a href="#" style="text-decoration:none;">Schedule</a>
            <a href="#" style="text-decoration:none;">Services</a>
            <a href="#" style="text-decoration:none;">About Us</a>
            <button class="btnLogin-popup">Login</button>
        </nav>
    </header>
    <div class="wrapper">
        <span class="icon-close">
            &#10006;
        </span>
        <div class="form-boxlogin">
            <h2>Login</h2>
            <form action="#">
                <div class="input-box">
                    <span class="icon">
                        <i class="fas fa-envelope"></i>
                    </span>
                    <input type="email"  id="email" style="color: rgb(252, 239, 239);" placeholder="" required>
                    <label for="email">Email</label>
                </div>
                <div class="input-box">
                    <span class="icon">
                        <i class="fas fa-lock"></i>
                    </span>
                    <input type="password"   id="password" placeholder="" required>
                    <label for="password">Password</label>
                </div>
                <div class="remember-forgot">
                    <label><input type="checkbox">Remember me</label>
                    <a href="#">Forgot Password?</a>
                </div>
                <button type="submit" class="btn">Login</button>
                <div class="login-register">
                    <p>Don't have an Account?
                        <a href="#" class="register-link">Register</a>
                    </p>
                </div>
            </form>
        </div>

<div class="form-boxregister">
            <h2>Registration</h2>
            <form action="#">
                <div class="input-box">
                    <span class="icon">
                        <i class="fa-solid fa-user"></i>
                    </span>
                    <input type="text" name="text" id="text" style="color: rgb(252, 239, 239);" placeholder="" required>
                    <label for="text">Username</label>
                </div>
                <div class="input-box">
                    <span class="icon">
                        <i class="fas fa-envelope"></i>
                    </span>
                    <input type="email" name="email" id="email" style="color: rgb(252, 239, 239);" placeholder="" required>
                    <label for="email">Email</label>
                </div>
                <div class="input-box">
                    <span class="icon">
                        <i class="fas fa-lock"></i>
                    </span>
                    <input type="password"  id="password" placeholder="" required>
                    <label for="password">Password</label>
                </div>
                <div class="remember-forgot">
                    <label><input type="checkbox">I agree to the Terms & Conditions</label>
                    
  </div>
                <button type="submit" class="btn">Register</button>
                <div class="login-register">
                    <p>Already have an Account?
                        <a href="#" class="login-link">Login</a>
                    </p>
                </div>
            </form>
        </div>
    </div>
    <script src="you.js"></script>
    <script type="module" src="http://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
    <script nomodule src="http://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>
</body>
</html>
