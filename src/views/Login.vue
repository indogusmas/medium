<template>
  <div class="auth-page">
    <div class="container page">
      <div class="row">
        <div class="col-md-6 offset-md-3 col-xs-12">
          <h1 class="text-xs-center">Sign In</h1>
          <p class="text-xs-center">
            <router-link to="/register">Need a Account ?</router-link>
          </p>
          <ul class="error-message">
            <li v-for="(error, i) in errors" :key="i"  style="list-style: none">{{error}}</li>
          </ul>
          <form>
            <fieldset class="form-group">
              <input
                type="text"
                v-model="email"
                class="form-control form-control-lg"
                placeholder="email"
              />
            </fieldset>
            <fieldset class="form-group">
              <input
                type="password"
                v-model="password"
                class="form-control form-control-lg"
                placeholder="passwor"
              />
            </fieldset>
            <button @click="login" class="btn btn-lg btn-secondary pull-xs-right">
              Sign In
            </button>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Login",
  data: function(){
    return {
      password: "",
      email:"",
      errors:[]
    };
  },
  methods:{
    login(){
      console.log(this.password);
      this.$store
        .dispatch("users/loginUser",{
          email:this.email,
          password:this.password
        })
        .then((response)=>{
          console.log(response);
        })
        .catch(err =>{
          console.log(err);
          this.errors=["error"];
        })
    }
  }
};
</script>
<style>
</style>