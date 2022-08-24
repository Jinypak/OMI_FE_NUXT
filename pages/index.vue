<template>
  <div class="flex max-w-5xl m-auto">
    <today-insta></today-insta>
  </div>
</template>

<script lang="ts">
import { Vue, Component } from 'nuxt-property-decorator'
import TodayInsta from '../components/main/TodayInsta.vue'

@Component({
  components: { TodayInsta },
})
export default class index extends Vue {}
</script>
