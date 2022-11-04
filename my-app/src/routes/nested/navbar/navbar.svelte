<div class="navbar">
    <div class="left" />
    <div class="center">
        <a href="/gallery">Gallery</a>
        <a href="/">Home</a>
    </div>
    <div class="right">
        <a id="r">Menu</a>

        <div class="menu">
            <br>
            <a>Home</a><br>
            <a>Home</a><br>
            <a>Home</a><br>
            <a>Home</a><br>
        
        </div>
    </div>
</div>



<style>
    div.navbar {
        justify-content: center;
        display: flex;
        align-items: center;
        flex-direction: row;
        background-color: #2c2c2c;
        margin: 0px;
        height: 64px;
        max-height: 64px;
    }

    .navbar a {
        max-width: fit-content;
        display: flex;
        text-decoration: none;
        padding: 6px 8px 6px 16px;
        font-size: 18px;
        color: #b6b6b6;
        text-align: right;
        cursor: pointer;
        margin: 0px;
        transition: 0.5s;
    }
    .navbar a:hover {
        text-shadow: #b6b6b6 0px 0px 4px;
        color: #e6e6e6;
    }

    div.left {
        flex-grow: 2;
    }
    div.center {
        display: flex;
        flex-direction: row;
        flex-grow: 2;
        align-content: center;
        justify-content: center;
       
    }
    div.right {
        position: relative;
        display: flex;
        justify-content: end;
        flex-direction: row;
        flex-grow: 2;
        align-content: center;
        transform-origin: bottom left;
        overflow: hidden;
    }
    div.right a {
        justify-self: center;
        align-self: flex-end;
        max-width: fit-content;
        padding: 0px;
        padding-right: 25px;
     
    }

    div.menu {
        display: flex;
        width: 20vh;
        position: absolute;
        overflow: hidden;
        height: 0px;
        max-height: 0px;
        transition: all 5s;
        flex-direction: column;
        justify-items: flex-end;
    }
    div.menu a{
        position: relative;
    }

    a:hover ~ .menu {
        overflow: visible;
        max-height: 40vh;
        height: 40vh;
        background-color: #2c2c2c;

    }
    div.menu:hover {
        overflow: visible;
        max-height: 40vh;
        height: 40vh;
        background-color: #2c2c2c;
    }

    

    /*div.right a:hover {

        width: 10vh;
        height: 40vh;
        padding-right: 25px;
    } */
</style>
