<template>
  <nav>
    <ol class="nav-horizonal">
      <li
        class="nav-horizonal-item"
        :class="{ 'nav-horizonal-item-active': item.active }"
        v-for="(item, index) in items"
        :key="index"
      >
        <component :is="item.icon" />
        {{ item.text }}
      </li>
    </ol>
  </nav>
</template>
<script>
export default {
  name: "HorizontalNav",
  props: {
    items: {
      required: true,
    },
  },
};
</script>
