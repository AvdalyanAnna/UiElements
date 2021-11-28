<template>
  <svg
    viewBox="0 0 14 25"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
    class="icon icon-fb"
    :class="iconClass"
  >
    <path
      d="M12.5781 14L13.2344 9.6875H9.0625V6.875C9.0625 5.65625 9.625 4.53125 11.5 4.53125H13.4219V0.828125C13.4219 0.828125 11.6875 0.5 10.0469 0.5C6.625 0.5 4.375 2.60938 4.375 6.35938V9.6875H0.53125V14H4.375V24.5H9.0625V14H12.5781Z"
    />
  </svg>
</template>
<script>
export default {
  name: "IconFb",
  props: {
    iconClass: {
      type: String,
      default: "white",
    },
  },
};
</script>
