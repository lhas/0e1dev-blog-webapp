<template>
  <div class="row sidebar">
    <div class="col s12 right">
      <div class="card animated zoomIn z-depth-0">
        <div class="card-image">
          <img src="https://avatars0.githubusercontent.com/u/1396448?v=3&s=466">
          <span class="card-title">@lhas</span>
        </div>
        <div class="card-content">
          <p>Também sou conhecido por Luiz Almeida, tenho 21 anos, trabalho com desenvolvimento web há 6 anos. <br> De estagiário a CTO.</p>

          <br>
          <p>Trabalhei de agências digitais a fábricas de software multinacionais.</p>

          <br>
          <p>As tecnologias que eu mais amo usar no front-end: <br> <strong>AngularJS</strong>, <strong>NodeJS</strong>, <strong>VueJS</strong>, <strong>SPA</strong>.</p>

          <br>
          <p>As tecnologias que eu mais amo usar no back-end: <br> <strong>Ruby on Rails</strong>, <strong>Laravel</strong>, <strong>WordPress</strong>.</p>

          <br>
          <p>Eu adoro mexer com <strong>DevOps</strong> também. <br> Do <strong>Vagrant</strong> ao <strong>Docker</strong>.  Com <strong>Arch Linux</strong>, é claro! :)</p>
          
          <br>
          <p>Sou entusiasta de boas práticas de código, libertarianismo, economia e tenho o dogma de que todo indivíduo deve aprender a programar. </p>
          
          <br> 
          <p>Acredito que o pensamento analítico de um programador auxilia na busca por soluções do dia-a-dia.</p>
        
          <br>

            <transition name="fade">
              <small class="grey-text">{{phrase.phrase}} <em>{{phrase.author}}</em></small>
            </transition>

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
import _ from 'lodash'

export default {
  name: 'sidebar',
  data () {
    return {
      phrase: {},
      phrases: [
        {
          phrase: '“Não acredito nas constituições nem nas leis, a mais perfeita constituição não conseguiria satisfazer-me. Necessitamos de algo diferente: inspiração, vida, um mundo sem leis, portanto, livre.” ',
          author: 'Mikhail Bakunin'
        },
        {
          phrase: '"Quando você perceber que, para produzir, precisa obter a autorização de quem não produz nada; quando comprovar que o dinheiro flui para quem negocia não com bens, mas com favores; quando perceber que muitos ficam ricos pelo suborno e por influência, mais que pelo trabalho, e que as leis não nos protegem deles, mas, pelo contrário, são eles que estão protegidos de você; quando perceber que a corrupção é recompensada, e a honestidade se converte em auto-sacrifício; então poderá afirmar, sem temor de errar, que sua sociedade está condenada.""',
          author: 'Ayn Rand'
        }]
    }
  },
  methods: {
    getPhrase: function () {
      this.phrase = _.sample(this.phrases)
    }
  },
  created: function () {
    let vm = this

    this.getPhrase()

    window.setInterval(function () {
      vm.getPhrase()
    }, 6000)
  }
}
</script>

<style scoped>
  .sidebar {
    margin-top: 20px;
    font-family: 'Arvo', serif;
    font-weight: 300;
    font-size: 14px;
    letter-spacing: .5px;
    text-align: right;
  }
  .sidebar .card-content {
    padding: 20px 0px;
  }
  .sidebar strong {
    font-weight: 700;
  }
  .redes-sociais a {
    width: 40px;
    text-align: center;
    padding: 3px 10px;
    line-height: 30px;
  }
  .redes-sociais {
    padding-right: 0px !important;
  }
  .redes-sociais a:last-child {
    margin-right: 0px !important;
  }
  .redes-sociais a i {
    font-size: 24px;
  }
  small {
    font-weight: 300;
    font-size: 17px;
    font-family: 'Work Sans', serif;
  }
  .card-title {
    font-family: 'Arvo', monospace;
    font-size: 50px;
    font-weight: 700;
    right: 0px;
  }
</style>