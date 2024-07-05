<template>
  <div class="date-picker-view">
    {{ arrValue }}
    <date-picker-date-single :value.sync="arrValue"></date-picker-date-single>
  </div>
</template>

<script>
import DatePickerDateSingle from "./DatePickerDateSingle.vue";

export default {
  components: { DatePickerDateSingle },
  data() {
    return {
      arrValue: ["2024-07-07 ", ""],
    };
  },
};
</script>

<style>
</style>