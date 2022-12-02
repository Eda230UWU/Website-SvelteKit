<script>
  import Navbar from "/src/routes/nested/navbar/navbar.svelte";
  import Page_end from "/src/routes/nested/page_end/page_end.svelte";
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

<div class="backg">
  <Navbar />

  <div class="intro">
    <h1>Welcome to my Homepage!</h1>
    <i
      >This is just a little website I've made in my free time. Feel free to
      hang out.</i
    >
  </div>

  <div class="main">
    <div class="mb1">
      <div class="brd1">
        <h1>About me</h1>
        <p>
          Hello, my name is Eduard. I'm in my second year of high school and I'm
          studying cybersecurity. My hobbies include digital art, programming,
          videogames and anime. <br /> If you'd like to see my "art" you can go to
          the gallery tab.
        </p>
      </div>
      <div class="mb2">
        <Wind></Wind>
      </div>
    </div>
  </div>

  <Page_end />
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
    min-height: 100vh;
    width: 100%;
    background-color: #003c8a;
  }

  div.main {
    padding: 50px 25px 25px 50px;
    display: flex;
    align-content: flex-start;
    justify-content: flex-start;
    background-color: #2c2c2c;
    margin: 25px;
    margin-top: 0px;
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
  div.mb1 {
    width: 100%;
    flex-direction: row;
    align-self: flex-start;
    margin: 0px;
    padding: 0px;
    
  }

  div.brd1 {
    min-width: 40vh;
    max-width: 50vh;
    background: linear-gradient(to bottom, #242424, #242424) padding-box,
      linear-gradient(to bottom, #00aeff, #00aeff00) border-box;
    border-radius: 25px;
    border: 2px solid transparent;
    padding: 30px;
    padding-top: 10px;
  }

  div.mb2 {
    margin-left: 50px;
    justify-self: flex-start;
    align-self: flex-start;
  }
</style>
