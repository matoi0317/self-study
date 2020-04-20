<template>
<div>
    <Head></Head>
    <Stories></Stories>
    <recommend></recommend>
    <Main></Main>
</div>
</template>

<script>
import Head from '~/components/Head.vue'
import Stories from '~/components/Stories.vue'
import Recommend from '~/components/Recommend.vue'
import Main from '~/components/Main.vue'

export default{
    name: "Index",
    components: { Head, Stories, Recommend, Main }
}
</script>

<style scoped>
</style>
