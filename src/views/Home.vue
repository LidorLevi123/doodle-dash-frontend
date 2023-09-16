<template>
    <section class="home">
        <img alt="Vue logo" src="https://skribbl.io/img/logo.gif">
        <PlayerSettings/>
    </section>
</template>
  
<script>
import PlayerSettings from '../cmps/PlayerSettings.vue'

export default {
    name: 'home',

    data() {
        return {
        }
    },

    computed: {
    },

    created() {
    },

    methods: {
    },

    components: {
        PlayerSettings
    }

}
</script>