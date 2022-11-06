<script>
  import Page_end from "/src/routes/nested/page_end/page_end.svelte";
  import Navbar from "../../nested/navbar/navbar.svelte";
</script>

<svelte:head>
  <link
    rel="icon"
    type="image/png"
    href="../icon{Math.floor(Math.random() * 6 + 1)}.png"
  />
  <title>UWU Galerie</title>
</svelte:head>

<Navbar />
<div class="backg">
  <div class="main">
    <h1>My Gallery</h1>
    <p>
      This is sort of a timeline of what my drawing used to look like to how
      they look like now.<br /> <i> You can navigate through the topright menu to "Gallery
      Tiles" for a grid like one</i>
    </p>
  </div>

  <div class="Main1">
    <h1>Kreslení rolehraní</h1>

    <div class="MainBox1">
      <h2>Maple Chibi (moje první kresba)</h2>
      <img id="MapChib" src="/galerie/MapleChibi.png" alt="MapleChibi.png" /><br
      />
      <i
        >Dokončeno na konci května 2021, tohle jsem kreslil s tabletem spolužáka</i
      >
    </div>

    <div class="MainBox1">
      <h2>Chisato meow but a Catgirl</h2>
      <img
        id="chis1"
        src="/galerie/Chisato Catgilr.png"
        alt="Chisato Catgril.png"
      /><br />
      <i>Dokončeno 2.9.2022 (první kresba s novým tabletem)</i>
    </div>

    <div class="MainBox1">
      <h2>Oči rolehraní</h2>
      <i>Head, Eyes</i> <br />
      <div class="MainBox2">
        <img id="eyes" src="/galerie/Eye1.png" alt="Eye1.png" /> <br />
        <i>Dokončeno 5.9.2022</i>
      </div>
      <div class="MainBox2">
        <img id="eyes" src="/galerie/Eye2.png" alt="Eye1.png" /> <br />
        <i>Dokončeno 6.9.2022</i>
      </div>
    </div>

    <div class="MainBox1">
      <h2>Azuki</h2>
      <img id="Azuki1" src="/galerie/Azuki1.png" alt="Azuki.png" /><br />
      <i>7.10.2022</i>
    </div>

    <div class="MainBox1">
      <h2>Hayasaca</h2>
      <img id="Hayasaca1" src="/galerie/hayasaca.png" alt="Hayasaca.png" /><br
      />
      <i>25.10.2022</i>
    </div>

    <div class="MainBox1">
      <h2>Misaka Mikoto</h2>
      <img id="Misaka1" src="/galerie/misaka_face.png" alt="Misaka.png" /><br />
      <i>3.11.2022</i>
    </div>
  </div>
</div>
<Page_end />

<!--- //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// -->
<style>
  div.main {
    background-color: #2c2c2c;
    border: 100px;
    border-color: #4e4e4e;
    margin: 50px 25px 25px 25px;
    padding: 15px;
    text-align: center;
    width: auto;
    height: auto;
  }
  img {
    max-height: 90vh;
  }


  /*.backg {
    width: 100%;
    background-image: linear-gradient(to right, #280085,#003c8a 10%, #003c8a 90%,#280085 100%);
  } */

  .backg {
    width: 100%;
    background-color: #003c8a;
  }

  div.Main1 {
    margin-right: 25px;
    margin: 0px 25px 15px 25px;
    background-color: #2c2c2c;
    
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
