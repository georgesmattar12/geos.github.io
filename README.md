<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Web Development Portfolio</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 1em;
            text-align: center;
        }

        section {
            max-width: 800px;
            margin: 2em auto;
            padding: 1em;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
        }

        h1, h2 {
            color: #333;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        li {
            margin-bottom: 0.5em;
        }

        button {
            background-color: #333;
            color: #fff;
            padding: 0.5em 1em;
            border: none;
            border-radius: 3px;
            cursor: pointer;
        }

        button:hover {
            background-color: #555;
        }
		footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em;
            position: fixed;
            width: 100%;
            bottom: 0;
			height:1%;
            font-size: 18px; /* Adjust the font size as needed */
        }
		 footer p {
            margin-top: -5px; /* Adjust this value as needed */
        }
	
    </style>
</head>
<body>
    <header>
        <h1>Your Web Development Portfolio</h1>
    </header>

    <section>
        <h2>About Me</h2>
		   <img src="C:/Users/Pc/Pictures/Saved Pictures/news photo/geo1.png" alt="Your Name" style="max-width: 30%; border-radius: 100%; display: block; margin: 0 auto;">
        <p>Hi, I'm George Mattar, a passionate web developer with expertise in front-end and back-end technologies. I create modern, responsive, and user-friendly websites for clients across various industries.</p>
    </section>

    <section>
        <h2>My Services</h2>
        <ul>
            <li>Custom Website Development</li>
            <li>Responsive Web Design</li>
            <li>Front-end and Back-end Development</li>
            <li>Content Management System (CMS) Integration</li>
            <li>E-commerce Solutions</li>
        </ul>
    </section>

   <section>
    <h2>Portfolio</h2>

     <div class="portfolio-item">
        <!-- <img src="path/to/project1-thumbnail.jpg" alt="Project 1"> -->
        <h3>Project 1: French Company Application</h3>
        <p>Developed a custom application for a French company, addressing their specific business needs. The application streamlines processes and enhances efficiency, tailored to the client's requirements.</p>
    </div>

    <div class="portfolio-item">
       <!--  <img src="path/to/project2-thumbnail.jpg" alt="Project 2"> -->
        <h3>Project 2: Web Store Application</h3>
        <p>Created a robust web store application for a client, featuring secure payment integration, a user-friendly product catalog, and customer account management. The platform is designed for optimal performance and scalability.</p>
    </div>

 

</section>


    <section>
        <h2>Contact Me</h2>
        <p>If you're looking for a dedicated web developer to bring your ideas to life, feel free to reach out. I'm excited to work with you!</p>
        <button onclick="window.location.href='mailto:georges.mattar.1@outlook.com'">Email Me</button>
    </section>

    <script>

    </script>
	 <footer>
        <p >&copy; 2023 GEO. All rights reserved.</p>
    </footer>
</body>

</html>
