<template>
  <div>
    <h1>An error occurred</h1>
    <p>{{ error }}</p>
  </div>
</template>

<script>
export default {
  props: ['error'],
}
</script>
