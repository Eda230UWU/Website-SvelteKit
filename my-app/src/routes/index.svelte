<svelte:head>
  <link rel=icon type="image/png" href="icon{Math.floor(Math.random()*6+1)}.png">

 
</svelte:head>

<div class="main">


  <h1>Eda230UWU main page</h1>
  <p>nuck figgers</p>


</div>

<div class="navbar">

    <ul class="navbar">
      <li><a href="localhost:3030">Home screen</a></li>
    </ul>
 
</div>





<style>
* {
    box-sizing: border-box;
    
    font-family: Arial;

}



div.main{
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
  width: auto;
  height: auto;
  z-index: 1;
  top: 0;
  left: 0;
  text-align: left;
  margin-top: 0px;
  
}

ul.navbar{
  list-style-type: none;
}

.navbar a {
  
  padding: 6px 8px 6px 16px;
  text-decoration: none;
  font-size: 18px;
  color: #b6b6b6;
  display: block;
  text-align: left;
}



h1 {

  margin-top: 0px;
  color: #ffffff;
  font-size: 18px;
  
  
}

p {
  color: #ffffff;
  
}

</style>