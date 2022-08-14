<template>
    <div class="Afrekenen">
        <div class="container ml-5">
            <div class="row is-size-2 has-text-left mb-6">
                Winkelmand
            </div>

            <div class="columns">
                <div class="column is-half">
                    <Form />
                </div>
                <div class="column">
                    <div class="is-size-3 has-text-left mb-6">
                        Jouw bestelling
                    </div>
                <div class="table-container">
                    <table class="table">
                        <thead>
                            <tr>
                            <th><abbr title="Product">Product</abbr></th>
                            <th></th>
                            <th>Subtotaal</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                            <th>Romper met auto</th>
                            <th></th>
                            <td>€23.99</td>
                            </tr>
                        </tbody>
                        <tfoot>
                            <tr>
                            <th><abbr title="Totaal">
                                Totaal</abbr></th>
                            <th></th>
                            <th>€23.99</th>
                            </tr>
                        </tfoot>    
                    </table>
                </div>
                <div class="field is-grouped">
                    <div class="control">
                        <button class="button is-link">Submit</button>
                    </div>
                    <div class="control">
                        <button class="button is-link is-light">Cancel</button>
                    </div>
                </div>
            </div>
            </div>
        </div>            
    </div>
</template>

<script>
// @ is an alias to /src
import Form from '@/components/Form.vue'

export default {
  name: 'Afrekenen',
  components: {
    Form
  }
}
</script>