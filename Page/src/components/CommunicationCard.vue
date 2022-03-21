<template>
  <div class="communication-border p-5 m-3">
    <div class="d-flex flex-row">
      <div class="mx-1">
        <i :class="icon"></i>
      </div>
      <div class="mb-3">
        <h4>{{ method }}</h4>
        <h6>021.123.145.14</h6>
      </div>
    </div>
    <button :class="buttonClass">{{ buttonLabel }}</button>
  </div>
</template>

<script>
export default {
  name: "Communication Card",
  props: {
    buttonClass: String,
    method: String,
    icon: String,
    buttonLabel: String
  }
};
</script>

<style>
.communication-border {
  border: 3px #f4f6fb solid;
  border-radius: 10px;
}
</style>
