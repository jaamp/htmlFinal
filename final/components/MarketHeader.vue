<template>
<div class="header">
<h1>{{ title }}</h1>
<Nav />
</div>
</template>

<script>
import Nav from '../components/Nav'

export default {
    components: {
        Nav
    },
        data () {
        return {
    title: "Farmers' Markets"
        }
    },
         head () {
    return {
        title: this.title
    }
  }
}

</script>

<style scoped>
.header {
    padding: 1% 5% 2% 5%;
    background-color: lavender
}
</style>