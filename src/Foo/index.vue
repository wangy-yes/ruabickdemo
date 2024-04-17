<script lang="ts" setup>
defineProps<{
  /**
   * Foo组件的msg
   */
  msg: string;
}>();
</script>
<template>Foo:{{ msg }}</template>
<style lang="less" scoped></style>
