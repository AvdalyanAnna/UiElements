<template>
  <svg
    viewBox="0 0 23 26"
    xmlns="http://www.w3.org/2000/svg"
    class="icon icon-player"
    :class="iconClass"
  >
    <path
      d="M21.2031 10.6231L4.01562 0.466824C2.59961 -0.363254 0.5 0.466824 0.5 2.46878V22.7813C0.5 24.6367 2.45312 25.7598 4.01562 24.8321L21.2031 14.6758C22.7168 13.7481 22.7168 11.5508 21.2031 10.6231Z"
    />
  </svg>
</template>
<script>
export default {
  name: "IconPlayer",
  props: {
    iconClass: {
      type: String,
      default: "white",
    },
  },
};
</script>
