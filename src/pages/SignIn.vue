<template>
  <div class="row">
    <div class="col-md-6 offset-md-3">
      <div>
        <div>
          <h3>Sign In</h3>

          <hr />
        </div>
        <form>
          <div class="form-group">
            <label>Email</label>
            <input type="text" class="form-control" />
          </div>
          <div class="form-group">
            <label>Password</label>
            <input type="password" class="form-control" />
          </div>
          <div class="my-3">
            <button type="submit" class="btn btn-primary">SignIn</button>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
import {mapState} from 'vuex'
export default {
  name: "Sign-In",
  computed:{
      ...mapState('auth',{
          name:state => state.name,
      })
  }
};
</script>

<style >
</style>