<template>
    <test/>
    <router-view/>
</template>

<script>
import Test from '@/components/Test.vue';
export default {
    components: {
        Test
    },

    data() {
        return {
            title: 'hello'
        }
    }
}
</script>

<style scoped>
</style>
