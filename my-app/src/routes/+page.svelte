<script>
  import Navbar from "/src/routes/nested/navbar/navbar.svelte";
  import Page_end from "/src/routes/nested/page_end/page_end.svelte";
  import Github from "./nested/github_link/github_link.svelte"
  import Vec from "./nested/vtipna_zluta_vec/viptna_zluta_vec.svelte"
  import Sidebar from "/src/routes/nested/sidebar/sidebar.svelte";
  import Dropdown from "/src/routes/nested/dropdown_menu/dropdown_menu.svelte";
  import Wind from "./nested/wind/wind.svelte";
</script>

<svelte:head>
  <link
    rel="icon"
    type="image/png"
    href="/icon{Math.floor(Math.random() * 6 + 1)}.png"
  />
  <title>Homepage</title>
</svelte:head>

<Navbar />

<div class="horizontal_line"></div>

<div class="main">
  
    <div class="sidebar">
      <h2>Projects</h2>
      
      <div class="side_box_1">
        <h3>AI-chan</h3>
        <i>design and art</i>
        <p>status: in progress</p>
      </div>

      <div class="side_box_1">
        <h3>Web for AI-chan</h3>
        <i>frontend</i>
        <p>status: on hold</p>
      </div>

    </div> 
  <div class="vertical_line"></div>
    <div class="quick">
      <h2>Quick access</h2>
        <div style="flex-direction: row;">
          <div style="width: 10px;"/>
          <Vec/>
          <div style="width: 50px;"/>
          <Github/>
          <div style="width: 50px;"/>
          <Wind/>
        </div>
        <div style="margin-top: 50px" class="horizontal_line"></div>

      </div>
    
  
  <div class="vertical_line"></div>
      <div class="idk mlsoun gmaer">
        <h2>lmao jsem linej</h2>

      </div>
  <div class="menu">

  </div>
</div>
   

<Page_end />

<!--- //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// -->
<style>
  .horizontal_line {
    width: 98%;
    height: 2px;
    background-color: #2c2c2c;
    margin: 0% 1% 0% 1%;
    
  }

  h2 {
    font-size: 52px;
    margin-top: 0px;
  }

  div.quick {
    align-self: flex-start;
    display: flex;
    flex-direction: column;
    background-color: #000000;
    padding-bottom: 20px;
    width: auto;
  }

  div.vertical_line{
    background-color: #2c2c2c;
    width: 1px;
    min-height: 65vh;
    height: 98%;
    margin: 1% 20px 1% 20px;
  }

  div.sidebar{
    width: 20vw;
    align-self: flex-start;
    height: 100%;
    flex-direction: column;
    justify-content: flex-start;
  }
  div.sidebar h3 {
    color: white;
    margin-bottom: 0px;
    font-size: 34px;
    margin-top: 6px;
  }
  div.sidebar p{
    font-size: 20px;
    margin-top: 12px;
  }
  div.sidebar i {
    font-size: 18px;
    padding: 0px;  
    padding-bottom: 5px;
  }
  
  div.side_box_1{
    background-color: #1f1f1f;
    padding: 12px;
    margin: 0px 12px 24px 12px;
    border-radius: 12px;
  }
  
  .quick h1 {
  }

  .quick i {
    padding: 0px;
    margin-top: 0px;
  }

  div.main {
    padding: 25px 50px 50px 20px;
    display: flex;
    flex-direction: row;
    align-content: flex-start;
    justify-content: flex-start;
    background-color: #000000;
    align-items: center;
    width: auto;
    height: auto;
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
  
</style>
