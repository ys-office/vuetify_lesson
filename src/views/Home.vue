<template>
<v-container>
  <v-row>
    <v-col>
    <SaleGraph />
    </v-col>
    <v-col>
    <SaleGraph />
    </v-col>
    <v-col>
    <SaleGraph />
    </v-col>
    <v-col>
    <SaleGraph />
    </v-col>
  </v-row>
</v-container>
</template>

<script>
import SaleGraph from '../components/SaleGraph'

export default {
  components: {
    SaleGraph
  }
}
</script>
