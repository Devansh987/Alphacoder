# 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zenzone: Where Beauty meet peace</title>
    <link href="Login.css" rel="stylesheet">
    <link rel="icon" href="zenzonelogo.png">
    <script src="Login.js"></script>
</head>
<body >
    <div class = "holder">
        <span class = "heading">
            
            <img id="img"src = "zenzonelogo.png" alt = "Zenzone logo">
            <h1>Zenzone</h1>
            <!-- <p>Where Beauty meet peace</p> -->
        </span>

        <div class ="Login-form">
            <h2>Welcome Back</h2>
            <p >Please log in to Book your appointment</p>

            <form action ="#">
                <label for = email>Email</label>
                <input type="email" id="email" name = "email" placeholder="Enter your email Address"  >

                <label for="password">Password</label>
                <input type="password" id = "password" name = "password" placeholder="Enter your password" >
                <a href="#">Forgot Password?</a>
                <a href="#">Create Account</a>
                <button type="submit">Log in</button>
                <button type="button" class = "guest button" onclick="window.location.href='Homepage.html'">Continue as guest</button>

         </form>
    </div>
    </div>
</body>
</html>
