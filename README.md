# Project Responsive Web Design using Bootstrap
# Date:
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
home.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone - Home</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        .navbar {
            background-color: #3c3c3c;
        }
        .navbar-dark .navbar-nav .nav-link {
            color: #fff;
            margin-right: 15px;
        }
        .navbar-dark .navbar-brand {
            color: #fff;
            font-weight: bold;
        }
        .cta-btn {
            color: #fff;
            font-size: 0.9rem;
        }
        .btn-learn-more {
            background-color: #e0e0e0;
            color: #000;
        }
        .btn-sign-up {
            background-color: #ea4c89;
            color: #fff;
        }
        .form-control {
            max-width: 200px;
        }
        .footer {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
        }
        .image-gallery {
            padding: 60px 0;
        }
        .image-gallery img {
            width: 100%;
            height: auto;
            border-radius: 8px;
            
        }
        .header {
            background-color: #333;
            color: white;
            padding: 1rem 0;
        }

        .header a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;}
       
        .search-box-container { display: flex; justify-content: center; margin: 20px 0;}
        .search-box {
        display: flex;
        align-items: center;
        background: #f4f4f4;
        border-radius: 20px;
        padding: 10px 15px;
        box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        max-width: 400px;
        width: 100%;
        align-items: center;
      }
  
      .search-box input[type="text"] {
        border: none;
        background: transparent;
        outline: none;
        flex: 1;
        font-size: 16px;
        color: #333;
      }
  
      .search-box select {
        border: none;
        background: transparent;
        color: #333;
        margin-right: 10px;
        font-size: 16px;
      }
  
      .search-box button {
        background: #ff5fa3;
        border: none;
        border-radius: 50%;
        width: 30px;
        height: 30px;
        display: flex;
        justify-content: center;
        align-items: center;
        cursor: pointer;
        color: #fff;
        font-size: 16px;
      }
  
      .search-box button:hover {
        background: #e75491;
      }
      h1 { font-size: 48px; /* Larger font size for h1 */ font-family: 'Georgia', 'Times New Roman', Times, serif; /* Different font family for h1 */ margin-bottom: 20px; margin-top: 30px; /* Add space above the h1 tag */ } p { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: smaller; text-align: center; }

    </style>
