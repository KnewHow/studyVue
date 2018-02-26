<template v-if="loginType === 'username'">
  <div>
    <label>UserName</label>
    <input placeholder="Enter your username" />
  </div>
</template>
<template v-else>
  <div>
    <label>Email</label>
    <input placeholder="Enter your Email" />
  </div>
</template>


<script>
export default {
  data () {
    return {
     loginType:'username'
    }
  },
  methods: {
    switchLoginType: function () {
      this.loginType = 'email'
    }
  }
}
</script>

<style>

</style>
