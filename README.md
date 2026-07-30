# hustler-game
Mini game missing both side
<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Game Portal</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #111;
    color: white;
}

header {
    padding: 20px;
    background: #222;
    text-align: center;
}

.logo {
    font-size: 32px;
    font-weight: bold;
}

.search {
    margin-top: 20px;
}

input {
    width: 70%;
    padding: 12px;
    border-radius: 20px;
    border: none;
}

section {
    padding: 20px;
}

h2 {
    border-left: 5px solid #00aaff;
    padding-left: 10px;
}

.games {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(180px,1fr));
    gap: 20px;
}

.card {
    background: #222;
    border-radius: 15px;
    overflow: hidden;
    text-align: center;
    padding-bottom: 15px;
}

.card img {
    width: 100%;
    height: 120px;
    object-fit: cover;
    background: #333;
}

button {
    background: #00aaff;
    border: none;
    color:white;
    padding:10px 25px;
    border-radius:20px;
    cursor:pointer;
}

.categories {
    display:flex;
    gap:10px;
    flex-wrap:wrap;
}

.category {
    background:#333;
    padding:10px 20px;
    border-radius:20px;
}

footer {
    text-align:center;
    padding:30px;
    background:#222;
}
</style>

</head>

<body>

<header>

<div class="logo">
🎮 GAME PORTAL
</div>

<p>無料で遊べるブラウザゲーム集</p>

<div class="search">
<input placeholder="ゲームを検索">
</div>

</header>


<section>

<h2>🔥 人気ゲーム</h2>

<div class="games">

<div class="card">
<img src="">
<h3>2048</h3>
<button>プレイ</button>
</div>


<div class="card">
<img src="">
<h3>ブロック崩し</h3>
<button>プレイ</button>
</div>


<div class="card">
<img src="">
<h3>Snake</h3>
<button>プレイ</button>
</div>

</div>

</section>



<section>

<h2>🆕 新着ゲーム</h2>

<div class="games">

<div class="card">
<img src="">
<h3>新しいゲーム</h3>
<button>プレイ</button>
</div>

</div>

</section>



<section>

<h2>🎯 ジャンル</h2>

<div class="categories">

<div class="category">パズル</div>
<div class="category">アクション</div>
<div class="category">脳トレ</div>
<div class="category">カード</div>
<div class="category">タイピング</div>

</div>

</section>


<footer>

© 2026 GAME PORTAL

</footer>




</body>
</html>
