<template>
  <div class="about">
    <h1>This is an about page</h1>
      <Header name="Heitor e Laís"/>
  </div>
</template>


<script>
    import Vue from 'vue';
    import Header from '@/components/Header.vue';

    export default Vue.extend({
        name: 'about',
        components: {
            Header,
        },
    });
</script>
