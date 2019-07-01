<template>
    <div class="header wrapper">

        <div id="nav">
            <router-link to="/">Home</router-link> |
            <router-link to="/about">About</router-link>
        </div>

    </div>

</template>

<script>
    export default {
        name: 'Header',
        components: {
        }
    }
</script>

<style lang="scss" scoped>
    .header {
        z-index: 1;
        padding: 20px 0;
        position: relative;
        .is-active {
            color: #e01b3c;
        }
        a {
            color: #000;
            text-decoration: none;
        }
        .menu-wrapper {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .menu {
            font-size: 25px;
            text-transform: uppercase;
            display: flex;
            justify-content: center;
            align-items: center;
            li {
                padding: 15px;
            }

        }
    }
</style>
