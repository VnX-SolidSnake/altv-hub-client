<template>
    <resources></resources>
</template>

<script>
import { postRequest, getRequest } from '@/utility/fetch.js';
import Resources from '@/components/resources.vue';

export default {
    name: 'Home',
    components: {
        Resources
    },
    data() {
        return {};
    },
    methods: {},
    mounted() {
        console.log('mounted');
    }
};
</script>
