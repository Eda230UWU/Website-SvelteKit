<svelte:head>
  <link
    rel="icon"
    type="image/png"
    href="icon{Math.floor(Math.random() * 6 + 1)}.png"
  />
  <title>UWU home</title>
</svelte:head>

<script>
  import Page_end from './nested/page_end/page_end.svelte';
  import Sidebar from './nested/sidebar/sidebar.svelte'
</script>
<div class="main">
  <h1>Eda230UWU main page</h1>
  <i>O mě</i>
</div>

<div class="navbar">    
  <a href="/galerie">Galerie</a>
  <a id="current" href="/" style="float:right">Home</a>
</div>

<div class="row">

  

  <div class="Main1">
    <h1>Trochu o mě</h1>
    <p>
      Ahoj! Jmenuju se Daniel Bulant, alias The Tutorials a jsem mladý programátor. Umím programovat weby, tedy PHP,
      HTML a podobně, a taky aplikace, a to v sketchware a v android studiu. Též umím i lehce Python, kde jsem
      vytvořil prvního českého hudebního bota.
      <br>
      V čem pracuji?
      <br>
      Svoje weby hostuju u endora.cz. Používám ji již několik let a jsem s ní spokojený, jelikož mi na většinu webů
      stačí free, jen na některé větší projekty mám plus. Kódy webů píšu v editor atom.io, který je nejenom
      open-source, ale taky jeden z nejhezčích které znám. A funguje lépe než np++, i když by měli trošku zapracovat
      na optimizaci.
      <br>
      Aplikace většinou vytvořím ve sketchware, odkud pak exportuji do android studia, kde aplikace více upravím.
      Zkuste mojí tvorbu, například word finder jednoduchou hru, kde máte za úkol spojit písmena do anglických slov.
      <br>
      Jak mě můžete podpořit?
      <br>
      Podpořit mě můžete buďto ohodnocením mích aplikací či videí nebo na patreonu</p>
      
      
    </div>
    
    <Sidebar/>
    
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

  div.row {
    height: auto;
    display: flex;
  }

  div.Main1 {
    overflow: hidden;
    width: calc(85% - 30px);
    margin-left: 15px;
    margin-right: 15px;
    margin-bottom: 15px;
    background-color: #2c2c2c;
    height: 100%;
    min-height: calc(100vh - 260px);
  }

  .Main1 img {
    display: block;
    padding: 12px;
    width: 240px;
    height: 180px;
    margin-left: 12px;
    margin-top: 0px;
    padding-left: 0px;
    margin-bottom: 0px;
    padding-bottom: 0px;    
  }

  .Main1 h1 {
    margin: 0px;
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

  a#current {
    color: #ffffff;
    text-shadow: 0px 0px 2px #b6b6b6;
  }

  p#end {
    margin-bottom: 12px;
  }

   

</style>

