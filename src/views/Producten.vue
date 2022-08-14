<template>
  <div class="Producten">
    <div class="notification is-success">
      <!-- Main container -->
      <div class="level">
        <!-- Left side -->
        <div class="level-left">
          <div class="level-item">
                <font-awesome-icon icon="check-circle" />
                <p class="ml-3">
                  “Rompeltje met huis” is toegevoegd aan je winkelmand.
                </p>
          </div>
        </div>

        <!-- Right side -->
        <div class="level-right">
          <div class="level-item">
            <p class="mr-3">
              Winkelmand bekijken
            </p>
            <font-awesome-icon icon="arrow-right" />
          </div>
        </div>
      </div>
  </div>


    <Product msg="Welcome op Rompertjes.gift"/>

      <p class="my-5 has-text-left is-size-4 has-text-grey">
        Je bent misschien ook geïnteresseerd in...
      </p>
      <Suggesties />
  </div>
</template>

<script>
// @ is an alias to /src
import Product from '@/components/Product.vue'
import Suggesties from '@/components/Suggesties.vue'

export default {
  name: 'Producten',
  components: {
    Product,
    Suggesties
  }
}
</script>

<style>
.notification {
  position: relative;
  top: unset;
  right: unset;
}
</style>
