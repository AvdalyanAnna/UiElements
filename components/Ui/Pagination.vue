<template>
  <ul class="pagination" :class="paginationClass">
    <li v-if="!hasNotArros" class="pagination-item pagination-back">
      <iconNext />
    </li>
    <li v-if="!hasNotList" class="pagination-item">1</li>
    <li v-if="!hasNotList" class="pagination-item">2</li>
    <li v-if="!hasNotList" class="pagination-item">3</li>
    <li v-if="!hasNotList" class="pagination-item">...</li>
    <li v-if="!hasNotList" class="pagination-item">9</li>
    <li v-if="!hasNotArros" class="pagination-item pagination-next">
      <iconNext />
    </li>
  </ul>
</template>
<script>
export default {
  name: "Pagination",
  props: {
    paginationClass: {
      type: String,
      default: "",
    },
    hasNotArros: {
      type: Boolean,
      default: false,
    },
    hasNotList: {
      type: Boolean,
      default: false,
    },
  },
};
</script>
