<script context="module">
    import { writable } from "svelte/store";
    export let menu_width = writable(0);
</script>


<div style:width="{$menu_width}px" class="side">
    <a href="/">HOMEPAGE</a>
    <a href="/gall/gallery_tiles">GALLERY</a>
    <a href="/testing">TESTING</a>
</div>



<style>
    .side {
        margin-top: 20px;
        transition: all, 1s;
        overflow: hidden;
        align-content: center;
        justify-content: flex-start;
        align-self: flex-start;
        height: 100vh;
    }
    a {
        margin-top: 12px;
        margin-right: 20px;
        font-size: 36px;
        color: rgb(141, 141, 141);
        text-decoration: none;
        transition: all 0.5s;
    }

    a:hover{
        color: white;
        text-shadow: #b6b6b6 0px 0px 12px;

    }

</style>
