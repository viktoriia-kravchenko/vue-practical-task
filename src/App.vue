<script>
import SearchField from './components/SearchField.vue';
import SearchResults from './components/SearchResults.vue';
import IPLookup from './components/IPLookup.vue';

export default {
  components: {
    SearchField,
    SearchResults,
    IPLookup,
  },
}
</script>

<template>
  <div class="container">
    <div class="d-flex flex-column min-vh-100 justify-content-center align-items-center">
      <SearchField />

      <SearchResults />

      <IPLookup />
    </div>
  </div>
</template>

<style>
</style>