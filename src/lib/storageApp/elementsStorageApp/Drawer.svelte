<script>
    import { onMount } from 'svelte'
    let drawer
    const drawerData = {
        title: 'Cajon1',
        icon: '🥇',
        elements: 1,
        color: '#00ffff7e',
    }
    onMount(()=>{
        drawer.style.backgroundColor = drawerData.color
    })
    
</script>

<div bind:this={ drawer } class="drawer">
    <div class="title">{ drawerData.icon }{ drawerData.title }</div>
    <div class="elements">{ drawerData.elements } {drawerData.elements == 1 ? 'elemento' : 'elementos'}</div>
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
        font-size: .8em;
        text-align: right;
    }
</style>