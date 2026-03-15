# fiorold-sungit-figorn




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>6 Love monthsary With You with more kupal pa at the same time</title>
    <style>
        body {
            background-color: #fce4ec; /* Light pink background */
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
            color: #880e4f;
        }

        h1 {
            margin-bottom: 20px;
            animation: fadeIn 3s;
        }

        .video-container {
            width: 90%;
            max-width: 600px;
            background: white;
            padding: 10px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            margin-bottom: 20px;
        }

        video {
            width: 100%;
            border-radius: 10px;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            width: 90%;
            max-width: 1000px;
        }

        .gallery img {
            width: 100%;
            border-radius: 10px;
            transition: transform 0.3s;
        }

        .gallery img:hover {
            transform: scale(1.05);
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>
</head>
<body>

    <h1>Happy 6th monthsary! ❤️</h1>

    <div class="video-container">
        <video id="myVideo" autoplay muted loop controls>
            <source src="received_1491150845340267.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>

    <h1>Happy 6th monthsary! ❤️</h1>

    <div class="video-container">
        <video id="myVideo" autoplay muted loop controls>
            <source src="video_20251005_195641.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>

    
 <h1>Happy 6th monthsary! ❤️</h1>

    <div class="video-container">
        <video id="myVideo" autoplay muted loop controls>
            <source src="InShot_20250914_190851826.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>


    <div class="gallery">
        <img src="1.jpg" alt="Memory 1">
        <img src="2.jpg" alt="Memory 2">
        <img src="3.jpg" alt="Memory 3">
    </div>

    <script>
        // Most browsers block video sound on "autoplay". 
        // This script tries to unmute if the user clicks anywhere on the page.
        document.body.addEventListener('click', function() {
            var video = document.getElementById('myVideo');
            video.muted = false;
        }, {once: true});
    </script>

</body>
</html>


<script>
    function createHeart() {
        const heart = document.createElement('div');
        heart.classList.add('Fiorold');
        
        // This adds the name you wanted to the falling animation
        heart.innerHTML = 'Fiorold ❤️'; 
        
        heart.style.left = Math.random() * 100 + 'vw';
        heart.style.animationDuration = Math.random() * 3 + 3 + 's';
        heart.style.fontSize = Math.random() * 10 + 15 + 'px';
        heart.style.opacity = Math.random();
        
        document.body.appendChild(heart);

        setTimeout(() => { heart.remove(); }, 6000);
    }

    setInterval(createHeart, 400); // Hearts fall every 0.4 seconds
</script>
