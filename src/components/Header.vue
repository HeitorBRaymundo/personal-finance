<template>
    <div class="header">
        <h3>{{ name }}</h3>
    </div>
</template>


<script>
    import Vue from 'vue';

    export default Vue.extend({
        name: 'Header',
        props: {
            name: String,
        }
    })
</script>
