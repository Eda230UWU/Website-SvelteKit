<svelte:head>
  <link
    rel="icon"
    type="image/png"
    href="../../icon{Math.floor(Math.random() * 6 + 1)}.png"
  />
  <title>Homepage</title>
</svelte:head>

<script>
    import Page_end from "../../nested/page_end/page_end.svelte";
    import Navbar from "../../nested/navbar/navbar.svelte";
  </script>

<div class="backg">
    <Navbar/>
    <div style="flex-directions: collumn; padding-left: 20px; background-color: #000000">
      <div class="main">
        <div class="intro">
        <h2 style="margin-bottom: 0px">Gallery</h2>
        <i style="padding-top: 0px">grid grid grid</i>
        <p> gaming</p>
        <div class="horizontal_line"/>

        
        </div> 


        <div class="horizontal_line"/>

      </div>
      <div id="menu" class="menu"></div>

    </div>
    <Page_end/>
</div>


<!--- //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// -->


<style>

  .horizontal_line {
    width: 98%;
    height: 2px;
    background-color: #2c2c2c;
    margin: 0% 1% 0% 1%;
    
  }

  div.intro {
    display: flex;
    flex-direction: column;
    padding-bottom: 20px;
  }

  .intro h1 {
    margin: 20px;
  }

  .intro i {
    margin-top: 0px;
    margin-bottom: 20px;
  }

  .backg {
    width: 100%;
    background-color: #003c8a;
  }
 
  div.main {
    
    grid-template-columns: repeat(5, [coll1-start] 0%, [coll1-end] 1%, [coll2-start] 1%, [coll2-end] 19);
    grid-template-rows: repeat(5, auto);
    display: grid;
    align-content: flex-start;
    justify-content: flex-start;
    background-color: #000000;
    align-items: center;
    padding: 15px;
    width: auto;
    height: auto;
    padding-left: 30px;
  }







   

</style>
