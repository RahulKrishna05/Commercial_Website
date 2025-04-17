# Ex02 Commercial Website
## Date: 17/04/2025

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
## HOME
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HOME PAGE</title>
</head>
<style type="text/css">
	.form {
		margin: 0 auto;
		width: 210px;
	}

	.form label{
		display: inline-block;
		text-align: right;
		float: left;
	}

	.form input{
		display: inline-block;
		text-align: left;
		float: right;
	}
</style>
<body style="background-image: url(vhome1.jpeg);background-size: 1500px;">
    <marquee behavior="" direction="right" style="color: burlywood;">WELCOME TO OUR SITE</marquee>
    <h1 style="text-align: center;color: aqua; padding: 50px;margin: auto; font-style:italic;">FRESHY SHOP</h1>
    <h2 style="text-align: center;color: aquamarine;">LOGIN / SIGN UP</h2>
    <br>
    <br>
    <form>
    <div class="form">
		<label style="color: aqua;">E-MAIL</label>
        <br>
		<input type="text" placeholder="Enter email">
        <br>
        <br>
		<label style="color: aqua;">PASSWORD</label>
		<input type="password" required>
        <br>
        <br>
		<nav>
			<a href="http://127.0.0.1:5500/prod.html" style="text-decoration: none; color:aqua;display: block;margin: 55px;"t target="_blank">LOGIN</a>
		</nav>
	</div>
    </form>
</body>
</html>
```
## PRODUCT
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PRODUCTS</title>
    <style>
        .container{
            margin: 20px;
            padding: 20px;
            border: 10px;
            display: flex;
            justify-content: center;
            flex-direction: row;
            flex-wrap: wrap;
            border: 10px solid black;}
        .box{
            margin: 10px;
            padding: 20px;
            font-size: larger;
            font-style: italic;
            border: 3px solid black;
        }

    </style>
</head>
<body>
    <h1 style="text-align: center;">PRODUCTS</h1>
    <header style="color: bisque;">
            <nav  style=" text-align:end;">
                <a href="http://127.0.0.1:5500/Fru.html" style="text-decoration: none; color: black; text-align: center; padding: 20px;">FRUITS </a>
                <a href="http://127.0.0.1:5500/cookies.html" style="text-decoration: none; color: black; text-align: center; padding: 08px;">COOKIES</a>
            </nav>
    </header>
    <div class="container">
        <div class="box"><img src="1insta.jpeg" alt="" height="200px" width="200px" ></div>
        <div class="box"><img src="2insta.jpeg" alt="" height="200px" width="200px" ></div>
        <div class="box"><img src="v3.jpeg" alt="" height="200px" width="200px" ></div>
        <div class="box"><img src="v4.jpeg" alt="" height="200px" width="200px" ></div>
        <div class="box"><img src="v5.jpeg" alt="" height="200px" width="200px" ></div>
    </div>
    <H3 style="text-align: center;color: green;font-style: italic;">FOR ORDERS CALL : 6587965412 ** E-mail:instamart@gmail.com</H3>
</body>
</html>
```
## FRUIT
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>fruits</title>
    <style>
        .container{
            margin: 20px;
            padding: 20px;
            border: 10px;
            display: flex;
            justify-content: center;
            flex-direction: row;
            flex-wrap: wrap;
            border: 10px solid black;}
        .box{
            margin: 10px;
            padding: 20px;
            font-size: larger;
            font-style: italic;
            border: 3px solid black;
        }

    </style>
</head>
<body>
    <h1 style="text-align: center;">PRODUCTS</h1>
    <header style="color: bisque;">
            <nav  style=" text-align:end;">
                <a href="http://127.0.0.1:5500/prod.html" style="text-decoration: none; color: black; text-align: center; padding: 20px;">VEGETABLE </a>
                <a href="http://127.0.0.1:5500/Fru.html" style="text-decoration: none; color: black; text-align: center; padding: 20px;">FRUITS </a>
                <a href="http://127.0.0.1:5500/cookies.html" style="text-decoration: none; color: black; text-align: center; padding: 08px;">COOKIES</a>
            </nav>
    </header>
    <div class="container">
        <div class="box"><img src="4insta.jpeg" alt="" height="200px" width="200px" ></div>
        <div class="box"><img src="6insta.jpeg" alt="" height="200px" width="200px" ></div>
        <div class="box"><img src="f3.jpeg" alt="" height="200px" width="200px" ></div>
        <div class="box"><img src="f4.jpeg" alt="" height="200px" width="200px" ></div>
        <div class="box"><img src="f5.jpeg" alt="" height="200px" width="200px" ></div>
    </div>
    <H3 style="text-align: center;color: green;font-style: italic;">FOR ORDERS CALL : 6587965412 ** E-mail:instamart@gmail.com</H3>
</body>
</html>
```
## COOKIES
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>cookies</title>
    <style>
        .container{
            margin: 5px;
            padding: 20px;
            border: 8px;
            display: flex;
            justify-content: center;
            flex-direction: row;
            flex-wrap: wrap;
            border: 10px solid black;}
        .box{
            margin: 10px;
            padding: 20px;
            font-size: larger;
            font-style: italic;
            border: 3px solid black;
        }

    </style>
</head>
<body>
    <h1 style="text-align: center;">PRODUCTS</h1>
    <header style="color: bisque;">
            <nav  style=" text-align:end;">
                <a href="http://127.0.0.1:5500/prod.html" style="text-decoration: none; color: black; text-align: center; padding: 20px;">VEGETABLE </a>
                <a href="http://127.0.0.1:5500/Fru.html" style="text-decoration: none; color: black; text-align: center; padding: 20px;">FRUITS </a>
                <a href="http://127.0.0.1:5500/cookies.html" style="text-decoration: none; color: black; text-align: center; padding: 08px;">COOKIES</a>
            </nav>
    </header>
    <div class="container">
        <div class="box"><img src="c1.jpeg" alt="" height="200px" width="200px" ></div>
        <div class="box"><img src="c2.jpeg" alt="" height="200px" width="200px" ></div>
        <div class="box"><img src="c3.jpeg" alt="" height="200px" width="200px" ></div>
    </div>
    <footer>
        <H3 style="text-align: center;color: green;font-style: italic;">FOR ORDERS CALL : 6587965412 ** E-mail:instamart@gmail.com</H3>
    </footer>
    
</body>
</html>
```
## OUTPUT
![Screenshot 2025-04-17 133714](https://github.com/user-attachments/assets/e33ddb0f-e347-41be-ac7e-70a1b0032c6e)

![Screenshot 2025-04-17 133732](https://github.com/user-attachments/assets/131659b4-0ef9-4843-a32f-ffa70a95361b)

![Screenshot 2025-04-17 133748](https://github.com/user-attachments/assets/670b199f-2290-4b6d-80ab-2233dd49adc4)

![Screenshot 2025-04-17 133805](https://github.com/user-attachments/assets/c25fdfab-e06f-4cf6-a3b3-b371312289b2)

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
