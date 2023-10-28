<template>
  <ul>
    <li class="d-flex_i gap-1_i">
      <p>Item 1</p> <!--Item title-->
      <p>10</p> <!--Item count-->
      <input v-model="clrPick" type="color" name="" id=""> <!--Item color-->
      <p>{{clrPick}}</p>
    </li>
    <li class="d-flex_i gap-1_i">
      <p>Item 2</p> <!--Item title-->
      <p>15</p> <!--Item count-->
      <input v-model="clrPick" type="color" name="" id=""> <!--Item color-->
      <p>{{clrPick}}</p>
    </li>
  </ul>
</template>

<script>
export default {
  name: "Lists-Items",
  data:()=>({
    clrPick: [],
  }),
}
</script>

<style scoped>

</style>