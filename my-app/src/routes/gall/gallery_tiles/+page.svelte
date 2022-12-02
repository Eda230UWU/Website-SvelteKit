<svelte:head>
  <link
    rel="icon"
    type="image/png"
    href="../../icon{Math.floor(Math.random() * 6 + 1)}.png"
  />
  <title>Homepage</title>
</svelte:head>

<script>
    import Page_end from "/src/routes/nested/page_end/page_end.svelte";
    import Navbar from "../../nested/navbar/navbar.svelte";
  </script>

<div class="backg">
    <Navbar></Navbar>
    <div class="intro">
      <h1>Gallery in a grid</h1>
      <i>This is just a gallery. Nothing really special about this one.</i>

    </div>


    <div class="main" style="margin-top:0px" >
      
      <div class="box_bg">
        <div class="box">
          <h2>name</h2>
          <div class="img_box">

            <img href="" class="img" alt="alt">
          </div>

        </div>
        
      </div>  

      <!-- epic -->
      
      <div class="box_bg">
        <div class="box">
          <h2>name</h2>
          <div class="img_box">

            <img href="" class="img" alt="alt">
          </div>

        </div>
        
      </div>  

      <!-- epic -->

      <div class="box_bg">
        <div class="box">
          <h2>name</h2>
          <div class="img_box">

            <img href="" class="img" alt="alt">
          </div>

        </div>
        
      </div>  

      <!-- epic -->

      <div class="box_bg">
        <div class="box">
          <h2>name</h2>
          <div class="img_box">

            <img href="" class="img" alt="alt">
          </div>

        </div>
        
      </div>  

      <!-- epic -->

      <div class="box_bg">
        <div class="box">
          <h2>name</h2>
          <div class="img_box">

            <img href="" class="img" alt="alt">
          </div>

        </div>
        
      </div>  

      <!-- epic -->
    
    
    </div>

    


    <Page_end></Page_end>
</div>


<!--- //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// -->


<style>



  div.box_bg {
    
    border-radius: 25px;
    background: linear-gradient(to bottom, #242424, #242424) padding-box,
      linear-gradient(to bottom, #00aeff, #00aeff00) border-box;
    width: 100%;
    border: 2px solid transparent;

  }
  div.box {
    margin: 2px;

  }  



  div.intro {
    display: flex;
    flex-direction: column;
    background-color: #2c2c2c;
    margin: 25px;
    align-items: center;
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
    background-color: #2c2c2c;
    margin: 25px;
    align-items: center;
    padding: 15px;
    width: auto;
    height: auto;
    padding-left: 30px;
  }







   

</style>
