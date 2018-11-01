<template lang="html">
  <div :class="$style.container">cached</div>
</template>

<script>
export default {
  name: 'CachedComponent',
  serverCacheKey: () => 'CachedComponent'
}
</script>

<style module>
.container {
  background-color: green;
}
</style>
