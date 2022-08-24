<template>
  <div>
    <Header />
    <Nuxt />
    <Navbar />
  </div>
</template>

<script lang="ts">
import { Vue, Component } from 'nuxt-property-decorator'
import Header from '../components/common/Header.vue'
import Navbar from '../components/common/Navbar.vue'

@Component({
  components: { Header, Navbar },
})
export default class Default extends Vue {}
</script>
