<template>
<div>
    <TemplateGrid>
        <img :src="img" :alt="title" width="200">
        <h2>{{ title }}</h2>
        <p>{{ description }}</p>
        <a :href="url">{{ url }}</a>
    </TemplateGrid>
</div>
</template>

<script>
    import TemplateGrid from './TemplateGrid.vue'

    export default {
        components: {
            TemplateGrid
        },
        props: {
            url: String,
            title: String,
            description: String,
            img: String,
        }
    }
</script>

<style scoped>
</style>