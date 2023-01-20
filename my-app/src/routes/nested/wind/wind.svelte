<div href="/gall/gallery_tiles" class="pic" >

    <div class="box"> 
        <div class="load"></div> 
        <a href="/gall/gallery_tiles">Examples of my art</a>
    </div>
</div>
<style>
    a {
        text-decoration: none;
        text-decoration: underline;
        margin: 24px 0px 0px 25px;
        font-size: 25px; 
        color: black;
        cursor: pointer;
    }
    div.load {
        align-self: flex-start;
        justify-self: flex-end;
        width: 0px;
        height: 5px;
        background-color: #3700ffcc;
        animation-duration: 20s;
        animation-name: load;
        animation-iteration-count: infinite;
        animation-delay: 3s;
        animation-timing-function: linear;
        
    }
    @keyframes load {
        from {width: 0%;}
        to {width: 100%;}
    }

    div.pic {
        background-image: url('/wind.png');
        background-size: 500%;
        background-position: 2560px;
        max-width: 512px;
        max-height: 384px;
        align-self: flex-start;
        justify-self: flex-start;
        border-radius: 25px;
        background-color: rgba(27, 27, 27, 0.219);
        animation-name: example;
        animation-duration: 20s;
        animation-iteration-count: infinite;
        animation-fill-mode: backwards;
    }

    @keyframes example {
        0% {background-position: 2560px;}
        15% {background-position: 2560px;}
        16% {background-position: 2048px;}
        36% {background-position: 2048px;}
        37% {background-position: 1536px;}
        60% {background-position: 1536px;}
        61% {background-position: 1024px;}
        85% {background-position: 1024px;}
        86% {background-position: 512px;}
        100% {background-position: 512px;}
        

} 

        


    div.box {
        overflow: hidden;
        
        width: 512px;
        height: 384px;
        border-radius: 25px;
        border: 5px;
        border-color: #2c2c2c;
        background-position: 0cm; 
        background-repeat: no-repeat;
        background-color: rgba(0, 114, 214, 0.281);
        transition: 0.5s;
        
}

    div.box:hover {

        background-color: rgba(0, 126, 236, 0.096);

    }
</style>