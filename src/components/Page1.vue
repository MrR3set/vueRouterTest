<template>
  <div class="page1">
    <h1>Page 1</h1>
    Params passed {{id}}
  </div>
</template>

<script>
export default {
  name: 'Page1',
  props:{
      id: Number
  }

}
</script>

