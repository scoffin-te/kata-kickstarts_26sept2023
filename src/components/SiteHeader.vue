<template>
    <header>
        <div id="site-logo">
            <img src="../../public/site-logo.png" />
        </div>
        <nav id="header-nav">
            <router-link v-bind:to="{ name: 'home' }">Home</router-link>
            <router-link v-bind:to="{ name: 'about' }">About Us</router-link>
        </nav>
    </header>
</template>

<style scoped>
</style>