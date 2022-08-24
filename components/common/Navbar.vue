<template>
  <div class="fixed bottom-0 left-0 right-0 max-w-6xl m-auto">
    <ul class="flex justify-evenly">
      <li>메인</li>
      <li>컨텐츠</li>
      <li>공연</li>
      <li>게시판</li>
      <li>마이페이지</li>
    </ul>
  </div>
</template>

<script lang="ts">
import { mixins } from 'nuxt-property-decorator'
import CommonMixin from '~/components/mixin/common'

export default class Navbar extends mixins(CommonMixin) {}
</script>
