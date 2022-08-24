<template>
  <div class="flex max-w-5xl m-auto">mypage</div>
</template>

<script lang="ts">
import { mixins } from 'nuxt-property-decorator'
import CommonMixin from '~/components/mixin/common'

export default class Navbar extends mixins(CommonMixin) {}
</script>
