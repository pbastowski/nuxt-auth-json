<template>
    <div>
        <h1>Component TEST</h1>
        text: <input :value="text" @input="e => (text = e.target.value)" />
        <pre>{{ text }}</pre>
    </div>
</template>

<script>
export default {
    data: () => ({
        text: '123'
    }),

    created() {},

    mounted() {},

    watch: {
        text(nv, ov) {
            console.log(nv)
        }
    }
}
</script>
