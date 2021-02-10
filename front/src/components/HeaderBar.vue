<template>
    <div class="header-container">
        <div id="headerBar">
            <h1>PostApp</h1>
            <ul class="navbar-unlogged">
                <li>Home</li>
                <li>Login</li>
                <li>Signup</li>
            </ul>
        </div>
    </div>
</template>

<script>
    export default {
    }
</script>

<style lang="scss" scoped>
.header-container {
    background-color: #45AAF2;
}

h1 {
    font-family: 'Lobster', cursive;
    font-size: 2.1em;
}

a:hover {
    text-decoration: underline;
}

#headerBar {
    width: 70%;
    height: 8vh;
    margin: auto;
    display: flex;
    justify-content: space-between;
    color: white;
    align-items: center;
    ul {
        width: 30%;
        display: flex;
        justify-content: space-between;
        list-style: none;
        li {
            font-size: 1.5em;
            font-weight: 400;
            font-family: 'Roboto', sans-serif;
        }
    }
}
</style>