<template>
  <img alt="Vue logo" src="./logo.png" />
  <TestTS></TestTS>
</template>

<script lang="ts">
import TestTS from 'module-ts-lib'
import LocalTS from './local-ts-lib/index'

export default {
  name: 'App',
  components: {
    TestTS,
    LocalTS
  }
}
</script>
