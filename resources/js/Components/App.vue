<template>
    <div class="container mx-auto">
        <header>
            <h1>Laracasts</h1>
        </header>

        <main class="flex">
            <router-link to="/">Home</router-link> |
            <router-link to="/about">About</router-link> |
            <router-view></router-view>
        </main>
    </div>

</template>

<script>
export default {

}
</script>

<style scoped>

</style>
