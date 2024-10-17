<script setup>
import { RouterLink } from 'vue-router';

</script>

<template>
    <nav class="navbar">
        <a href="/">        
        <img src="https://images.pexels.com/photos/87146/pexels-photo-87146.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
            alt="Cafe logo" class="logo">
        </a>
        <div class="menu">
            <a href="/">Home</a>
            <a href="/about">About</a>
            <a href="/products">Products</a>
            <a href="/contact">Contacts</a>
        </div>
    </nav>

</template>

<style scoped>
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 20px;
    background-color: #555;
}

.logo {
    width: 190px;
    border-radius: 10%;
}

.menu {
    display: flex;
    gap: 20px;
    font-size: 1.4rem;
}

.menu a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}
</style>