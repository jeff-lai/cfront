<template>
    <div>
        <v-header></v-header>
        <!--        <router-view></router-view>-->
    </div>

</template>

<script>
    import vHeader from '../components/Header'

    export default {
        name: 'Home',
        components: {
            vHeader,
        }
    }
</script>
