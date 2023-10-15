<script setup>

</script>

<template>

  <div class="wrapper">

    <header>
      <h1>Login Page</h1>
      <p>its login form</p>
    </header>


    <main>

      <div class="form-content">
<!--        action="LoginUser"-->
        <form action="LoginUser">
          <div>
            <label for="">username</label>
            <input>
          </div>

          <div  class="form-field">
            <label for="">email</label>
            <input>
          </div>

          <div class="form-field">
            <label for="">password</label>
            <input>
          </div>

          <button type="submit">LOGIN</button>

<!--          @click="LoginUser"-->
        </form>
      </div>

    </main>


    <footer>

    </footer>

  </div>

</template>

<script>
export default {
  name: 'index',

  data() {
    return {
      email: '',
      password: '',
      username: '',
    }
  },

  components: {

  },

  methods: {
    LoginUser() {
      console.log('logging user started..')
    }
  }


}
</script>

<style scoped>
/*for just this page styling*/

</style>