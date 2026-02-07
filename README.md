# valentine-for-jeet
For my Valentine ❤️
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Will You Be My Valentine? 💖</title>

    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, #ff758c, #ff7eb3);
            font-family: 'Segoe UI', sans-serif;
        }

        .card {
            background: white;
            padding: 25px;
            border-radius: 20px;
            text-align: center;
            box-shadow: 0 10px 30px rgba(0,0,0,0.3);
            width: 300px;
        }

        img {
            width: 100%;
            border-radius: 15px;
            margin-bottom: 15px;
        }

        h1 {
            color: #ff4d6d;
        }

        button {
            padding: 10px 18px;
            font-size: 16px;
            border: none;
            border-radius: 20px;
            cursor: pointer;
            margin: 10px;
        }

        #yes {
            background: #ff4d6d;
            color: white;
        }

        #no {
            background: #ddd;
        }
    </style>
</head>

<body>

<div class="card">
    <!-- PHOTO -->
    <img src="https://drive.google.com/uc?export=view&id=PHOTO_FILE_ID" alt="Us 💕">

    <h1>Will you be my Valentine? 💘</h1>

    <button id="yes">YES 💖</button>
    <button id="no">NO 🙃</button>

    <!-- MUSIC -->
    <audio id="music" src="https://drive.google.com/uc?export=download&id=1f3t_VIbE8OzGu0oJBl9W5Pb03VZzqk-r"></audio>
</div>

<script>
    document.getElementById("yes").onclick = function () {
        document.getElementById("music").play();
        alert("Yayyy!! I love you ❤️🎶");
    };

    document.getElementById("no").onclick = function () {
        alert("Not allowed 😤 Try again!");
    };
</script>

</body>
</html>

