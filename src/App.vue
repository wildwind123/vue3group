<template>
  <Examples.Bar>
    slot bar
  </Examples.Bar>
  <hr>
  <Examples.Foo>
    slot foo
  </Examples.Foo>
</template>
<script lang="ts" setup>
import { Examples } from './components/example';
</script>