<template>
    <div id="header">
        <div class="brand">
            <span>Muhaafidz Portfolio</span>
        </div>
        <div class="nav">
            <router-link to="/">Home</router-link>
            <router-link to="/about">About</router-link>
        </div>
    </div>
</template>

<style lang="scss">
#header {
    padding: 26px;
    display: flex;
    justify-content: space-between;
    align-items: center;

    .brand {
        font-weight: bold;
        font-size: 30px;
        color: #b94287;
    }
    .nav {

        a {
            margin-left: 10px;
            font-weight: bold;
            color: #2c3e50;
            text-decoration: none;
            &.router-link-exact-active {
            color: #b94287;
            }
        }
    }
}
</style>