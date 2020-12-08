<template>
    <div class="Sign-in page">
      <form>
        <h3> Sign In</h3>

        <div class="form-group">
          <label>Email address</label>
          <input type="email" class="form-control form-control-lg" />
        </div>

        <div class="form-group">
          <label>Password</label>
          <input type="pasword" class="form-control form control-lg" />
        </div>

        <button type="submit" class="btn btn-dark btn-lg btn-block">Sign In</button>
        <p class="forgot password text-right mt-2 mb-4">
          <router-link to="/forgot password">Forgot password ?</router-link>
        </p>

        <div class="social-icons">
            <ul>
              <li><a href="#"><i class="fa fa-google"></i></a></li>
              <li><a href="#"><i class="fa fa-facebook"></i></a></li>
            </ul>
          </div>

      </form>
    </div>
</template>

<script>
  export default {
      data() {
        return{}
      }
    }
</script>
