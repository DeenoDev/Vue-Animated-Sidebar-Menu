<template>
    <div class="sidebar">
        
    </div>
    
</template>

<script>
export default {
        props: {},
        setup(){
            
        }
    }
</script>

<style>
:root {
    --sidebar-bg-color: #2f855a;
    --sidebar-bg-color: #38a169;
    --sidebar-bg-color: #276749;
}
</style>

<style scoped>
.sidebar {
    color: white;
    background-color: var(--sidebar-bg-color);

    float: left;
    position: fixed;
    z-index: 1;
    top: 0;
    left: 0;
    bottom: 0;
    padding: 0.5em;

    display: flex;
    flex-direction: column;
}

</style>