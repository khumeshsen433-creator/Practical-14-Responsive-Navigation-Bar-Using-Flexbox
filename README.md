# Practical-14-Responsive-Navigation-Bar-Using-Flexbox

<!DOCTYPE html>
<html>
<head>
    <title>Flexbox Navbar</title>
    <meta name="viewport"
          content="width=device-width, initial-scale=1">

    <style>
        * {
            box-sizing: border-box;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            gap: 15px;
            padding: 15px;
            background: navy;
            color: white;
        }

        .links {
            display: flex;
            gap: 20px;
        }

        a {
            color: white;
            text-decoration: none;
        }

        button {
            padding: 10px;
            cursor: pointer;
        }

        @media (max-width: 600px) {
            nav, .links {
                flex-direction: column;
                text-align: center;
            }
        }
    </style>
</head>
<body>
    <nav>
        <h2>MyCollege</h2>

        <div class="links">
            <a href="#">Home</a>
            <a href="#">Courses</a>
            <a href="#">About</a>
            <a href="#">Contact</a>
        </div>

        <button>Login</button>
    </nav>
</body>
</html>
