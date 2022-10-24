<div class="TopBar">
    <div class="LeftContain">
        <i class="fa-solid fa-chevron-left"></i>
        <i class="fa-solid fa-database"></i>
    </div>
    <div class="RigContain">
        <i class="fa-solid fa-filter"></i>
        <i class="fa-solid fa-plus"></i>
    </div>
</div>
<style>
    .TopBar{
        background-color: var(--primaryColor);
        height: 40px;
        display: flex;
        justify-content: space-between;
    }
    .TopBar > div {
        display: flex;
        align-items: center;
    }
    .LeftContain{
        padding-left: 16px;
    }
    .RigContain{
        padding-right: 16px;
    }
    .RigContain > i {
        margin-left: 16px;
    }
    .LeftContain i {
        margin-right: 8px;
    }
</style>