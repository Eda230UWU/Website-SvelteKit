<svelte:head>
  <link
    rel="icon"
    type="image/png"
    href="icon{Math.floor(Math.random() * 6 + 1)}.png"
  />
  <title>UWU Galerie</title>
</svelte:head>

<div class="main">
  <h1>Eda230UWU main page</h1>
  <i>nuck figgers</i>
</div>

<div class="navbar">
  <a href="/Sex_2_Leaks">Sex 2 leaks</a>

  <a id="current" href="/galerie">Galerie</a>
  <a href="/" style="float:right">Home</a>
</div>

<div class="Main1">
  <h1>Kreslení rolehraní</h1>
  <div class="MainBox1">
    <h2>Chisato meow but a Catgirl</h2>
    <img id="chis1" src="/Chisato Catgilr.png" alt="Chisato Catgril.png" />
    <i>Dokončeno 2.9.2022</i>
  </div>

  <div class="MainBox1">
    <h2>Oči rolehraní</h2>
    <i>Head, Eyes</i> <br />
    <div class="MainBox2">
      <img id="eyes" src="/Eye1.png" alt="Eye roleplay.png" /> <br />
      <i>Dokončeno 5.9.2022</i>
    </div>
    <div class="MainBox2">
      <img id="eyes" src="/Eye2.png" alt="Eye roleplay.png" /> <br />
      <i>Dokončeno 6.9.2022</i>
    </div>
  </div>
</div>

<div class="bottom">
  <div class="bottom1">
    <a href="https://github.com/Eda230UWU">GitHub<br /></a>
    <a href="https://steamcommunity.com/id/Azuki_Best_Girl/">Steam Account</a>
  </div>
</div>

<!--- //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// -->
<style>
  * {
    box-sizing: border-box;

    font-family: Arial;
  }

  h1 {
    color: #ffffff;
    font-family: Calibri;
    padding-top: 14px;
    padding-left: 12px;
    padding-right: 12px;
    padding-bottom: 14px;
  }

  h2 {
    color: #ffffff;
    font-family: Calibri;
    padding-top: 13px;
    padding-left: 12px;
    padding-right: 12px;
    padding-bottom: 5px;
    font-size: medium;
  }

  p {
    margin: 0px;
    color: #ffffff;
    font-family: Calibri;
    padding-top: 14px;
    padding-left: 12px;
    padding-right: 12px;
  }

  i {
    margin: 0px;
    color: #ffffff;
    font-family: Calibri;
    padding-top: 14px;
    padding-left: 12px;
    padding-right: 12px;
  }

  div.main {
    background-color: #2c2c2c;
    border: 100px;
    border-color: #4e4e4e;
    margin: 15px;
    padding: 15px;
    text-align: center;
    width: auto;
    height: auto;
  }

  div.navbar {
    background-color: #2c2c2c;
    margin: 15px;
    overflow: hidden;
    margin-top: 0px;
  }

  .navbar a {
    float: left;
    display: block;
    text-decoration: none;
    padding: 6px 8px 6px 16px;
    text-decoration: none;
    font-size: 18px;
    color: #b6b6b6;
    text-align: left;
    height: 32px;
  }

  div.Main1 {
    overflow: hidden;
    width: calc(100% - 30px);
    margin-left: 15px;
    margin-right: 15px;
    margin-bottom: 15px;
    background-color: #2c2c2c;
    height: 100%;
    min-height: calc(100vh - 260px);
  }

  div.MainBox2 {
    margin: 15px 0px 15px 15px;
    background-color: #2c2c2c;
    height: 100%;
    display: inline-block;
    width: max-content;
    
  }
  .Main1 h1 {
    margin: 0px;
    font-size: 72px;
    margin-left: 12px;
  }

  .Main1 i {
    margin-bottom: 24px;
    padding-bottom: 12px;
  }

  .main h1 {
    margin-top: 0px;
    margin-bottom: 0px;
    color: #ffffff;
    font-size: 32px;
  }

  div.MainBox1 {
    margin-left: 10px;
    float: left;
    border: 2px solid #6b6b6b;
    margin-right: 20px;
    padding-right: 60%;
    margin-bottom: 12px;
    padding: 12px;
    max-width: 100%;
    width: calc(100% - 30px);
  }

  img#chis1 {
    height: fit-content;
    max-width: 100%;
    padding: 0px 12px 0px 12px;
    margin: 0px;
  }

  img#eyes {
    height: fit-content;
    max-width: 100%;
    padding: 0px 12px 0px 12px;
    margin: 0px;
  }

  .MainBox1 img {
    height: fit-content;
    width: 100%;
    max-width: fit-content;
    padding: 0px 12px 0px 12px;
    margin: 0px;
  }
  .MainBox1 i {
    margin: 0px 0px 10px 12px;
    padding-bottom: 12px;
    padding: 0px;
  }

  a#current {
    color: #ffffff;
    text-shadow: 0px 0px 5px #6b6b6b;
  }
  p#end {
    margin-bottom: 12px;
  }
  div.bottom {
    width: 100%;
    height: 100px;
    background-color: #2b2b2b;

    font-size: 10px;
  }

  div.bottom1 {
    padding-top: 15px;
    margin-left: 25%;
  }

  div.bottom1 a {
    color: #b6b6b6;
    text-decoration: none;
  }
</style>
