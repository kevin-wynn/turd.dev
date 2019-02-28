<template>
  <div class="turd">
    <div class="content">
      <h1>TURD</h1>
      <h2>Testing Updates Readily Delivered</h2>
      <h3>You think your code's shit? Look at ours!</h3>
      <br>
      <p>Turd is a Slack/CircleCI integration that will alert users directly when their tests fail or pass. Allowing users to re-run workflows directly from Slack, inspect errors and find out what went wrong, or check the status of a workflow.</p>
      <p>
        <small>coming soon...</small>
      </p>
      <br>
      <a href="https://github.com/kevin-wynn/turd.dev"/>
    </div>
  </div>
</template>

<script>
export default {
  name: "Intro"
};
</script>

<style lang="scss" scoped>
.turd {
  height: 100vh;
  width: 100vw;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;

  .content {
    width: 50vw;
    height: 50vh;
  }

  h1 {
    color: #3e2723;
    font-size: 150px;
  }
}
</style>
