<template>
  <main class="page-container" :class="className">
    <slot/>
  </main>
</template>

<script>
  export default {
    name: "PageContainer",
    props:['className']
  }
</script>