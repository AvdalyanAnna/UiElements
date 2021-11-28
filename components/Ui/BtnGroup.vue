<template>
  <div class="btn-group">
    <Btn
      v-for="(item, index) in btnList"
      :key="index"
      :btnClass="item.status ? groupBtnActiveClass : groupBtnClass"
      @click="changeActive(index)"
    >
      {{ item.text }}
    </Btn>
  </div>
</template>
<script>
export default {
  name: "BtnGroup",
  props: {
    btnListName: {
      type: String,
      required: true,
    },
    btnList: {
      required: true,
    },
    groupBtnClass: {
      type: String,
      default: "btn-light",
    },
    groupBtnActiveClass: {
      type: String,
      default: "btn-primary",
    },
  },
  methods: {
    changeActive(index) {
      this.$parent[this.btnListName].forEach((item, i) => {
        if (index == i) {
          item.status = true;
        } else {
          item.status = false;
        }
      });
    },
  },
};
</script>
