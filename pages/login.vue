<template>
<div>
  Login page
</div>
</template>

<script lang="ts" setup>
definePageMeta({ 
  layout: 'guest',
  middleware: ['guest'] 
});
</script>