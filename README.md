<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>For My Love</title>
  <style>
    body {
      margin: 0;
      font-family: 'Comic Sans MS', cursive, sans-serif;
      background-color: pink;
      text-align: center;
    }
    .hidden {
      display: none;
    }
    .login-container, .letter-container {
      padding: 30px;
    }
    input {
      padding: 10px;
      margin: 5px;
      border: none;
      border-radius: 5px;
      font-size: 16px;
    }
    button {
      padding: 10px 20px;
      background-color: #ff69b4;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 16px;
      cursor: pointer;
    }
    img {
      max-width: 100%;
      border-radius: 10px;
      margin-top: 20px;
    }
    .letter {
      text-align: left;
      max-width: 700px;
      margin: 0 auto;
      background: rgba(255,255,255,0.9);
      padding: 20px;
      border-radius: 10px;
    }
  </style>
</head>
<body>

<audio autoplay loop>
  <source src="you_are_the_reason.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

<div class="login-container" id="loginPage">
  <h1>Welcome 💖</h1>
  <img src="Ella.jpg" alt="Landing Image"/>
  <p>Enter your love credentials ✨</p>
  <input type="text" id="username" placeholder="Username"><br>
  <input type="password" id="password" placeholder="Password"><br>
  <button onclick="login()">Login</button>
</div>

<div class="letter-container hidden" id="mainContent">
  <h1>My Sweet Letter to You 💌</h1>
  <img src="hotcake.jpg" alt="hotcake"/>
  <div class="letter">
    <p>To My Beautiful Love,</p>
    <p>I just want you to know how much you mean to me. Every day, I look at you and feel proud - not just because of what you do, but because of who you are. Here are 30 reasons I'm proud of you:</p>
    <ul>
      <li>I am proud of you because you never give up, even when things get really tough.</li>
      <li>I am proud of you because you show up for the people you love, no matter what.</li>
      <li>I am proud of you because you chase your dreams with so much passion and grace.</li>
      <li>I am proud of you because your heart is kind, generous, and always full of love.</li>
      <li>I am proud of you because you always try to do the right thing, even when it's hard.</li>
      <li>I am proud of you because you take care of others even when you're tired.</li>
      <li>I am proud of you because you're always learning, growing, and evolving.</li>
      <li>I am proud of you because you've turned your pain into strength.</li>
      <li>I am proud of you because you know your worth and never settle for less.</li>
      <li>I am proud of you because your laughter brightens up the darkest days.</li>
      <li>I am proud of you because you keep pushing forward even when no one's looking.</li>
      <li>I am proud of you because you hold your head high and carry yourself with dignity.</li>
      <li>I am proud of you because you're not afraid to be vulnerable and real.</li>
      <li>I am proud of you because you work so hard, and it never goes unnoticed.</li>
      <li>I am proud of you because you keep showing up for life, even when it's overwhelming.</li>
      <li>I am proud of you because you inspire others just by being yourself.</li>
      <li>I am proud of you because your beauty runs deeper than just the outside.</li>
      <li>I am proud of you because you're creative, thoughtful, and incredibly intelligent.</li>
      <li>I am proud of you because you trust me with your heart.</li>
      <li>I am proud of you because you make the little things feel magical.</li>
      <li>I am proud of you because you face your fears even when you're scared.</li>
      <li>I am proud of you because you take responsibility and own your actions.</li>
      <li>I am proud of you because you protect your peace and set boundaries.</li>
      <li>I am proud of you because you're not afraid to say sorry and mean it.</li>
      <li>I am proud of you because you lift others up without bringing yourself down.</li>
      <li>I am proud of you because you're honest and real, even when it's uncomfortable.</li>
      <li>I am proud of you because you make life better just by being in it.</li>
      <li>I am proud of you because you're my peace in a loud world.</li>
      <li>I am proud of you because you've grown so much and continue to grow.</li>
      <li>I am proud of you because you love me in a way that makes me want to be better.</li>
    </ul>
    <p>With all my love,<br>- [Ajayi Oluwagbemileke]</p>
  </div>
  <br>
  <a href="Reasons_Im_Proud_Of_You_Letter.pdf" download>
    <button>Download This Letter as PDF 💝</button>
  </a>
</div>

<script>
  function login() {
    const username = document.getElementById("username").value.trim();
    const password = document.getElementById("password").value.trim();
    if(username === "Emmanuella" && password === "4th November 2023") {
      document.getElementById("loginPage").classList.add("hidden");
      document.getElementById("mainContent").classList.remove("hidden");
    } else {
      alert("Oops! Wrong credentials. Try again, my love. 💔");
    }
  }
</script>

</body>
</html>
