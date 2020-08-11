<template>
    <nav>
        <h1>NavBar</h1>
        <div>
            <ul>
                <li v-for="mnuItem in arrMenu" v-bind:key="menuArray.id">
                    <NavItem :menu="menuArray"/>
                </li>
            </ul>
        </div>
    </nav>
</template>

<script>
    import NavItem from './NavItem';

    export default {
        name: 'NavBar',
        components: {
            NavItem
        },
        props: {
            menus: Array
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    nav {
        background-color: gray;
    }
</style>
