<template>
  <div class="fixed bottom-0 left-0 right-0 max-w-6xl m-auto">
    <ul class="flex justify-evenly">
      <router-link to="/">HOME</router-link>
      <router-link to="/about">ABOUT</router-link>
      <router-link to="/test1">공연</router-link>
      <router-link to="/board">게시판</router-link>
      <router-link to="/mypage">마이페이지</router-link>
    </ul>
  </div>
</template>

<script lang="ts">
import { mixins } from 'nuxt-property-decorator'
import CommonMixin from '~/components/mixin/common'

export default class Navbar extends mixins(CommonMixin) {}
</script>
