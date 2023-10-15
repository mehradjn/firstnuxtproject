<script setup>

</script>

<template>

  <div class="wrapper">

    <header>
      <h1>Register Page</h1>
      <p>its register form</p>
    </header>


    <main>

      <div class="form-content">
        <!--        action="LoginUser"-->
        <form>
          <div>
            <label for=""
                   :class="username.length<3 ? 'error' : '' "
            >
              username
            </label>
            <input v-model="username"
                type="text"
                placeholder="enter your username.."
            />
          </div>

          <div  class="form-field">
            <label for="">email</label>

            <input >
          </div>

          <div class="form-field" >
            <label for="">password</label>
            <input>
          </div>


          <!--          @click="LoginUser"-->
        </form>

        <button @click="RegisterUser">REGISTER</button>

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
    RegisterUser() {
      console.log('registering user started..')
    }
  }


}
</script>

<style scoped>
/*for just this page styling*/
.error{
  color: red;
}
</style>