<script setup>
import MenuIcon from '/node_modules/vue-material-design-icons/Menu.vue'
</script>

<template>

    <nav class="nav">
        <span><a href="#">Fabrício Maxwell</a></span>
        <ul class="nav-list">
            <li><a href="#">Sobre</a></li>
            <li><a href="">Experiência</a></li>
            <li><a href="">Projetos</a></li>
            <li><a href="">Contato</a></li>
        </ul>
        <MenuIcon :size="35" />
    </nav>
</template>

<style scoped>
.nav {
    display: flex;
    justify-content: space-between;
    height: 100%;
    align-items: center;
    padding-inline: 40px;
    position: relative;
}

.nav .nav-list {
    display: flex;
    position: absolute;
    flex-direction: column;
    gap: 0.8rem;
    padding: 1rem;
    top: 60px;
    right: 44px;
    background-color: white;
    border-radius: 15px;
    box-shadow: 10px 10px 15px gray;
    


}


</style>