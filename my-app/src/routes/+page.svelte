<svelte:head>
  <link
    rel="icon"
    type="image/png"
    href="icon{Math.floor(Math.random() * 6 + 1)}.png"
  />
  <title>Homepage</title>
</svelte:head>

<script>
  import Navbar from '/src/routes/nested/navbar/navbar.svelte';
  import Page_end from '/src/routes/nested/page_end/page_end.svelte';
  import Sidebar from '/src/routes/nested/sidebar/sidebar.svelte';
  import Dropdown from '/src/routes/nested/dropdown_menu/dropdown_menu.svelte';
  import Wind from './nested/wind/wind.svelte';
</script>

<div class="backg">

  <Navbar></Navbar>

  <div class="intro">
    <h1>Welcome to my Homepage!</h1>
    <i>This is just a little website i've made in my free time, so feel free to hang out</i>
  </div>

  <div class="main">
    <div class="mb1">
      <div>
        <h1>About me</h1>
        <p>Hello, my name is Eduard. I'm in my second year of high school and I'm studying cybersecurity. My hobbies include digital art, programming, videogames and anime. <br> If you'd like to see my "art" you can go to the gallery tab.</p>
      </div>  
      <div>
        <Wind></Wind>
      </div>
      
    </div>  

    

  </div>






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

