<template>
  <div class="home">
    <main>
     Yaay! User authenticated!
    </main>
  </div>
</template>

<script>
// @ is an alias to /src
import { mapGetters } from 'vuex'
export default {
  name: 'Home',
  components: {

  },
  computed: {
    ...mapGetters(['user'])
  }
}
</script>
