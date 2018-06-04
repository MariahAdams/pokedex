<template>
  <div class="sortbox">
    <h2>Sort</h2>
    <select v-model="chosenSort.prop">
      <option disabled value="">Sort by: </option>
      <option value="pokemon">A-Z</option>
      <option value="id">#</option>
      <option value="attack">Attack</option>
      <option value="hp">HP</option>
      <option value="defense">Defense</option>
    </select>
  </div>
</template>

<script>
export default {
  props: ['chosenSort']
};
</script>

<style>
.sortbox {
  float: left;
}

</style>
