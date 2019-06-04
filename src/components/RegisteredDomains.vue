<template>
  <div class="registered-domains">
    <ul>
      <li v-for="domain in domains" :key="domain._id">
        <span>https://</span>
        {{domain.subdomain}}
        <span>.turd.dev</span>
        <span>=></span>
        <span>{{domain.redirect}}</span>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "RegisteredDomains"
};
</script>

<style lang="scss">
.registered-domains {
}
</style>
