<template>
  <div id="jumbotron" class="container-fluid">
    <div class="container position-relative">
      <img src="img/jumbo-weed.png" alt="" class="position-absolute col-md-8 offset-md-4">
    </div>
    <div class="container">
      <div class="row">
        <div class="col-md-5 d-flex flex-column py-5">
        <h1>DUTCH PASSION®</h1>
        <h3>semi di cannabis, dal 1987</h3>
        <span>
          Uniamo la nostra esperienza insuperabile nella
          produzione di semi di cannabis femminizzati con
          le ultime genetiche per offrirti i semi di cannabis
          della migliore qualità.
        </span>
        <button type="button" name="button">COLLEZIONE DI SEMI</button>
      </div>
      </div>
      <div class="row">
        <div id="jumbotron_card_container" class="container position-relative" >
          <div id="jumbotron_card" class="card">
            <div class="row">
              <div class="col-md-4 d-flex flex-column justify-content-center align-items-center">
                <h4>Accesso Rapido</h4>
                <img src="img/lente.png" alt="">
                <img src="img/fiore.png" alt="">
              </div>
              <div class="col-md-4">
                <h4>seed finder</h4>
                <span>Trova la varietà perfetta per te. Ricco di CBD? All'aperto? Gusto? Effetto? Per favore, lascia che ti aiutiamo!</span>
                <img src="img/interrogativo.png" alt="">
              </div>
              <div class="col-md-4">
                <h3>Scopri Dutch Passion®</h3>
                <hr>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

</template>

<script>
    export default {
        mounted() {
        }
    }
</script>
<style scooped lang="scss">
  #jumbotron{
    background-image: url('/img/jumbo.jpg');
    background-position: center;
    background-size: cover;
    height: 500px;
  }
  #jumbotron_card {
    position: absolute;
    top: 100px;
  }
</style>
