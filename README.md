
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alexia's Portfolio</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Custom styles for this template -->
    <style>
        body {
            padding-top: 5rem;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin-right: 10px;
        }
        footer {
            background-color: #f8f9fa;
            text-align: center;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-md navbar-dark bg-dark fixed-top">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Alexia Vasquez</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarCollapse">
                <ul class="navbar-nav me-auto mb-2 mb-md-0">
                    <li class="nav-item"><a class="nav-link active" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- About Section -->
    <section id="about" class="container mt-4">
        <h2>About Me</h2>
        <p>Hello! I'm Alexia, a passionate data enthusiast with a knack for transforming data into compelling stories through code and visualization. With a background in aviation, and computer science, I've honed my skills in primarily python, R, and SQL, while being particularly fascinated by the power of data visualization to reveal insights, inform decisions, and to remove as much opinion about topics that I can.
        On my GitHub, you'll find a portfolio of projects ranging from exploratory data analysis to sophisticated interactive visualizations. Whether I'm uncovering trends in large datasets or developing tools that empower users to interact with data in new ways, I'm always looking for the next challenge that pushes the boundaries of what's possible with data. Let's connect and explore how we can make data-driven decisions more intuitive and impactful.</p>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="container mt-4">
        <h2>Projects</h2>
        <ul>
            <li><a href="link_to_project_1">Project 1</a></li>
            <li><a href="link_to_project_2">Project 2</a></li>
            <!-- Add more projects as needed -->
        </ul>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="container mt-4">
        <h2>Contact Me</h2>
        <p>Email: Alexiavasquez1@yahoo.com</p>
        <p>Phone: +1 682-239-0598</p>
        <p>Social Media: <a href="https://www.linkedin.com/in/alexia-vasquez-664577182">LinkedIn</a></p>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Alexia Vasquez</p>
    </footer>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
    <script>
        $(document).ready(function(){
            // Add smooth scrolling to all links
            $("a").on('click', function(event) {
                if (this.hash !== "") {
                    event.preventDefault();
                    var hash = this.hash;
                    $('html, body').animate({
                        scrollTop: $(hash).offset().top
                    }, 800, function(){
                        window.location.hash = hash;
                    });
                }
            });
        });
    </script>
</body>
</html>
