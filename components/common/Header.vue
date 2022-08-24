<template>
  <h1>Header222</h1>
</template>

<script lang="ts">
import { mixins } from 'nuxt-property-decorator'
import CommonMixin from '~/components/mixin/common'

export default class Header extends mixins(CommonMixin) {}
</script>
