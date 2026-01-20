<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>For You ❤️</title>

<style>
body {
    background: linear-gradient(to right, #ff758c, #ff7eb3);
    font-family: Arial, sans-serif;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 0;
}
.card {
    background: white;
    padding: 30px;
    border-radius: 15px;
    width: 330px;
    text-align: center;
    box-shadow: 0 10px 20px rgba(0,0,0,0.2);
}
h2 { color: #ff4d6d; }

button {
    margin-top: 15px;
    padding: 10px;
    width: 100%;
    border: none;
    background: #ff4d6d;
    color: white;
    border-radius: 8px;
    font-size: 16px;
    cursor: pointer;
}

.heart {
    font-size: 60px;
    margin-top: 20px;
    display: none;
    animation: beat 1s infinite;
}

@keyframes beat {
    0% { transform: scale(1); }
    50% { transform: scale(1.3); }
    100% { transform: scale(1); }
}
</style>
</head>

<body>
<div class="card">
    <h2>💖 Hi Love</h2>
    <p>Click the button 🥺</p>

    <button onclick="showHeart()">Show My Heart</button>
    <div class="heart" id="heart">❤️</div>
</div>

<script>
function showHeart() {
    document.getElementById("heart").style.display = "block";
}
</script>
</body>
</html>
