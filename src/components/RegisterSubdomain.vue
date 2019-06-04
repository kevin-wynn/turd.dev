<template>
  <div class="register-subdomain">
    <div class="sign-up">
      <span>https://</span>
      <input
        class="fix register-input"
        type="text"
        v-autowidth="{maxWidth: '960px', minWidth: '50px', comfortZone: 0}"
        v-model="subdomain"
        placeholder=""
        autofocus
      />
      <span>.turd.dev</span>
      <button @click.prevent="saveDomain" class="save">Save Domain</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "RegisterSubdomain",
  data: function() {
    return {
      subdomain: ""
    };
  },
  methods: {
    saveDomain: function() {
      console.log("hello");
    }
  }
};
</script>

<style lang="scss">
.register-subdomain {
  .sign-up {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    font-size: 28px;
    margin-top: 25px;

    .register-input {
      font-size: 28px;
      border: 0;
      padding-left: 5px;
      padding-right: 5px;
      display: inline-flex;
      border-bottom: 1px solid #ececec;
      color: #666;
      text-align: center;

      &:active,
      &:focus {
        outline: none;
      }
    }

    .save {
      border: 0;
      background: #19b5fe;
      color: #fff;
      font-size: 18px;
      padding: 15px;
      margin-left: 15px;
      transition: 0.2s ease all;
      cursor: pointer;

      &:hover {
        background: darken(#19b5fe, 10%);
      }

      &:active,
      &:focus {
        outline: 0;
      }
    }
  }
}
</style>
