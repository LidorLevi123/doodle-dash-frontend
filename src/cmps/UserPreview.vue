<template>
    <article class="user-preview">
        <span class="name">{{ user.name }}</span>
        <span class="points">{{ user.points }} points</span>
    </article>
</template>

<script>
export default {
    props: {
        user: { type: Object }
    },

    methods: {

    },
}
</script>