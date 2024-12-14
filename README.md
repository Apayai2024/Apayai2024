<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Study Skills Hub</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Study Skills Hub</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#resources">Resources</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home" class="hero">
        <div class="container">
            <h2>Boost Your Learning Today</h2>
            <p>Your go-to platform for mastering study skills and improving productivity!</p>
            <a href="#resources" class="btn">Explore Resources</a>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2>About Us</h2>
            <p>Welcome to Study Skills Hub! We are dedicated to helping students achieve their academic goals with practical tips and tools.</p>
        </div>
    </section>

    <section id="resources">
        <div class="container">
            <h2>Resources</h2>
            <div class="resource-cards">
                <div class="card">
                    <h3>Study Tips</h3>
                    <p>Discover effective strategies to maximize your learning.</p>
                </div>
                <div class="card">
                    <h3>Printable Planners</h3>
                    <p>Stay organized with our free downloadable planners.</p>
                </div>
                <div class="card">
                    <h3>Exclusive Tutorials</h3>
                    <p>Access video tutorials on time management and productivity.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="5" required></textarea>

                <button type="submit">Send</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Study Skills Hub. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
