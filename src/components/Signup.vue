<template>
  <div class="vue-template">
    <form>
      <h3>Resgistrar</h3>

      <div class="form-group">
        <label>Nome</label>
        <input type="text" class="form-control form-control-lg" />
      </div>

      <div class="form-group">
        <label>Email</label>
        <input type="email" class="form-control form-control-lg" />
      </div>

      <div class="form-group">
        <label>Senha</label>
        <input type="password" class="form-control form-control-lg" />
      </div>

      <button type="submit" class="btn btn-dark btn-lg btn-block">
        Inscrever-se
      </button>

      <p class="forgot-password text-right">
        Já registrado?
        <router-link :to="{ name: 'login' }">Entrar?</router-link>
      </p>
    </form>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
};
</script>