</head>

  
<body>
    <!-- Navigation Bar -->
    <header class="header">
        <div class="container d-flex justify-content-between align-items-center">
            <a href="#" class="fs-4">Dribbble</a>
            <nav>
                <a href="#">Shots</a>
                <a href="#">Designers</a>
                <a href="#">Teams</a>
                <a href="#">Community</a>
                <a href="#">Jobs</a>
            </nav>
            <div>
                <button class="btn btn-outline-light">Sign Up</button>
                <button class="btn btn-light">Sign In</button>
            </div>
        </div>
    </header>
    
    <!-- Hero Section -->
    <body> <h1 class="text-center mb-4"> Discover the world’s top designers </h1> <p style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: smaller; text-align: center;"> Explore work from the most talented and accomplished designers ready to take on your next project </p>
        
    
        
    <div class="search-box-container"> <div class="search-box"> <select> <option>Shots</option> <!-- Add more options here --> </select> <input type="text" placeholder="What are you looking for?" /> <button> <span>&#128269;</span> <!-- Search Icon --> </button> </div> </div>

    <!-- Image Gallery Section -->
    <section class="image-gallery text-center">
        <div class="container">
            <div class="row">
                <div class="col-md-3 mb-4">
                    <img src="C:\Users\Suriya\Pictures\Screenshots\Screenshot 2024-12-22 184606.png" alt="Image 1">
                </div>
                <div class="col-md-3 mb-4">
                    <img src="C:\Users\Suriya\Pictures\Screenshots\Screenshot 2024-12-22 184617.png" alt="Image 2">
                </div>
                <div class="col-md-3 mb-4">
                    <img src="C:\Users\Suriya\Pictures\Screenshots\Screenshot 2024-12-22 184637.png" alt="Image 3">
                </div>
                <div class="col-md-3 mb-4">
                    <img src="C:\Users\Suriya\Pictures\Screenshots\Screenshot 2024-12-22 184652.png" alt="Image 4">
                </div>
                <div class="col-md-3 mb-4">
                    <img src="C:\Users\Suriya\Pictures\Screenshots\Screenshot 2024-12-22 184719.png" alt="Image 4">
                </div>
                <div class="col-md-3 mb-4">
                    <img src="C:\Users\Suriya\Pictures\Screenshots\Screenshot 2024-12-22 184731.png" alt="Image 4">
                </div>
                <div class="col-md-3 mb-4">
                    <img src="C:\Users\Suriya\Pictures\Screenshots\Screenshot 2024-12-22 184745.png" alt="Image 4">
                </div>
                <div class="col-md-3 mb-4">
                    <img src="C:\Users\Suriya\Pictures\Screenshots\Screenshot 2024-12-22 184804.png" alt="Image 4">
                </div>
                <div class="col-md-3 mb-4">
                    <img src="C:\Users\Suriya\Pictures\Screenshots\Screenshot 2024-12-22 184832.png" alt="Image 4">
                </div>
                <div class="col-md-3 mb-4">
                    <img src="C:\Users\Suriya\Pictures\Screenshots\Screenshot 2024-12-22 184850.png" alt="Image 4">
                </div>
                <div class="col-md-3 mb-4">
                    <img src="C:\Users\Suriya\Pictures\Screenshots\Screenshot 2024-12-22 184907.png" alt="Image 4">
                </div>
                <div class="col-md-3 mb-4">
                    <img src="C:\Users\Suriya\Pictures\Screenshots\Screenshot 2024-12-22 184937.png" alt="Image 4">
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
   

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```
designers.html
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Header</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 10px 20px;
            background-color: #fff;
            border-bottom: 1px solid #eaeaea;
        }
        .logo {
            font-size: 24px;
            font-weight: bold;
        }
        .search-bar {
            display: flex;
            align-items: center;
            background-color: #f5f5f5;
            border-radius: 20px;
            padding: 5px 10px;
            flex-grow: 2;
            max-width: 500px;
            margin: 0 20px;

        }
        .search-bar input {
            border: none;
            background: none;
            outline: none;
            padding: 5px;
            font-size: 16px;
            flex-grow: 1;

        }
        .search-bar button {
            background-color: #ea4c89;
            border: none;
            border-radius: 50%;
            padding: 10px;
            cursor: pointer;
            color: #fff;
        }
        .nav-links {
            display: flex;
            align-items: center;
        }
        .nav-links a {
            margin: 0 10px;
            text-decoration: none;
            color: #333;
            font-size: 16px;
        }
        .auth-links a {
            margin: 0 10px;
            text-decoration: none;
            color: #333;
            font-size: 16px;
        }
        .auth-links .login {
            background-color: #333;
            color: #fff;
            padding: 5px 10px;
            border-radius: 20px;
        }
        .image-gallery {
            padding: 60px 0;
        }
        .image-gallery img {
            width: 100%;;
            height: auto;
            border-radius: 8px;}
    
        
    </style>
</head>
<body>
    <header class="header">
        <div class="logo">Dribbble</div>
        <div class="search-bar">
            <input type="text" placeholder="What are you looking for?">
            <button>&#128269;</button> <!-- Using a search icon -->
        </div>
        <nav class="nav-links">
            <a href="#">Designers</a>
            <a href="#">Shots</a>
            
            <a href="#">Teams</a>
            <a href="#">Community</a>
            <a href="#">Jobs</a>
        </nav>
        <div class="auth-links">
            <a href="#">Sign up</a>
            <a href="#" class="login">Log in</a>
        </div>
    </header>
</body>
<body> <br></br><p style="font-family:cursive; font-size:xx-large; text-align: center; " class="text-center mb-4"> All designers </p>
<section class="image-gallery text-center">
    <div class="container">
        <div class="row">
            <div class="col-md-12 mb-4">
                <img src="C:\Users\Suriya\Pictures\Screenshots\Screenshot 2024-12-22 212530.png" alt="Image 1">
            </div>
            <div class="col-md-12 mb-4">
                <img src="C:\Users\Suriya\Pictures\Screenshots\Screenshot 2024-12-22 212456.png" alt="Image 2">
            </div>
            <div class="col-md-12 mb-4">
                <img src="C:\Users\Suriya\Pictures\Screenshots\Screenshot 2024-12-22 212516.png" alt="Image 3">
            </div>


```

login.html

