<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Effects of Technology on Students</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: ghostwhite;
            border: 5px solid peachpuff;
        }

        button {
            padding: 10px 20px;
            font-size: 16px;
            margin: 10px;
        }

        #content {
            margin: 20px;
        }

        .splash {
            display: none;
        }

        img, video {
            max-width: 100%;
            height: auto;
            margin: 10px 0;
        }

        footer {
            background-color: turquoise;
            padding: 10px;
        }

        footer p {
            color: white;
        }

        .gallery {
            display: flex;
            flex-direction: column; /* Adjusted to display images in a vertical line */
            align-items: center; /* Centering images horizontally */
            margin: 20px;
        }

        .gallery img {
            max-width: 80%; /* Adjusted size to fit within the border lines */
            height: auto;
            margin: 10px;
            border: 2px solid peachpuff;
            border-radius: 5px;
        }
    </style>
</head>
<body>

    <h1>Effects of Technology on Students</h1>

    <div id="content">
        <div id="about" class="splash">
            <h2>About</h2>
            <p>
                Technology has become an integral part of education, influencing students in various ways.
                The effects include improved access to information, enhanced collaboration, but also potential challenges
                such as distraction and increased screen time. Explore the impact of technology on students' academics
                through our informative content.
            </p>

            <img src="C:\Users\Administrator\Desktop\honeyinfot2\1.jpeg" alt="About Image">
            <video controls>
                <source src="C:\Users\Administrator\Desktop\honeyinfot2\10000000_24550685561244875_5376936100170870617_n.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </div>
        <script>
		var myVideo = C:\Users\Administrator\Desktop\honeyinfot2\10000000_24550685561244875_5376936100170870617_n.mp4("video1);
		function playPause() {
		if (myVideo.paused)
		myVideo.play();
		else
		myVideo.pause();
		}
		function makeBig() {
		myVideo.width = 550;
		}
		function makeSmall() {
		myVideo.width = 320;
		}
		function makeNormal() {
		myVideo.width = 420;
		}
		</script>
		
	
        <div id="home" class="splash">
            <h2>Welcome to the Home Page</h2>
            <p>This is the starting point of your educational website. Explore the effects of technology on students using the navigation buttons.</p>
            <div class="gallery">
                <img src="C:\Users\Administrator\Desktop\honeyinfot2\2.jpg" alt="Gallery Image 1">
                <img src="C:\Users\Administrator\Desktop\honeyinfot2\3.jpg" alt="Gallery Image 2">
                <img src="C:\Users\Administrator\Desktop\honeyinfot2\4.jpg" alt="Gallery Image 3">
                <img src="C:\Users\Administrator\Desktop\honeyinfot2\5.jpg" alt="Gallery Image 4">
            </div>
        </div>

        <button onclick="showSplash('home')">Home</button>
        <button onclick="showSplash('about')">About</button>
        <!-- Add more buttons as needed -->
    </div>

    <footer>
        <p>Footnotes:</p>
        <ol>
            <li>Honey Esparagoza</li>
            <li>Krislen Faith Dillo</li>
            <li>Anelyn Almonte</li>
            <li>Ma.Christina Vicente</li>
            <li>Jellibeth Dayo</li>
            <li>Dante Macuja</li>
        </ol>
        <p>Class Section: BSIS 2 E</p>
        <p>References:</p>
        <ul>
            <li>Code structure and styling inspired by educational web development practices.</li>
            <!-- Add more references as needed -->
        </ul>
    </footer>

    <script>
        function showSplash(splashId) {
            // Hide all splash pages
            var splashes = document.getElementsByClassName("splash");
            for (var i = 0; i < splashes.length; i++) {
                splashes[i].style.display = "none";
            }

            // Show the selected splash page
            document.getElementById(splashId).style.display = "block";
        }
    </script>

</body>
</html>
