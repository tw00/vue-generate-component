<template>
  <section class="{{name | kebabCase}}">
    <h1>{{name | camelCase}} Component</h1>
  </section>
</template>

<script>
import { mapGetters, mapActions } from 'vuex'

export default  {
  name: '{{name | camelCase}}',
  props: [],
  data() {
    return {
    }
  },
  mounted() {
  },
  computed: {
    ...mapGetters('store', [
    ])
  }
  methods: {
    ...mapActions('store', [
    ])
  },
  components: {
  }
}
</script>

<style>
.{{name | kebabCase}} {

}
</style>
