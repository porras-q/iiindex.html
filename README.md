<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Harbor Light Community Center</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        /* Centering and spacing */
        .center-and-space-content {
            text-align: center;
            padding: 10px;
        }

        nav ul {
            list-style: none;
            padding: 0;
            text-align: center;
        }

        nav ul li {
            display: inline;
            margin: 0 5px;
        }

        nav ul li a {
            text-decoration: none;
        }
    </style>
</head>
<body>

<header class="center-and-space-content">
    <img src="https://edube.org/uploads/media/default/0001/04/logo.jpg" 
         alt="Harbor Light Community Center Logo">
    <p>Welcome to Harbor Light Community Center</p>
</header>

<nav aria-label="Main Navigation">
    <ul>
        <li><a href="#about">|  About   |</a></li>
        <li><a href="#services">Services  |</a></li>
        <li><a href="#events">Events  |</a></li>
        <li><a href="#contact">Contact  |</a></li>
    </ul>
</nav>

<div class="banner">
    <img src="https://edube.org/uploads/media/default/0001/04/decorative-banner.jpg" 
         aria-hidden="true" alt="">
</div>

<main>
    <section id="about">
        <h2>About Us</h2>
        <p>The Harbor Light Community Center has been at the heart of our community for over
        30 years, offering a wide range of services and programs designed to support and enrich the lives
        of our residents.</p>
        <p>
            <img src="https://edube.org/uploads/media/default/0001/04/community-center.jpg" 
                 alt="Harbor Light Community Center People" hspace="10" vspace="10">
        </p>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <p>From educational workshops and sports leagues to wellness programs and art classes,
        our services are tailored to meet the diverse needs of our community members.</p>
    </section>

    <section id="events" itemscope itemtype="http://schema.org/Event">
        <h2>Join Our Events</h2>
        <p>Our community center is a hub of activity, hosting events throughout the year. Don't
        miss our annual summer festival for fun, food, and festivities for all ages.</p>
        
        <p><strong itemprop="name">Annual Summer Festival</strong></p>
        <time datetime="2050-07-20" itemprop="startDate">Starts: July 20, 2050</time>
        <meta itemprop="description" content="Annual Summer Festival with fun, food, and festivities for all ages.">
    </section>
</main>

<footer id="contact" class="center-and-space-content">
    <h2>Contact Us</h2>
    <p>Have questions or want to get involved? Email us!</p>
    <a href="mailto:info@harborlight.com"><em>info@harborlight.com</em></a>
    <p>© 2050 Harbor Light Community Center</p>
</footer>

</body>
</html>
