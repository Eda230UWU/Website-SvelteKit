<div class="dropdown">
    <p>Dropdown Menu</p>
    <p>Option 1</p>
    <p>Option 2</p>
    <p>Option 3</p>
</div>

<style>
    div.dropdown{
        flex-direction: column;
        display: flex;
        background-color: #333333;
        width: 20vh;
        margin-left: 5vh;
        height: 40px;
        align-items: center;
        max-height: 40px;
        overflow: hidden;
        transition: all 0.3s;
    }


    div.dropdown:hover    {
        height: 160px;
        max-height: 160px;
    }

    div.dropdown p {
        padding: 0px;
        margin: 10px;
        margin-left: 10px;
    }

</style>