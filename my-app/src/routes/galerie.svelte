<svelte:head>
  <link
    rel="icon"
    type="image/png"
    href="icon{Math.floor(Math.random() * 6 + 1)}.png"
  />
</svelte:head>

<div class="main">
  <h1>Galerie s Kočkoholkama</h1>
  <i>Azuki je život, Coconut je láska</i>
</div>

<div class="navbar">
  <a href="/Sex_2_Leaks">Sex 2 leaks</a>

  <a  id="current" href="/galerie">Galerie</a>
  <a href="/" style="float:right">Home</a>
</div>

<div class="Side1">
  <h1>MOTD: Trnka je homoklád</h1>
  <p>Trnkuv test byl sracka</p>
  <p id="SideEnd">sidebar diniger</p>
</div>

<div class="Main1">
  <h1>KOCKOHOLKA KOCKOHOLKA</h1>
  <p>Fakt moc miluju kočkoholky</p>

  <!-- svelte-ignore a11y-missing-attribute -->
  <img src="maple.jpg" />
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
  }

  div.Main1 {
    overflow: hidden;
    width: calc(85% - 30px);
    margin-left: 15px;
    margin-right: 15px;
    background-color: #2c2c2c;
  }

  .Main1 img {
    display: block;
    padding: 12px;
    width: 240px;
    height: 180px;
    margin-left: 12px;
    margin-top: 0px;
    padding-left: 0px;
  }

  .Main1 h1 {
    margin: 0px;
  }

  div.Side1 {
    overflow: hidden;
    width: calc(15% - 15px);
    background-color: #2c2c2c;
    float: right;
    margin-right: 15px;
  }
  .Side1 h1 {
    margin-bottom: 0px;
    font-size: 15px;
  }

  .main h1 {
    margin-top: 0px;
    margin-bottom: 0px;
    color: #ffffff;
    font-size: 32px;
  }

  .main p {
    color: #ffffff;
    margin-bottom: 0px;
    padding-bottom: 0px;
  }

  a#current {
    color: #ffffff;
    text-shadow: 0px 0px 2px #b6b6b6;
  }

  p#SideEnd {
    margin-bottom: 12px;
  }
</style>
