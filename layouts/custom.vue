<script lang="ts" setup>
const { data } = useFetch('https://ungh.cc/repos/unjs/nitro')
</script>

<template>
  <div>
    {{ data }}
    <p>Custom Layout</p>
    <hr/>
    <slot />
  </div>
</template>
