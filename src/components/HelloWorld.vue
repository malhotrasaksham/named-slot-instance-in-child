<template>
  <div class="hello">
    <slot name="primary"></slot>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  },
  mounted() {
    console.log(!!this.$slots.primary);
  }
};
</script>
