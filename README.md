<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <!-- Include Ionic Icons -->
    <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
    <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>
    <style>
        /* Sample CSS for basic layout */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px 20px;
            background-color: #333;
            color: #fff;
        }
        .navbar ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
        }
        .navbar ul li {
            margin-left: 20px;
        }
        .navbar ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
        }
        .info {
            text-align: center;
            margin-top: 50px;
        }
        .info h1, .info h3 {
            margin: 10px;
            font-weight:normal ;
        }
        .info h4 {
            margin: 10px;
            font-weight:bolder;
            font-size: large;
            font-family: Arial, Helvetica, sans-serif;
        }
        .info ol{
            text-align: center;
            justify-content: center;
        }
        .info a {
            padding: 10px 20px;
            background-color: #333;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
        .image {
            text-align: center;
            margin-top: 20px;
        }
        .image img {
            max-width: 300px;
            border-radius: 50%;
        }

        .image img:hover{
            left: 55%;

        }
        .icons {
            text-align: center;
            margin-top: 20px;
        }
        .icons a {
            font-size: 30px;
            margin: 0 10px;
            color: #333;
            text-decoration: none;
        }
        .icons ion-icon:hover{
        color: blueviolet;
        }
    </style>
</head>
<body>
    <div class="main">
        <div class="navbar">
            <img src="my logo.png" alt="Logo" class="logo">
            <ul>
                <li><a href="#">HOME</a></li>
                <li><a href="#">ABOUT</a></li>
                <li><a href="#">SKILLS</a></li>
                <li><a href="#">MY WORK</a></li>
                <li><a href="#">CONTACT</a></li>
                <li><a href="#">PROGRAMMING LANGUAGES</a></li>
            </ul>
        </div>
        <div class="info">
            <h3>Hi, I'm <span>Reginald</span></h3>
            <h1>MECHANICAL ENGINEER AND WEB DEVELOPER</h1>
            <h2>ABOUT</h2>
            <h3>Aspiring Mechanical engineer, thrilled about opportunities and challenges that allow me to conceive and optimize technical solutions outside the boundaries of textbook application into the real world market.</h3>
            <br>
            <a href="#">Hire me</a>
        </div>
        <div class="image">
            <img src="WhatsApp Image 2024-09-13 at 7.40.22 PM (1).jpeg" alt="Photo" class="Photo">
        </div>
        <div class="icons">
            <a href="#"><ion-icon name="logo-facebook"></ion-icon></a>
            <a href="#"><ion-icon name="logo-instagram"></ion-icon></a>
            <a href="#"><ion-icon name="logo-twitter"></ion-icon></a>
        </div>
    </div>
</body>
</html>

      
