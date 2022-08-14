<template>
  <div class="winkelmand">
    <div class="container">
      <div class="is-size-2 has-text-left mb-6">
        Winkelmand
      </div>
    </div>
    <Bestelling msg="Welcome op Rompertjes.gift"/>

    <BestellingJa />
      <div class="columns">
        <div class="column is-half">
          <p class="my-5 has-text-left is-size-4 has-text-grey">
            Je bent misschien ook geïnteresseerd in...
          </p>
          <Suggesties />
        </div>
        <div class="column">
          <p class="my-5 has-text-left is-size-4 has-text-grey">
            Winkelmand-totalen
          </p>
          <div class="box mt-5">
            <div class="level">
              <!-- Left side -->
              <div class="level-left">
                <strong>Subtotaal</strong>
              </div>
              <!-- Right side -->
              <div class="level-right">
                €23.99
              </div>
            </div>
            <hr>
            <div class="level">
              <!-- Left side -->
              <div class="level-left">
                <strong>Totaal</strong>
              </div>
              <!-- Right side -->
              <div class="level-right">
                <strong>€23.99</strong>
              </div>
            </div>
          </div>
        
          <router-link to="/afrekenen">
            <div class="buttons">
                <b-button 
                label="Doorgaan naar afrekenen" 
                type="is-dark"
                size="is-medium" />
                <font-awesome-icon class="ml-5" icon="arrow-right" />
            </div>
          </router-link>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Bestelling from '@/components/Bestelling.vue'
import BestellingJa from '@/components/BestellingJa.vue'
import Suggesties from '@/components/Suggesties.vue'

export default {
  name: 'Winkelmand',
  components: {
    Bestelling,
    BestellingJa,
    Suggesties
  }
}
</script>