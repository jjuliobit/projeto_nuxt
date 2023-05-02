<template>
  <nav class="navbar navbar-expand-lg nav">
    <a class="navbar-brand" href="#">Logo</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav"
      aria-expanded="true" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse nav-group-1" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item active">
          <a class="nav-link" href="/">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Services</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact</a>
        </li>
        <div class="nav-group-2">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link entrar" href="/login">Entrar</a>
            </li>
            <li class="nav-item">
              <a class="nav-link criar-conta">Criar Conta</a>
            </li>
          </ul>
        </div>
      </ul>
    </div>
  </nav>
</template>

<style lang="scss">
@import '../assets/styles/header.scss';
</style>
