<template>
  <div>
    <Main />
    123
  </div>
</template>

<script lang="ts">
import { Vue, Component } from 'nuxt-property-decorator'
import Main from '../components/Main.vue'

@Component({
  components: {
    Main,
  },
})
export default class index extends Vue {}
</script>
