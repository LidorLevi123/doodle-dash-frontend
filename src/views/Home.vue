<template>
    <section class="home">
        <img alt="Vue logo" src="https://skribbl.io/img/logo.gif" class="logo">
        <PlayerSettings @create-room="createRoom()"/>
    </section>
</template>
  
<script>
import PlayerSettings from '../cmps/PlayerSettings.vue'
import { utilService } from '../services/util.service.js'

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
        createRoom() {
            const gameId = utilService.makeId()
            this.$router.push(`game/${gameId}`)
        }
    },

    components: {
        PlayerSettings
    }

}
</script>