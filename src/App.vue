<script setup lang="ts">

import { Button } from 'tinstyle/vue'

const test = () => {
  alert()
}

</script>

<template>
  <Button @click="test">Click</Button>
</template>