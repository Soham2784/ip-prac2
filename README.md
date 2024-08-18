<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Travel Around - Your Gateway to Adventure</title>
    <style>
        .logo {
            width: 150px;
        }

        .body {
            background-color: #f0f0f0;
            color: #333;
        }

        .header {
            background-color: #ff6347;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }

        .header img {
            display: block;
            margin: 0 auto 10px auto;
        }

        .nav ul {
            list-style: none;
            padding: 0;
        }

        .nav ul li {
            display: inline;
            margin: 0 10px;
        }

        .nav ul li a {
            color: #fff;
            text-decoration: none;
        }

        .section {
            padding: 20px;
        }

        .home {
            background-color: #fff;
        }

        .heading {
            color: #ff6347;
        }

        .table {
            width: 100%;
            border: 1px solid #333;
            border-collapse: collapse;
            background-color: #fff;
        }

        .table th,
        .table td {
            padding: 10px;
            border: 1px solid #333;
        }

        .table th {
            background-color: #ff6347;
            color: #fff;
        }

        .submit-btn {
            background-color: #ff6347;
            color: #fff;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
        }

        .footer {
            background-color: #ff6347;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }

        .footer a {
            color: #fff;
            text-decoration: none;
        }

        .city {
            width: 400px;
            height: 300px;
        }

        h1 {
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            str
        }

        .searchh {
            border-radius: 10px;
            margin: 200px;
            width: 250px;
            height: 24px;
        }
    </style>
</head>

<body class="body">
    <header class="header">
        <img class="logo" src="Screenshot 2024-08-12 190215.png" alt="Travel Around Logo">
        <h1><strong>Travel Around</strong></h1>
        <nav class="nav">
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#destinations">Destinations</a></li>
                <li><a href="#contact">Contact</a></li>
                <input class="searchh" type="text" id="mySearch" onkeyup="myFunction()" placeholder="Search to travel.."
                    title="Type in a category">
            </ul>
        </nav>
    </header>

    <main>
        <section id="home" class="section home">
            <h2 class="heading">Welcome to Travel Around!</h2>
            <p>Your gateway to unforgettable adventures and breathtaking destinations.</p>
            <video width="500px" height="550px" controls>
                <source src="https://videos.pexels.com/video-files/3135808/3135808-sd_640_360_24fps.mp4"
                    type="video/mp4">
                Your browser does not support the video tag.
            </video>
            <br>

            <audio controls>
                <source src="Audio 2024-08-18 at 12.14.25_7fb2edb6.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
        </section>

        <section id="about" class="section">
            <h2 class="heading">About Us</h2>
            <table class="table">
                <tr>
                    <th>Company Name</th>
                    <td>Travel Around</td>
                </tr>
                <tr>
                    <th>Founded</th>
                    <td>2005</td>
                </tr>
                <tr>
                    <th>Mission</th>
                    <td>To provide exceptional travel experiences and unforgettable adventures.</td>
                </tr>
                <tr>
                    <th>Contact</th>
                    <td>Email: @travelaround.com<br>Phone: +1200302238</td>
                </tr>
            </table>
        </section>

        <section id="destinations" class="section">
            <h2 class="heading">Featured Destinations</h2>
            <table class="table" style="width: 100%; border-collapse: collapse;">
                <tr>
                    <th style="width: 30%; text-align: left;">Destination</th>
                    <th style="width: 40%; text-align: left;">Description</th>
                    <th style="width: 30%; text-align: left;">Image</th>
                </tr>
                <tr>
                    <td>Paris, France</td>
                    <td style="width: 30%;">Experience the romance and charm of the City of Light. From the Eiffel Tower
                        to the Louvre, Paris is a dream come true.</td>
                    <td>
                        <img class="city" src="paris.png.png" alt="Paris, France" style="width: 100%;">
                    </td>
                </tr>
                <tr>
                    <td>London, England</td>
                    <td style="width: 30%;">Explore the rich history, iconic landmarks, and vibrant culture of London.
                        From the Tower of London to Buckingham Palace, the city is full of wonders.</td>
                    <td>
                        <img class="city" src="london.png.png" alt="London, England" style="width: 100%;">
                    </td>
                </tr>
                <tr>
                    <td>Tokyo, Japan</td>
                    <td style="width: 30%;">Immerse yourself in the futuristic skyline, historic temples, and unique
                        culture of Tokyo. A perfect blend of the old and the new.</td>
                    <td>
                        <img class="city" src="tokyo.png.png" alt="Tokyo, Japan" style="width: 100%;">
                    </td>
                </tr>
            </table>
        </section>


        <section id="contact" class="section">
            <h2 class="heading">Contact Us</h2>
            <form action="/submit-form" method="post">
                <table border="0" cellpadding="10" cellspacing="0">
                    <tr>
                        <td><label for="name">Name:</label></td>
                        <td><input type="text" id="name" name="name" required></td>
                    </tr>
                    <tr>
                        <td><label for="email">Email:</label></td>
                        <td><input type="email" id="email" name="email" required></td>
                    </tr>
                    <tr>
                        <td><label for="message">Message:</label></td>
                        <td><textarea id="message" name="message" rows="4" cols="50" required></textarea></td>
                    </tr>
                    <tr>
                        <td colspan="2" style="text-align: center;"><input type="submit" class="submit-btn"
                                value="Submit"></td>
                    </tr>
                </table>
            </form>
        </section>
    </main>

    <footer class="footer">
        <p>Follow us on:
            <a href="https://www.facebook.com/TravelAround" target="_blank">Facebook</a> |
            <a href="https://www.twitter.com/TravelAround" target="_blank">Twitter</a> |
            <a href="https://www.instagram.com/TravelAround" target="_blank">Instagram</a>
        </p>
    </footer>
</body>

</html>
