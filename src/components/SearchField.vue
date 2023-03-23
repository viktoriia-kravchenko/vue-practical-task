<script>
export default {
  name: 'SearchField',
}
</script>

<template>
  <div class="mx-auto col-10 col-md-8 col-lg-6 mb-5">
    <form>
      <div class="d-flex flex-row justify-content-center align-items-center">
        <input 
          type="text" 
          class="form-control me-4" 
          name="query" 
          placeholder="Enter your ZIP code"
        >

        <button class="btn btn-success">Search</button>
      </div>
    </form>
  </div>
</template>

<style></style>