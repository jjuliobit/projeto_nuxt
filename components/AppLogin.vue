<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-6 d-none d-lg-block card-login__image"></div>
      <div class="col-lg-6 col-sm-12 card-login__form">
        <div class="card">
          <div class="card-body">
            <h2 class="card-title">Login</h2>
            <hr>
            <form>
              <div class="form-group">
                <label class="label-login"  for="username">Usuario</label>
                <input type="text" class="form-control input-login" id="username" placeholder="Usuario">
              </div>
              <div class="form-group">
                <label class="label-login" for="password">Senha</label>
                <input type="password" class="form-control input-login" id="password" placeholder="Senha">
              </div>
              <div class="d-grid button-container">
                <button type="submit" class="btn btn-login">Login</button>
                <button type="submit" class="btn btn-login">Register</button>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
  
  
<style lang="scss">
@import '../assets/styles/login.scss';
</style>

