<template>
  <div class="home">

    <Winkel msg="Welcome op Rompertjes.gift"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Winkel from '@/components/Winkel.vue'

export default {
  name: 'Home',
  components: {
    Winkel
  }
}
</script>
