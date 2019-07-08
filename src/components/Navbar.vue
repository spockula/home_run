<template>
  <main id="navbar">
    <nav class="navbar navbar-expand-lg navbar-light bg-light main-navbar">
      <div>
        <a class="navbar-brand" href="#">Home_Run</a>
      </div>
      <div>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
      </div>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav ml-auto mr-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#">About <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Contact</a>
      </li>
    </ul>
    <div class="form-inline my-2 my-lg-0">
      <a class="btn btn-primary mr-sm-2 register-btn">Register</a>
      <a class="btn my-2 my-sm-0 login-btn">Login</a>
    </div>
  </div>
</nav>
  </main>
  
</template>

<script>
export default {
  
}
</script>

<style scoped>

#navbar {
  height: 100vh;
}

#navbar .main-navbar{
  background-color: #f3f6fd;
  display: flex;
  justify-content: space-between;
}

#navbar .register-btn {
  cursor: pointer;
  background: #6784ff;
  border: none;
  box-shadow: 2px 7px 12px rgba(0,0,0,0.14);
}

#navbar .login-btn {
  cursor: pointer;
  border: 1px solid #6784ff;
  box-shadow: 2px 7px 12px rgba(0,0,0,0.14);
}

</style>
