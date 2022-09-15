<template>
  <div class="card">
    <slot name="icon"></slot>
    <slot name="title"></slot>
    <slot name="text"></slot>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.card {
  width: 20.2vw;
  min-height: 424px;
  padding: 40px 30px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  gap: 25px;
  align-items: center;
  border: 1px solid #d7d7d7;
  filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.1));
  border-radius: 10px;
  text-align: center;
  font-family: "Averta Std";
  font-style: normal;
  font-weight: 400;
  font-size: 21px;
  line-height: 29px;
}
</style>
