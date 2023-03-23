<script>
export default {
  name: 'SearchResults',
}
</script>

<template>
  <div class="mx-auto col-10 col-md-8 col-lg-6 mb-5">
    <div class="text-left mb-4">
      <h3>ZIP code: 23</h3>
    </div>

    <table class="table table-striped mb-5">
      <tbody>
        <tr>
          <th>State</th>
          <td>Alabama</td>
        </tr>

        <tr>
          <th>City</th>
          <td>XXX</td>
        </tr>

        <tr>
          <th>IP</th>
          <td>XXX</td>
        </tr>

        <tr>
          <th>User Agent</th>
          <td>XXX</td>
        </tr>

        <tr>
          <th>HTTP Referer</th>
          <td>XXX</td>
        </tr>

        <tr>
          <th>UTM tags</th>
          <td>XXX</td>
        </tr>
      </tbody>
    </table>

    <div class="d-flex justify-content-between">
      <a href="#/" class="btn btn-outline-secondary">
        Return
      </a>
  
      <button class="btn btn-outline-success">IP Lookup</button>
    </div>
  </div>
</template>

<style>
</style>