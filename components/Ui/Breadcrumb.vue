<template>
  <nav aria-label="breadcrumb">
    <ol class="breadcrumb">
      <li
        v-for="(item, index) in items"
        :key="index"
        class="breadcrumb-item active"
        aria-current="page"
      >
        {{ item.text }}
        <IconNext v-if="items.length - 1 === 0 || index !== items.length - 1" />
      </li>
    </ol>
  </nav>
</template>
<script>
export default {
  name: "Breadcrumb",
  props: {
    items: {
      required: true,
    },
  },
};
</script>
