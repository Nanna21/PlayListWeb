<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    }
body {
  background-attachment: fixed;
}
.card {
    width: 300px;
    margin: 50px auto;
    background: linear-gradient(135deg, #fffcf0 0%, #fff3b0 100%);
    padding: 15px 15px 35px 15px;
    border-radius: 2px 2px 15px 5px;
    box-shadow: 3px 5px 15px rgba(0,0,0,0.15);
    position: relative; 
}
    .card img { width: 100%; height: 200px; object-fit: cover; border-radius: 5px; margin-bottom: 15px; }
    .card h2 { color: #2c3e50; font-size: 1.5rem; margin-bottom: 10px; }
    .card p { color: #444; font-size: 1.1rem; line-height: 1.5; }
 .badge{
    position: absolute; top: -20px;left: 250px ;
    background-color: rgb(161, 212, 20);
    border: rgb(161, 212, 20) solid 3px;
    font-size: 15px;
    border-radius: 10px;
 }
.card:hover {
    transform: scale(1.05) rotate(10deg);
    z-index: 10;
}

.secret-memo{
    padding-top: 20PX;
    border-top: gray dashed 2px;
    visibility: hidden;
}
.card:hover .secret-memo {
    visibility: visible;
}
    </style>
</head>
<body>
        <div class="card">
            <div class="badge">Hot🔥</div>
            
            <img src="https://th.bing.com/th/id/OIP.ZYurYGaOg4SiXhEJQikvcAHaHa?o=7rm=3&rs=1&pid=ImgDetMain&o=7&rm=3" width="250px" alt="일본 맛집">
            <h2>✨ 서동건의 꿈</h2>
            <p>🍤 1. 일본으로 여행가서 맛집탐방</p>
            <p>💻 2. 첫 게임 만들기</p>
            
            <div class="secret-memo">🤫 TMI: 여권 없음</div>
        </div>
</body>
</html>
