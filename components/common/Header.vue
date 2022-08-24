<template>
  <div class="flex justify-between max-w-5xl m-auto p-2 border-b-2">
    <h2>menu</h2>
    <img class="w-20" :src="require('~/assets/img/logo.png')" alt="" />
    <p>avatar</p>
  </div>
</template>

<script lang="ts">
import { mixins } from 'nuxt-property-decorator'
import CommonMixin from '~/components/mixin/common'

export default class Header extends mixins(CommonMixin) {}
</script>
