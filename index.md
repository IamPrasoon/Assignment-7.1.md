
<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Responsive Navbar</title>
    <style>
        body { margin: 0; font-family: Arial; }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 15px;
            background: navy;
            color: white;
            padding: 15px;
        }
        nav {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
        }
        nav a { color: white; text-decoration: none; }
        button {
            background: orange;
            padding: 10px;
            border: none;
            border-radius: 5px;
        }
        @media (max-width: 600px) {
            header { flex-direction: column; }
            nav { justify-content: center; }
        }
    </style>
</head>
<body>
    <header>
        <h2>Prasoon's Website</h2>
        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
        <button onclick="location.href='#contact'">Join Us</button>
    </header>

    <main>
        <section id="home"><h1>Welcome!</h1></section>
        <section id="about"><h2>About Me</h2></section>
        <section id="contact"><h2>Contact</h2></section>
    </main>
</body>
</html>
