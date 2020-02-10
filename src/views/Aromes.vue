<template>
  <div class="container">
    <HeaderAromes />
    <AromesSelection />
    <ButtonSelectionAromes />
  </div>
</template>

<script>
//import { Component, Prop, Vue } from 'vue-property-decorator';
import HeaderAromes from '../components/HeaderAromes.vue';
import AromesSelection from '../components/AromesSelection.vue';
import ButtonSelectionAromes from '../components/ButtonSelectionAromes.vue';

/*@Component
export default class Aromes extends Vue {
  
}*/

export default {
  name: 'Aromes',
  components: {
    HeaderAromes,
    AromesSelection,
    ButtonSelectionAromes,
  },
  // data: () => {
  //   return {
  //     flavours = []
  //   }

  // },
  // methods: {
  //   pushFlavours(value) {
  //     return this.flavours = [...this.flavours, value];
  //   }
  // }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.container {
  background-color: #c9c9c9;
}

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
