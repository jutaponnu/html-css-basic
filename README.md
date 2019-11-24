# html-css-basic

<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="utf-8">
  <title>Jutaponnuのポートフォリオサイト</title>
  <link rel="icon" href="favicon.ico">
  <meta name="description" content="Jutaponnuのポートフォリオサイトです。">
  <link rel="stylesheet" href="css/styles.css">
</head>
<body>
  <header>
    <div class="container">
      <div class="icon">
        <img src="img/taro.png" width="120" height="120" alt="Jutaponnuのアイコンです">
      </div>
      <div class="info">
        <h1>ゆたぽんぬ</h1>
        <p>UI/UXデザイナー見習いです</p>
        <ul>
          <li>
            <a href="https://dotinstall.com" target="_blank">
              <img src="img/blog.png" width="20" height="20" alt="ブログサイトへのリンク画像です">
            </a>
          </li>
          <li>
            <a href="https://dotinstall.com" target="_blank">
              <img src="img/photos.png" width="20" height="20" alt="写真サイトへのリンク画像です">
            </a>
          </li>
        </ul>
      </div>
    </div>
  </header>

  <section class="works">
    <h1>WORKS</h1>

    <section>
      <img src="img/work1.png" width="400" height="260" alt="勇者ゲームの紹介画像">
      <h1>勇者ゲーム</h1>
      <p>楽しいアプリです。楽しいアプリです。楽しいアプリです。楽しいアプリです。楽しいアプリです。楽しいアプリです。楽しいアプリです。楽しいアプリです。楽しいアプリです。楽しいアプリです。楽しいアプリです。</p>
    </section>

    <section>
      <img src="img/work2.png" width="400" height="260" alt="宝探しゲームの紹介画像">
      <h1>宝探しゲーム</h1>
      <p>楽しいアプリです。楽しいアプリです。楽しいアプリです。楽しいアプリです。楽しいアプリです。楽しいアプリです。楽しいアプリです。楽しいアプリです。楽しいアプリです。楽しいアプリです。楽しいアプリです。</p>
    </section>

    <section>
      <img src="img/work3.png" width="400" height="260" alt="神経衰弱の紹介画像">
      <h1>神経衰弱</h1>
      <p>楽しいアプリです。楽しいアプリです。楽しいアプリです。楽しいアプリです。楽しいアプリです。楽しいアプリです。楽しいアプリです。楽しいアプリです。楽しいアプリです。楽しいアプリです。楽しいアプリです。</p>
    </section>
  </section>

  <footer>
    <p>(c) dotinstall.com</p>
  </footer>
</body>
</html>

body{
  color: #333;
  font-family: Verdana, sans-serif;
  margin: 0;
}

header{
  background-color: #efefef;
  padding-top: 32px;
  padding-bottom: 32px;
  align-items: center;
}

.container {
  /* background-color: pink; */
  width: 400px;
  margin-left: auto;
  margin-right: auto;
  display: flex;
  align-items: center;
}

.icon {
  /* background-color: skyblue; */
}

.icon img {
  /* border-radius: 20px; */
  border-radius: 50%;
  border-width: 4px;
  border-style: solid;
  border-color: white;
}

.info {
  /* background-color: tomato; */
  margin-left: 32px;
}

.info h1 {
  font-weight: normal;
  font-size: 24px;
  margin: 0;
}

.info p {
  margin: 0;
  margin-bottom: 16px;
}

.info ul {
  margin: 0;
  padding: 0px;
  list-style-type: none;
  display: flex;
}

.info ul li {
  margin-right: 8px;
}

.works {
  width: 400px;
  margin-left: auto;
  margin-right: auto;
}

.works > h1 {
  font-weight: normal;
  font-size: 24px;
  text-align: center;
  margin-top: 60px;
  margin-bottom: 60px;
}

.works > section {
  margin-bottom: 60px;
}

.works > section > h1 {
  font-weight: normal;
}

.works p {
  line-height: 1.8;
}

footer p {
  text-align: center;
  font-size: 14px;
  margin-bottom: 60px;
  color: grey;
}
