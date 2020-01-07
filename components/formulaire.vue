<template>
    <form :class="{rounded:rounded}"
        class="max-w-sm rounded shoadow-lg overflow-hidden">
   <div class="px-6">
        <p>kol</p>
   </div>
    </form>
</template>

<script lang="ts">
export default {
  name:'formulaire', 
  props: {
    rounded: {rounded: Boolean, default: false},
  },
  data() {
    return {
    }
  },
}

</script>

<style>

</style>