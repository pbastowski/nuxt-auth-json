<template>
    <div>
        <h1>Home</h1>
        <nuxt-link to="public">public</nuxt-link>
        <nuxt-link to="secret">secret</nuxt-link>
        <nuxt-link to="profile">profile</nuxt-link>
        <Test></Test>
    </div>
</template>

<script>
import Test from '~/components/Test.vue'

export default {
    auth: false,
    components: { Test }
}
</script>
