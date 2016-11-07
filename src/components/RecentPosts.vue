<template>
  <div class="row row-recent-posts animated zoomIn">

    <div class="col s12">

      <div class="card z-depth-0 lighten-5">
        <a href="#" class="grey-text text-darken-2">

          <img src="https://templateflip.com/wp-content/uploads/2015/05/blog-home-template-min1-600x273.jpg" alt="">

        <div class="card-content">
          <span class="card-title">Criando sites em vários idiomas com o AngularJS (incluindo dados dinâmicos) <span class="timeago grey-text">15 horas atrás</span></span>
          <p>
Graças a internet, empresas que no passado dependiam do mercado local para ofertar e adquirir serviços, agora podem escalar seu empreendimento a nível global. Por esta exposição, se faz necessário adaptar-se ao idioma local do público alvo desejado...</p>
        </div> <!-- .card-content -->

        </a>

        <div class="card-content tags">
          <p><a href="#" class="btn-flat"><i class="material-icons left">star</i> Ruby</a></p>
        </div>
      </div> <!-- .card -->

    </div> <!-- .col -->

  </div> <!-- .row -->
</template>

<script>
export default {
  name: 'recent-posts',
  data () {
  }
}
</script>

<style scoped>
  .row-recent-posts {
    margin-top: 20px;
    margin-bottom: 20px;
  }
    .card {
      background: transparent !important;
      margin-bottom: 20px;
    }
  .timeago {
    font-size: 15px;
    opacity: 0.6;
    text-transform: uppercase;
    font-weight: 300;
  }
  img {
    width: 100% !important;
  }
  .tags {
    font-size: 14px;
  }
  .card-title {
    font-family: 'Arvo';
    font-size: 24px;
    line-height: 34px !important;
    font-weight: 700;
    margin-bottom: 20px;
    display: inline-block;
    letter-spacing: 0.5px;
  }
  .card-content {
    letter-spacing: 0.5px;
    font-size: 13px;
    line-height: 24px;
    font-family: 'Arvo';
  }
</style>