<template>
  <div>
    <p>메인 페이지 입니다.</p>
    <div>
      {{ products }}
    </div>
  </div>
</template>

<script>
import axios from 'axios'
export default {
  data() {
    return {
      products: [],
    }
  },
  async created() {
    const response = await axios.get('http://localhost:3000/products')
    console.log(response)
    this.products = response.data
  },
}
</script>

<style lang="scss" scoped></style>
