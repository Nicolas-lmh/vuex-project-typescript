<template>
  <div class="mainMenu">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
// import { Component, Prop, Vue } from 'vue-property-decorator';

// @Component
// export default class HelloWorld extends Vue {
//   @Prop() private msg!: string;
// }
export default {
    name:"MainMenu",
    props: ['msg'],
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
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
  color: #383e4a;
}
</style>
