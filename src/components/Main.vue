<template lang="html">
  <section class="src-components-main">
       <Navbar/>
      <Wallet />
  </section>
</template>
<script lang="js">
import Wallet from "./Wallet.vue";
import Navbar from "./Navbar.vue";

  export default  {
    name: 'Main',
    components: {
      Wallet,
      Navbar
    },
    props: [],
    mounted () {

    },
    data () {
      return {

      }
    },
    methods: {

    },
    computed: {

    }
}
</script>

<style scoped lang="scss">
</style>
