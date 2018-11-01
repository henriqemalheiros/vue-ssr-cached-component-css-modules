<template lang="html">
  <div>
    <CachedComponent/>
    <RegularComponent/>
  </div>
</template>

<script>
import CachedComponent from '../components/CachedComponent'
import RegularComponent from '../components/RegularComponent'

export default {
  name: 'PageIndex',
  components: {
    CachedComponent,
    RegularComponent
  }
}
</script>
