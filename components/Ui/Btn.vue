<template>
  <button @click="$emit('click')" class="btn" :class="btnClass">
    <component :is="iconPrevText"></component>
    <slot></slot>
    <component :is="iconNextText"></component>
  </button>
</template>
<script>
export default {
  name: "Btn",
  props: {
    btnClass: {
      type: String,
      default: "btn-primary",
    },
    iconPrevText: {
      type: String,
      default: "",
    },
    iconNextText: {
      type: String,
      default: "",
    },
  },
};
</script>
