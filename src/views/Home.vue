<template>
  <div class="home">
    <div class="intro">
      <h1>Turd.dev</h1>
      <p>Sign up today and create a custom subdomain to redirect to your own domain. Let everyone know what kind of dev you are! You think your code is shit, look at ours!</p>
    </div>
    <RegisterSubdomain/>
  </div>
</template>

<script>
// @ is an alias to /src
import RegisterSubdomain from "@/components/RegisterSubdomain";

export default {
  name: "home",
  components: {
    RegisterSubdomain
  }
};
</script>

<style lang="scss">
.home {
  display: flex;
  align-items: center;
  flex-direction: column;

  .intro {
    margin-top: 25px;
    width: 50%;
  }
}
</style>

