<template>
    <section class="player-settings">
        <input type="text" class="nickname" placeholder="Enter your name">
        <select name="" id="">
            <option value="heb">Hebrew</option>
            <option value="eng">English</option>
        </select>

        <button @click="onPlay()" class="btn play full">Play!</button>
        <button @click="onCreateRoom()" class="btn create-prv-room full">Create Private Room</button>
    </section>
</template>
  
<script>
export default {
    name: 'player-settings',

    data() {
        return {
        }
    },

    computed: {
    },

    created() {
    },

    methods: {
        onPlay() {
            console.log('Play!')
        },
        onCreateRoom() {
            this.$emit('create-room')
        }
    }

}
</script>