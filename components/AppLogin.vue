<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-6 d-none d-lg-block card-login__image"></div>
      <div class="col-lg-6 col-sm-12 card-login__form">
        <div class="card">
          <div class="card-body">
            <h2 class="card-header">Login</h2>
            <form>
              <div class="form-group">
                <label class="label-login" for="username">Usuario</label>
                <input type="text" class="form-control input-login" id="username" placeholder="Usuario">
              </div>
              <div class="form-group">
                <label class="label-login" for="password">Senha</label>
                <input type="password" class="form-control input-login" id="password" placeholder="Senha">
              </div>
              <hr>
              <div class="es">
                <p class="card-text">
                <a href="/?=newpassword">Esqueceu a senha?</a>
              </p>
              </div>
              <div class="d-grid ">
                <div class="button-container">
                  <button type="submit" class="btn btn-login"><i class="mdi mdi-account"></i>Entrar</button>
                  <button type="submit" class="btn btn-login"><i class="mdi mdi-account-multiple-plus"></i>Criar nova conta</button>
                </div>
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

