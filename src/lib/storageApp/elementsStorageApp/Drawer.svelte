<script>
    import { onMount } from 'svelte'
    let drawer
    const drawerData = {
        title: 'Cajon1',
        icon: '🥇',
        elements: 1,
        color: '#00ffff7e',
        atributes: [
            
        ]
    }
    onMount(()=>{
        drawer.style.backgroundColor = drawerData.color
    })
    
</script>

<div bind:this={ drawer } class="drawer">
    <div class="title">{ drawerData.icon }{ drawerData.title }</div>
    <div class="elements">
        <div class="elementsL">
        </div>
        <div class="elementsR">
            { drawerData.elements } {drawerData.elements == 1 ? 'elemento' : 'elementos'}
        </div>
    </div>
</div>

<style>
    .drawer{
        padding: 4px;
        border-radius: 8px;
    }
    .title{
        font-size: 1.8em;
    }
    .elements{
        display: flex;
        justify-content: space-between;
        font-size: .8em;
    }
    .elementsL{
        padding: 0 16px;
    
    }
    .elementsR{
        text-align: right;
        padding-right: 8px;
    }
</style>