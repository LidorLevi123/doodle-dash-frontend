<template>
    <section class="game">
        <img src="https://skribbl.io/img/logo.gif" class="logo" alt="">
        <GameBar />
        <UserList :users="users"/>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
    </section>
</template>
  
<script>
import GameBar from '../cmps/GameBar.vue';
import UserList from '../cmps/UserList.vue';

export default {
    name: 'game',
    data() {
        return {
            users: [
                { name: 'keyes', points: 230 }
            ]
        }
    },

    computed: {},

    created() {
    },

    methods: {},

    components: { 
        GameBar,
        UserList
     }
}
</script>