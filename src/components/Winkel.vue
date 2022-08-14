<template>
  <div class="winkel">
    <div class="level">
      <!-- Left side -->
      <div class="level-left">
        <div class="level-item">
          <p class="is-size-2">Winkel</p>
        </div>
      </div>
      <!-- Right side -->
      <div class="level-right">
        <div class="level-item">
          <div class="select">
            <select>
              <option>Nieuwste</option>
              <option>Standaard sortering</option>
              <option>Gemiddelde Waardering</option>
              <option>Populariteit</option>
              <option>Prijs: van laag naar hoog</option>
              <option>Prijs: van hoog naar laag</option>
            </select>
          </div>
        </div>
      </div>
    </div>
      <div class="columns is-variable is-1-mobile is-0-tablet is-3-desktop is-8-widescreen is-2-fullhd">
        <div class="column">
          <div class="card">
            <header class="card-header">
              <p class="card-header-title">
                Romper met auto
              </p>
              <p class="card-header-icon" aria-label="categorie">
                <span class="icon">
                  <font-awesome-icon icon="mars" />
                </span>
              </p>
            </header>
            <div class="card-image">
              <figure class="image is-4by5">
                <img src="../assets/rompertje5.1.jpg" alt="Placeholder image">
              </figure>
            </div>
            <footer class="card-footer">
              <div class="level py-4">
                <!-- Left side -->
                <div class="level-left">
                  <div class="level-item ml-4">
                    <p class="has-text-success">
                      10 op voorraad
                    </p>
                  </div>
                </div>
                <!-- Right side -->
                <div class="level-right ml-4">
                  <p class="level-item"><router-link to="/producten" class="button is-small is-info">Meer info</router-link></p>
                </div>
              </div>
            </footer>
          </div>
        </div>
        <div class="column">
          <div class="card">
            <header class="card-header">
              <p class="card-header-title">
                Romper met unicorn
              </p>
              <p class="card-header-icon" aria-label="categorie">
                <span class="icon">
                  <font-awesome-icon icon="venus" />
                </span>
              </p>
            </header>
            <div class="card-image">
              <figure class="image is-4by5">
                <img src="../assets/rompertje5.1.jpg" alt="Placeholder image">
              </figure>
            </div>
            <footer class="card-footer">
              <div class="level py-4">
                <!-- Left side -->
                <div class="level-left">
                  <div class="level-item ml-4">
                    <p class="has-text-success">
                      10 op voorraad
                    </p>
                  </div>
                </div>
                <!-- Right side -->
                <div class="level-right ml-4">
                  <p class="level-item"><router-link to="/producten" class="button is-small is-info">Meer info</router-link></p>
                </div>
              </div>
            </footer>
          </div>
        </div>
        <div class="column">
          <div class="card">
            <header class="card-header">
              <p class="card-header-title">
                Romper met gatenkaas
              </p>
              <p class="card-header-icon" aria-label="categorie">
                <span class="icon">
                  <font-awesome-icon icon="venus-mars" />
                </span>
              </p>
            </header>
            <div class="card-image">
              <figure class="image is-4by5">
                <img src="../assets/rompertje5.1.jpg" alt="Placeholder image">
              </figure>
            </div>
            <footer class="card-footer">
              <div class="level py-4">
                <!-- Left side -->
                <div class="level-left">
                  <div class="level-item ml-4">
                    <p class="has-text-success">
                      10 op voorraad
                    </p>
                  </div>
                </div>
                <!-- Right side -->
                <div class="level-right ml-4">
                  <p class="level-item"><router-link to="/producten" class="button is-small is-info">Meer info</router-link></p>
                </div>
              </div>
            </footer>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
  name: 'HelloWorld',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
