<script>
    import {menu_width} from "../menu/menu.svelte"
</script>

<div class="navbar">
    <div class="left" />
    <div class="center">
        <a href="/gall/gallery_tiles">Gallery</a>
        <a href="/">Homepage</a>
    </div>
    <div class="right">
        <a id="r" on:click={() => {if($menu_width === 0){$menu_width=400} else{$menu_width=0}}}>Menu</a>

        <!--<div class="menu">
                <div class="black">
                    <br style="margin: 1px;">
                    <!-svelte-ignore a11y-missing-attribute ->
                    <a style="margin-top: 2px;">Menu</a><br>
                    
                    <a href="/">Homepage</a><br>
                    <a href="/gall/gallery">Gallery Timeline</a><br>
                    <a href="/gall/gallery_tiles">Gallery Tiles</a><br>
                    <a href="/testing">Testing</a><br>
            </div>
        </div>-->
    </div>
</div>



<style>
    div.navbar {
        justify-content: center;
        display: flex;
        align-items: center;
        flex-direction: row;
        background-color: #000000;
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
        align-self: flex-start;
        height: 100%;
        position: relative;
        display: flex;
        justify-content: end;
        align-content: flex-end;
        flex-direction: row;
        flex-grow: 2;
        align-content: center;
        transform-origin: bottom left;
        overflow: visible;
    }
    div.right a {
        justify-self: center;
        max-width: fit-content;
        align-self: center;
        padding: 0px;
        padding-right: 25px;
        position: absolute;
    }

    div.menu {
        align-self: flex-start;
        background-image: linear-gradient(to bottom, #00878b, #00878b);
        overflow: hidden;
        display: flex;
        width: 182px;
        position: absolute;
        height: 0px;
        max-height: 0px;
        transition: all 1s;
        flex-direction: column;
        justify-items: flex-end;
        align-items: flex-end;
    }
    div.black {
        display: flex;
        background-color: #1d1d1d;
        height: inherit ;
        width: 180px;
        justify-items: flex-end;
        align-items: end;
    }
    div.menu a{
        padding: 0px 25px 0px 25px;
        position: relative;
        align-self: flex-end;
    }

    a:hover ~ .menu {
        max-height: 225px;
        height: 225px;
        background-color: #1d1d1d;

    }
    div.menu:hover {
        max-height: 225px;
        height: 225px;
        background-color: #1d1d1d;
    }


    

    /*div.right a:hover {

        width: 10vh;
        height: 40vh;
        padding-right: 25px;
    } */
</style>
