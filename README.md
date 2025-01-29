<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>For Maha ❤️</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Welcome, My Love! 💖</h1>
        <p>Maha, this is a little journey about us, leading to something special...</p>
        <a href="memory.html" class="btn">Start the Journey</a>
    </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Memory Lane</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Memory Lane 📸</h1>
        <div class="gallery">
            <img src="img1.jpg" alt="Our moment 1">
            <img src="img2.jpg" alt="Our moment 2">
            <img src="img3.jpg" alt="Our moment 3">
        </div>
        <a href="reasons.html" class="btn">Next</a>
    </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Reasons I Love You</title>
    <link rel="stylesheet" href="style.css">
    <script defer src="script.js"></script>
</head>
<body>
    <div class="container">
        <h1>Reasons I Love You ❤️</h1>
        <ul>
            <li onclick="showReason(1)">❤️</li>
            <li onclick="showReason(2)">❤️</li>
            <li onclick="showReason(3)">❤️</li>
        </ul>
        <p id="reason-text"></p>
        <a href="quiz.html" class="btn">Next</a>
    </div>
</body>
  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Love Quiz</title>
    <link rel="stylesheet" href="style.css">
    <script defer src="script.js"></script>
</head>
<body>
    <div class="container">
        <h1>Love Quiz 💕</h1>
        <p>What was our first date location?</p>
        <button onclick="showResult()">A. Cafe</button>
        <button onclick="showResult()">B. Park</button>
        <button onclick="showResult()">C. Movie</button>
        <p id="quiz-result"></p>
        <a href="proposal.html" class="btn">Final Step</a>
    </div>
</body>
</html>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Marry Me?</title>
    <link rel="stylesheet" href="style.css">
    <script defer src="script.js"></script>
</head>
<body>
    <div class="container">
        <h1>Maha, Will You Marry Me? 💍</h1>
        <button onclick="showConfetti()">Yes! 💖</button>
        <canvas id="confetti"></canvas>
    </div>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    text-align: center;
    background: pink;
}
.container {
    margin-top: 50px;
}
h1 {
    color: darkred;
}
.btn {
    padding: 10px 20px;
    background: red;
    color: white;
    text-decoration: none;
    border-radius: 5px;
}
.gallery img {
    width: 100px;
    margin: 10px;
}
ul {
    list-style: none;
}
ul li {
    display: inline;
    font-size: 2rem;
    cursor: pointer;
}
function showReason(num) {
    let reasons = [
        "You are my happiness! 💕",
        "Your kindness melts my heart! 🥰",
        "I love the way you laugh! 😍"
    ];
    document.getElementById("reason-text").innerText = reasons[num - 1];
}

function showResult() {
    document.getElementById("quiz-result").innerText = "Correct! No matter the answer, I love you! ❤️";
}

function showConfetti() {
    alert("Yay! You said Yes! 🎉💍");
}
git add .
git commit -m "First commit - Proposal for Maha"
git push origin main
