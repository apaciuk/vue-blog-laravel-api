<template>
  <div class="container h-100">
    <div class="row align-items-center h-100">
      <div class="col-12 mx-auto">
        <div class="jumbotron text-center">
          <h1 class="display-4">Nuxt-Bootstrap-UIkit</h1>
          <p class="lead">Nuxt.js project + Bootstrap Vue Framework<br />
          UIKit Examples</p>
          <Basic />
          <basicCar />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Basic from '~/components/Basic.vue'
import basicCar from '~/components/basicCar.vue'

export default {
  name: "Home",
  components:
  Basic,
  basicCar
}
</script>
<style>
#__layout {
  height: 100vh;
}
.jumbotron {
  background-color: #fff;
}
</style>

