<template>
    <section class="user-list">
        <ul class="clean-list">
            <li v-for="user in users" :key="user._id">
                <UserPreview :user="user"/>
            </li>
        </ul>
    </section>
</template>

<script>
import UserPreview from './UserPreview.vue'
export default {
    props: {
        users: { type: Array }
    },

    methods: {

    },

    components: {
        UserPreview
    }
}
</script>