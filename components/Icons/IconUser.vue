<template>
  <svg
    viewBox="0 0 22 25"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
    class="icon icon-user"
    :class="iconClass"
  >
    <path
      d="M11 12.5C14.2812 12.5 17 9.82812 17 6.5C17 3.21875 14.2812 0.5 11 0.5C7.67188 0.5 5 3.21875 5 6.5C5 9.82812 7.67188 12.5 11 12.5ZM15.1719 14H14.375C13.3438 14.5156 12.2188 14.75 11 14.75C9.78125 14.75 8.60938 14.5156 7.57812 14H6.78125C3.3125 14 0.5 16.8594 0.5 20.3281V22.25C0.5 23.5156 1.48438 24.5 2.75 24.5H19.25C20.4688 24.5 21.5 23.5156 21.5 22.25V20.3281C21.5 16.8594 18.6406 14 15.1719 14Z"
    />
  </svg>
</template>
<script>
export default {
  name: "IconUser",
  props: {
    iconClass: {
      type: String,
      default: "white",
    },
  },
};
</script>
