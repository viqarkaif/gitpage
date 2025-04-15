# Holiday Booking  - Static Website Documentation
Project Overview
The Holiday Booking Website provides a user-friendly interface to explore travel destinations, learn about offered services, and book holidays seamlessly. The design focuses on simplicity, responsiveness, and visual appeal.


Tools Used
- HTML: To structure the website content.
- CSS: To style the website.
- GitHub Pages: To host and publish the website.

# Code Explanation

 
# 1. HTML Code
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Holiday Booking</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="https://dreamholidaysmanipal.com/wp-content/uploads/2023/10/Dream-Holidays-e1697437136717.png" alt="Dream Holidays Logo">
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#destinations">Destinations</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#booking">Book Now</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h1>Welcome to Dream Holidays</h1>
        <p>Plan your perfect getaway with our exclusive deals!</p>
        <img src="https://tripcrafters.com/agent/agent_photos/33718-1673001649.png" alt="Holiday Banner" class="banner">
    </section>

    <section id="destinations">
        <h2>Popular Destinations</h2>
        <div class="destination">
            <img src="https://dynamic-media-cdn.tripadvisor.com/media/photo-o/2e/92/29/4d/caption.jpg?w=1000&h=600&s=1" alt="Maldives">
            <h3>Maldives</h3>
            <p>Experience paradise on Earth.</p>
        </div>
        <div class="destination">
            <img src="https://www.thetimes.com/imageserver/image/%2Fmethode%2Ftimes%2Fprod%2Fweb%2Fbin%2F7510fc3d-ce85-4200-a7cf-49d6f22ea9e7.jpg?crop=4999%2C2812%2C0%2C0&resize=1500" alt="Switzerland">
            <h3>Switzerland</h3>
            <p>Explore the stunning Alps.</p>
        </div>
        <div class="destination">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e2/Queenstown_from_Bob%27s_Peak.jpg/500px-Queenstown_from_Bob%27s_Peak.jpg" alt="New Zealand">
            <h3>New Zealand</h3>
            <p>Discover breathtaking landscapes.</p>
        </div>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <ul>
            <li>Flight Booking</li>
            <li>Hotel Reservations</li>
            <li>Travel Insurance</li>
            <li>Tour Packages</li>
        </ul>
    </section>

    <section id="booking">
        <h2>Book Your Holiday</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <input type="text" placeholder="Destination" required>
            <input type="date" required>
            <button type="submit">Book Now</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Dream Holidays. All rights reserved.</p>
    </footer>
</body>
</html>

```


# 2. CSS Code

 ```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    color: #333;
    line-height: 1.6;
}

header {
    background: #1e90ff;
    color: white;
    padding: 1rem;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

header .logo img {
    height: 50px;
}

nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    margin: 0;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

section {
    padding: 2rem;
    text-align: center;
}

section#home {
    background: #f4f4f4;
}

.banner {
    width: 200px; /* Reduce the image width even further */
    height: auto; /* Maintain the aspect ratio */
    margin-top: 10px; /* Minimal spacing above the image */
  }
  

.destination {
    margin: 1rem;
    padding: 1rem;
    border: 1px solid #ddd;
    border-radius: 5px;
    display: inline-block;
    text-align: center;
    max-width: 300px; /* Restrict the overall width of the destination block */
}

.destination img {
    width: 100%; /* Make the image fit within the container */
    height: auto; /* Maintain the original aspect ratio */
    border-radius: 10px; /* Add rounded corners for aesthetic appeal */
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2); /* Optional: Add a shadow for a polished look */
}

form input,
form button {
    display: block;
    width: 80%;
    margin: 1rem auto;
    padding: 10px;
}

form button {
    background: #1e90ff;
    color: white;
    border: none;
    cursor: pointer;
}

form button:hover {
    background: #1c86ee;
}

footer {
    text-align: center;
    padding: 1rem;
    background: #333;
    color: white;
}

```

# Deployment Guide

- Prepare the Code:- Save the HTML code as index.html.
- Save the CSS code as style.css.


 # Create a GitHub Repository:
- Go to GitHub and create a new repository.
- Upload the files to the repository.

#  Enable GitHub Pages:
- Go to the repository’s Settings.
- Under the Pages section, set the source to main branch and root folder.

 #  Access Your Website:-
- GitHub will provide a live link (e.g., https://<username>.github.io/<repo-name>).


