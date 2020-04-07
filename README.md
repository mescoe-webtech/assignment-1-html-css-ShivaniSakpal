# assignment-1-html-css-ShivaniSakpal
assignment-1-html-css-ShivaniSakpal created by GitHub Classroom
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="style.css">
    <title>Form - Signup</title>
</head>
<body>
    <header>
        <h2 class="logo">SIGNUP</h2>
        <nav>
        <ul class="nav-links">
            <li><a class="nav-link" href="index.html">Login</a></li>
            <li><a class="nav-link" href="signup.html">Signup</a></li>
        </ul>
        </nav>
    </header>
    <main>
        <div class="box-container">
            <form class="box-register">
                <h3>Registration Form</h3>
                <input type="text" placeholder="Enter Name" name="name" required><br>
                <input type="text" placeholder="Enter User Name" name="uname" required><br>
                <input type="text" placeholder="Enter Phone Number" name="pnum" required><br>
                <input type="email" placeholder="Enter Email Id" name="email" required><br>
                <label><b>Select Gender</b></label>
                <input type="radio" name="gender" value="male" checked><span>Male</span><br>
                <input type="radio" name="gender" value="female"><span>Female</span><br>
                <br>
                <label><b>Select Birthdate :</b></label><input type="date" name="bday">
                <br>
                <input type="text" placeholder="Enter Address" name="address"><br>
                <input type="password" placeholder="Enter Password" name="password" required><br>
                <button type="submit">Login</button>
            </form>
        </div>
    </main>
</body>
</html>
