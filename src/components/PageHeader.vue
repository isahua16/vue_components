<template>
    <div>
        <h1>LOGO</h1>
        <nav>
            <a href="">About</a>
            <a href="">Store</a>
        </nav>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    div {
        display: grid;
        place-items: center;
        grid-template-columns: 1fr 1fr;
    }

    nav {
        display: grid;
        grid-auto-flow: column;
        place-items: center;
        column-gap: 12px;
    }

    a {
        text-decoration: none;
        color: black;
    }

</style>