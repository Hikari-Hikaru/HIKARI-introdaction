<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#fbb6c2">
  <title>I_am_hikari___のスタオタ(StartEntertaimentオタク)の経歴</title>
  <style>
    body {
      font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
      line-height: 1.6;
      margin: 0;
      padding: 0;
      color: #333;
      background-color: #f9f9f9;
    }

    header, main, footer {
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
    }

    header {
      background-color: #fbb6c2;
      color: #FF007F;
      text-align: center;
      padding: 40px 20px;
    }

    header h1 {
      margin: 0;
      font-size: 1.8em;
    }

    main {
      background-color: white;
      margin-top: 20px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
      border-radius: 5px;
    }

    h2 {
      color: #FF007F;
      font-size: 1.5em;
      background-color: #fbb6c2;
      padding: 10px;
      border-radius: 5px;
    }

    .text-image-row {
      display: flex;
      align-items: flex-start;
      margin-bottom: 20px;
      gap: 20px;
    }

    .text-image-row img {
      max-width: 200px;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
      cursor: pointer;
      transition: transform 0.3s ease;
    }

    .text-image-row img:hover {
      transform: scale(1.05);
    }

    .text-image-row p {
      flex: 1;
      margin: 0;
      line-height: 1.8;
    }

    footer {
      text-align: center;
      font-size: 0.9em;
      color: #777;
      margin-top: 30px;
      padding-top: 10px;
      border-top: 1px solid #ddd;
    }

    @media (max-width: 600px) {
      .text-image-row {
        flex-direction: column;
        align-items: center;
      }

      .text-image-row img {
        max-width: 100%;
      }
    }

    /* モーダルスタイル */
    #modal {
      display: none;
      position: fixed;
      z-index: 9999;
      left: 0;
      top: 0;
      width: 100%;
      height: 100%;
      overflow: auto;
      background-color: rgba(0,0,0,0.8);
    }

    #modal img {
      display: block;
      margin: 5% auto;
      max-width: 90%;
      max-height: 90%;
      border-radius: 10px;
      box-shadow: 0 0 20px rgba(255,255,255,0.5);
    }

    #modal:target {
      display: block;
    }
  </style>
</head>
<body>
  <header>
    <h1>HIKARIの自己紹介</h1>
  </header>

  <main>
    <h2>HIKARIです。</h2>

    <!-- 1 -->
    <div class="text-image-row">
      <p>
        まず、中学1年生の頃(Hey!Say!JUMPがデビューした年)2007年：山田涼介くん担当になりました！<br><br>
      </p>
      <img src="https://raw.githubusercontent.com/Hikari-Hikaru/HIKARI-introdaction/main/ry1.jpg" alt="おでかけ写真1" onclick="openModal(this.src)">
    </div>

    <!-- 2 -->
    <div class="text-image-row">
      <p>
        その後、訳あって、高校2年生の頃にB.I.Shadowにハマりました！<br><br>
        (初代：高畑岬、中島健人(旧SexyZoneメンバー)、菊池風磨(Timeleszメンバー)/セクゾデビュー直前までのメンバー：中島健人、菊池風磨、高地優吾(SixTONES)、松村北斗(SixTONES))<br><br>
      </p>
      <img src="https://raw.githubusercontent.com/Hikari-Hikaru/HIKARI-introdaction/main/kn1.jpg" alt="おでかけ写真2" onclick="openModal(this.src)">
    </div>

    <!-- 3 -->
    <div class="text-image-row">
      <p>
        その後、SexyZoneにハマり、オタ卒したくない一心で、Mr.SnowやLoveTuneやMr.kingとMr.Princeにハマりました！<br><br>
      「花のち晴れ」のドラマの頃は「平野紫耀担」でした👑❤️<br><br>
      </p>
      <img src="https://raw.githubusercontent.com/Hikari-Hikaru/HIKARI-introdaction/main/sh1.jpg" alt="おでかけ写真3" onclick="openModal(this.src)">
    </div>

    <!-- 4 -->
    <div class="text-image-row">
      <p>
        宇宙Six時代の話等をオタク時代の記憶を頼りに母に話しているものの、見事に「さっくん🩷佐久間大介くん」にハマり、今に至っておりますwww<br><br>
        <br><br>
        こんな私ですが、是非仲良くしてください⛄<br><br>
        <br><br>
        菊池風磨くん、京本大我くん、向井康二くん世代 × 中島裕翔くん月日ですが、私よりも年下の方、ぜひタメ語で絡んでください(笑)。
      </p>
      <img src="https://raw.githubusercontent.com/Hikari-Hikaru/HIKARI-introdaction/main/da1.webp" alt="おでかけ写真4" onclick="openModal(this.src)">
    </div>

  </main>

  <footer>
    © 2025 HIKARI-HIKARU
  </footer>

  <!-- モーダル -->
  <div id="modal" onclick="closeModal()">
    <img id="modal-img" src="" alt="拡大画像">
  </div>

  <script>
    function openModal(src) {
      document.getElementById('modal').style.display = 'block';
      document.getElementById('modal-img').src = src;
    }

    function closeModal() {
      document.getElementById('modal').style.display = 'none';
    }
  </script>
</body>
</html>
