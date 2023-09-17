<template>
    <section class="game">
        <img src="https://skribbl.io/img/logo.gif" class="logo" alt="">
        <GameBar />
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
    </section>
</template>
  
<script>
import GameBar from '../cmps/GameBar.vue';

export default {
    name: 'game',
    data() {
        return {};
    },
    computed: {},
    created() {
    },
    methods: {},
    components: { GameBar }
}
</script>