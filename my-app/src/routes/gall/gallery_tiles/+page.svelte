<svelte:head>
  <link
    rel="icon"
    type="image/png"
    href="icon{Math.floor(Math.random() * 6 + 1)}.png"
  />
  <title>Homepage</title>
</svelte:head>

<script>
    import Page_end from "/src/routes/nested/page_end/page_end.svelte";
    import Navbar from "../../nested/navbar/navbar.svelte";
  </script>

<div class="backg">
    <Navbar></Navbar>
    <Page_end></Page_end>
</div>


<!--- //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// -->


<style>

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
    display: flex;
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
  .main h1 {
    padding: 0px;
    align-self: flex-start;
    margin-top: 24px;
    font-size: 25px;
  }
  .main p {
    margin-top: 0px;
    padding: 0px;
    align-self: flex-start;
  } 
  div.mb1 {
    flex-direction: row;
    align-self: flex-start;
    margin: 0px;
    margin-left: 25px;
    padding: 0px;
    max-width: 60vh;
  }






   

</style>
