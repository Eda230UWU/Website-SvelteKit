<svelte:head>
  <link
    rel="icon"
    type="image/png"
    href="icon{Math.floor(Math.random() * 6 + 1)}.png"
  />
  <title>UWU Galerie</title>
</svelte:head>

<script>
    import Page_end from '../nested/page_end/page_end.svelte';

</script>


<div class="main">
  <h1>Eda230UWU main page</h1>
  <i>Moje práce co se kreslení týče</i>
</div>

<div class="navbar">
  <a id="current" href="/galerie">Galerie</a>
  <a href="/" style="float:right">Home</a>
</div>

<div class="Main1">
  <h1>Kreslení rolehraní</h1>

  <div class="MainBox1">
    <h2>Maple Chibi (moje první kresba)</h2>
    <img id="MapChib" src="/galerie/MapleChibi.png" alt="MapleChibi.png"><br/>
    <i>Dokončeno na konci května 2021, tohle jsem kreslil s tabletem spolužáka</i>
  </div>

  <div class="MainBox1">
    <h2>Chisato meow but a Catgirl</h2>
    <img id="chis1" src="/galerie/Chisato Catgilr.png" alt="Chisato Catgril.png"/><br>
    <i>Dokončeno 2.9.2022 (první kresba s novým tabletem)</i>
  </div>

  <div class="MainBox1">
    <h2>Oči rolehraní</h2>
    <i>Head, Eyes</i> <br/>
    <div class="MainBox2">
      <img id="eyes" src="/galerie/Eye1.png" alt="Eye1.png" /> <br/>
      <i>Dokončeno 5.9.2022</i>
    </div>
    <div class="MainBox2">
      <img id="eyes" src="/galerie/Eye2.png" alt="Eye1.png" /> <br />
      <i>Dokončeno 6.9.2022</i>
    </div>
  
    
  </div>
  
  <div class="MainBox1">
      <h2>KryvasCZ kočkoholka</h2>
      <img id="KryCZ_catgirl" src="/galerie/KryvasCZ.png" alt="Eye1.png"/><br/>
      <i>Dokončeno 29.9.2022</i>
    </div>
  
</div>

<Page_end/>

<!--- //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// -->
<style>
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
    
    max-height: 90vh;
    padding: 0px 12px 0px 12px;
    margin: 0px;
    
  }

  img#eyes {
    height: fit-content;
    max-width: 100%;
    padding: 0px 12px 0px 12px;
    margin: 0px;
  }

  img#KryCZ_catgirl {
    max-height: 90vh;
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

</style>
