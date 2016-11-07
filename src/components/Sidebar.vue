<template>
  <div class="row sidebar">
    <div class="col s12 right">
      <div class="card z-depth-0">
        <div class="card-image">
          <img src="https://avatars0.githubusercontent.com/u/1396448?v=3&s=466">
          <span class="card-title">@lhas</span>
        </div>
        <div class="card-content">
          <p>Também sou conhecido por Luiz Almeida, tenho 21 anos, trabalho com desenvolvimento web há 6 anos. De estagiário a CTO.</p>

          <br>
          <p>Trabalhei de agências digitais até fábricas de software multinacionais.</p>

          <br>
          <p>As tecnologias que eu mais amo usar no front-end: <br> <strong>AngularJS</strong>, <strong>NodeJS</strong>, <strong>VueJS</strong>, <strong>SPA</strong>.</p>

          <br>
          <p>As tecnologias que eu mais amo usar no back-end: <br> <strong>Ruby on Rails</strong>, <strong>Laravel</strong>, <strong>WordPress</strong>.</p>

          <br>
          <p>Eu adoro mexer com <strong>DevOps</strong> também. Do <strong>Vagrant</strong> ao <strong>Docker</strong>. <br> Com <strong>Linux</strong>, é claro! :)</p>

        </div>
        <div class="card-action redes-sociais">
          <a href="https://www.facebook.com/lhas666" target="_blank" class="btn-flat blue darken-2 white-text"><i class="fa fa-facebook"></i></a>
          <a href="https://github.com/lhas" target="_blank" class="btn-flat grey white-text"><i class="fa fa-github"></i></a>
          <a href="https://www.linkedin.com/in/luizhrqas" target="_blank" class="btn-flat light-blue lighten-2 white-text"><i class="fa fa-linkedin"></i></a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'sidebar',
  data () {
  }
}
</script>

<style scoped>
  .sidebar {
    margin-top: 20px;
  }
  .redes-sociais a {
    padding: 3px 10px;
  }
</style>