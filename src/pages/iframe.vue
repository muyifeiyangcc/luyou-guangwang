<script setup lang="ts" generic="T extends any, O extends any">
function aa() {
  window.postMessage('Hello from parent window!', '*')
}
</script>

<template>
  <div>
    <div h-100 w-100 bg-black c-white @click="aa">
      dian
    </div>
  </div>
</template>
