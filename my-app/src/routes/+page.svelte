<svelte:head>
  <link
    rel="icon"
    type="image/png"
    href="icon{Math.floor(Math.random() * 6 + 1)}.png"
  />
  <title>Homepage</title>
</svelte:head>

<script>
  import Navbar from './nested/navbar/navbar.svelte';
  import Page_end from './nested/page_end/page_end.svelte';
  import Sidebar from './nested/sidebar/sidebar.svelte'
  import Dropdown from './nested/dropdown_menu/dropdown_menu.svelte'
</script>

<Navbar></Navbar>



<div class="main">
  <h1>Welcome to my homepage!</h1>
  <i>Feel free to browse a bit</i>
</div>


<div class="row">

  

  <div class="Main1">
    <h1>Náhodné CSS styly</h1>
    <Dropdown/> <br>
    <Dropdown/>
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
    margin-left: 25px;
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