```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Login Page</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            background: linear-gradient(to right, #141e30, #243b55);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #fff;
        }
        .card {
            border-radius: 20px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
            background: #1e272e;
            color: #fff;
            border: none;
        }
        .card-header {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 10px;
            text-align: center;
            font-size: 1.5rem;
            font-weight: bold;
            background: #2f3640;
            border-top-left-radius: 20px;
            border-top-right-radius: 20px;
            padding: 1rem;
            color: #fff;
        }
        .card-header img {
            width: 30px;
            height: 30px;
        }
        .btn-primary {
            background-color: #0097e6;
            border: none;
            color: #fff;
            transition: background-color 0.3s ease;
        }
        .btn-primary:hover {
            background-color: #00a8ff;
        }
        .form-control {
            background: #f5f6fa;
            color: #2f3640;
            border-radius: 10px;
            transition: border-color 0.3s ease;
        }
        .form-control:focus {
            box-shadow: none;
            border-color: #0097e6;
        }
        .form-label {
            color: #dcdde1;
        }
        .link {
            color: #00a8ff;
            transition: color 0.3s ease;
        }
        .link:hover {
            color: #0097e6;
            text-decoration: underline;
        }
        .text-center a {
            color: #00a8ff;
            transition: color 0.3s ease;
        }
        .text-center a:hover {
            color: #0097e6;
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="card p-4" style="width: 22rem;">
        <div class="card-header">
            
            Login
        </div>
        <div class="card-body">
            <form>
                <div class="mb-3">
                    <label for="email" class="form-label">Email address</label>
                    <input type="email" class="form-control" id="email" placeholder="Enter your email" required>
                </div>
                <div class="mb-3">
                    <label for="password" class="form-label">Password</label>
                    <input type="password" class="form-control" id="password" placeholder="Enter your password" required>
                </div>
                <div class="d-flex justify-content-between align-items-center">
                    <div>
                        <input type="checkbox" id="rememberMe">
                        <label for="rememberMe" class="form-label">Remember me</label>
                    </div>
                    <a href="#" class="text-decoration-none link">Forgot Password?</a>
                </div>
                <button type="submit" class="btn btn-primary w-100 mt-3">Login</button>
            </form>
        </div>
        <div class="text-center mt-3">
            <span>Don't have an account? <a href="signup.html" target="_blank" class="text-decoration-none link">Sign Up</a></span>
        </div>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

signup.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Sign Up Page</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            background: linear-gradient(to right, #1c92d2, #f2fcfe);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #fff;
        }
        .card {
            border-radius: 20px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
            background: #ffffff;
            color: #000;
            border: none;
            width: 100%;
            max-width: 400px;
            padding: 20px;
        }
        .card-header {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 10px;
            text-align: center;
            font-size: 1.5rem;
            font-weight: bold;
            background: linear-gradient(to right, #1c92d2, #f2fcfe);
            border-top-left-radius: 20px;
            border-top-right-radius: 20px;
            padding: 1rem;
            color: #ffffff;
        }
        .btn-primary {
            background-color: #1c92d2;
            border: none;
            color: #ffffff;
            transition: background-color 0.3s ease, transform 0.3s ease;
            border-radius: 10px;
        }
        .btn-primary:hover {
            background-color: #007bb5;
            transform: scale(1.05);
        }
        .form-control {
            background: #f5f6fa;
            color: #2f3640;
            border-radius: 10px;
            transition: border-color 0.3s ease, box-shadow 0.3s ease;
        }
        .form-control:focus {
            box-shadow: 0 0 10px rgba(28, 146, 210, 0.5);
            border-color: #1c92d2;
        }
        .form-label {
            color: #2f3640;
        }
        .link {
            color: #1c92d2;
            transition: color 0.3s ease;
        }
        .link:hover {
            color: #007bb5;
            text-decoration: underline;
        }
        .text-center a {
            color: #1c92d2;
            transition: color 0.3s ease;
        }
        .text-center a:hover {
            color: #007bb5;
            text-decoration: underline;
        }
        .logo {
            width: 50px;
            height: 50px;
        }
        .animate-fade-in {
            animation: fade-in 1s ease-in-out forwards;
        }
        @keyframes fade-in {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <div class="card animate-fade-in">
        <div class="card-header">
           
            Sign Up
        </div>
        <div class="card-body">
            <form>
                <div class="mb-3">
                    <label for="fullName" class="form-label">Full Name</label>
                    <input type="text" class="form-control" id="fullName" placeholder="Enter your full name" required>
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Email address</label>
                    <input type="email" class="form-control" id="email" placeholder="Enter your email" required>
                </div>
                <div class="mb-3">
                    <label for="password" class="form-label">Password</label>
                    <input type="password" class="form-control" id="password" placeholder="Enter your password" required>
                </div>
                <div class="mb-3">
                    <label for="confirmPassword" class="form-label">Confirm Password</label>
                    <input type="password" class="form-control" id="confirmPassword" placeholder="Confirm your password" required>
                </div>
                <button type="submit" class="btn btn-primary w-100 mt-3">Sign Up</button>
            </form>
        </div>
        <div class="text-center mt-3">
            <span>Already have an account? <a href="login.html" target="_blank" class="text-decoration-none link">Login</a></span>
        </div>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
# OUTPUT:
home


![Screenshot 2024-12-22 213649](https://github.com/user-attachments/assets/c4dd4281-c5d6-45c9-a7a0-c978181cfdc7)



designers
![Screenshot 2024-12-22 213603](https://github.com/user-attachments/assets/d8584bb3-407f-4ec9-82fa-953b520dd699)


login


![Screenshot 2024-12-22 213741](https://github.com/user-attachments/assets/99843c68-8ed3-4f4b-82d7-37a06dc779a3)

signup


![Screenshot 2024-12-22 213726](https://github.com/user-attachments/assets/6e3d6726-1433-422e-9644-b07cdde13fea)

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
