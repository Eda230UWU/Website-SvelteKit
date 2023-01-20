<script>
  import Page_end from "/src/routes/nested/page_end/page_end.svelte";
  import Navbar from "../../nested/navbar/navbar.svelte";
</script>

<svelte:head>
  <link
    rel="icon"
    type="image/png"
    href="../../icon{Math.floor(Math.random() * 6 + 1)}.png"
  />
  <title>UWU Galerie</title>
</svelte:head>

<Navbar />
<div class="backg">
  <div class="main">
    <h1>My Gallery</h1>
    <p>
      This is sort of a timeline of what my drawing used to look like to how
      they look like now.<br />
      <i>
        You can navigate through the topright menu to "Gallery Tiles" for a grid
        like one</i
      >
    </p>
  </div>

  <div class="Main1">
    <h1>First artworks</h1>

    <div class="mb1">
      <h2>Chibi Maple Minaduki [Nekopara]</h2>
      <div class="mb2">
        <img
          id="MapChib"
          src="/galerie/MapleChibi.png"
          alt="MapleChibi.png"
        /><br />
        <i
          >This is my very first artwork I finished at the end of May 2022. My
          classmate lent me his drawing tablet in school almost everyday. Before
          this I only made some random sketches and didn't know much theory. As
          a result i drew everything on one layer (I think I didn't even
          separate lineart and colors). I didn't even pick colors myself and I
          just picked them from the reference image. I also don't like the thin
          lineart and white background</i
        >
      </div>
    </div>

    <div class="mb1">
      <h2>Chisato Nishikigi as a catgirl [Lycoris Recoil]</h2>

      <div class="mb2">
        <img
          id="chis1"
          src="/galerie/Chisato Catgilr.png"
          alt="Chisato Catgril.png"
        /><br />
        <i
          >This one i finished on 2nd of September 2022, few days after i bought
          my own drawing tablet. This is not my second drawing, nor my first
          finished drawing on this tablet. They looked really bad so i decided
          to not include them. Even though it turned out "ok" i didn't like her
          eyes. I also could've made the shading a bit sharper and my color
          picking is really bad. While there isn't almost any skin shading, the
          hair shading is very dark.</i
        >
      </div>
    </div>

    <div class="mb1">
      <h2>Eye drawing</h2>
      <div class="mb2">
        <div class="mb3">
          <div class="MainBox2">
            <img src="/galerie/Eye1.png" alt="Eye1.png" /> <br />
          </div>
          <div class="MainBox2">
            <img src="/galerie/Eye2.png" alt="Eye1.png" /> <br />
          </div>
        </div>
        <i
          >These two are drawings i made in three days after i finished my
          Chisato drawing. As I said, I wasn't satisfied with her eyes, so i
          watched a tutorial and tried to estabilish a style for my future
          drawings. I was really happy how it turned out.</i
        >
      </div>
    </div>

    <div class="mb1">
      <h2>Azuki Minaduki [Nekopara]</h2>
      <div class="mb2">
        <img id="Azuki1" src="/galerie/Azuki1.png" alt="Azuki.png" /><br />

        <i
          >This one was finished on 7th of October in 2022. I personally think
          this was a huge improvement from the Chisato one. I tried to do hard
          shading which really improved the drawing. The lineart is also a bit
          better and hile the eyes weren't so good i don't think they turned out
          badly. The red background also looks better than just a white/grey
          background. The only detail I would like to change is shading of her
          skin, especialy the face.
        </i>
      </div>
    </div>

    <div class="mb1">
      <h2>Hayasaka Ai [Kaguya-sama, love is war]</h2>
      <div class="mb2">
        <img id="Hayasaca1" src="/galerie/hayasaca.png" alt="Hayasaca.png" /><br
        />
        <i
          >I finished this artwork on 25th of October 2022. I think it turned
          out fine, except for her skin. I should pick more saturated colors and
          a bit more orange color for skin.</i
        >
      </div>
    </div>

    <div class="mb1">
      <h2>Misaka Mikoto [A certain scientific Railgun]</h2>
      <div class="mb2">
        <img id="Misaka1" src="/galerie/misaka_face.png" alt="Misaka.png" /><br
        />
        <i
          >Finished on 3rd of November 2022. This was a redraw of one scene. I
          think it turned out fine. The hair is pretty nice and the shading
          turned out very good. I don't like her hairpin tho. Also her skin is
          yellow (same issue as previous artwork).</i
        >
      </div>
    </div>
  </div>
</div>
<Page_end />

<!--- //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// -->
<style>
  div.main {
    
    background-color: #1d1d1d;
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
    background-image: linear-gradient(
      to right,
      #280085,
      #003c8a 40%,
      #003c8a 60%,
      #280085 100%
    );
  }
  */
  
  div.Main1 {
    margin-right: 25px;
    margin: 0px 25px 50px 25px;
    background-color: #1d1d1d;
  }

  div.mb2 {
    display: flex;
    flex-direction: row;
  }
  div.mb2 i {
    font-size: 24px;
  }

  div.MainBox2 {
    padding: 0px;
    margin: 0px;
    background-color: #1d1d1d;
    height: 100%;
    display: inline-block;
    width: max-content;
  }
  div.MainBox2 img {
    max-width: 40vh;
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

  div.mb1 {
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

  .mb1 img {
    height: fit-content;
    width: 100%;
    max-width: 80vh;
    padding: 0px 12px 0px 12px;
    margin: 0px;
  }
  .mb1 i {
    margin: 0px 0px 10px 12px;
    padding-bottom: 12px;
    padding: 0px;
  }

  h2 {
    font-size: 30px;
    margin: 0px;
    margin-bottom: 10px;
  }
</style>
