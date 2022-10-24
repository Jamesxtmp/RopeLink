<script>
</script>
<div class="navbar">
    <div class="navbarBack">
        <i class="secondary fa-solid fa-house-chimney"></i>
        <i class="primary fa-solid fa-plus"></i>
        <i class="secondary fa-solid fa-pencil"></i>
    </div>
</div>
<style>
    .navbar{
        position: absolute;
        display: flex;
        bottom: 50px;
        right: 0;
        left: 0;
        justify-content: center;
    }
    .navbarBack{
        /* background-color: aqua; */
        display: flex;
        align-items: flex-end;
    }
    .navbarBack i {
        background-color: var(--background2);
        display: flex;
        justify-content: center;
        align-items: center;
        border-radius: 50%;
        margin: 0 2px;
    }
    .secondary{
        width: 12vw;
        height: 12vw;
    }
    .primary{
        font-size: 2em;
        width: 18vw;
        height: 18vw;
    }
    
</style>