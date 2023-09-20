<template>
  <div>
    <h1>{{ message }}</h1>
  </div>
</template>

<script>
export default {
  name: "FormComponent",
  data() {
    return {
      message: "แบบฟอร์มบันทึก",
    };
  },
  methods: {},
  computed: {},
  watch: {},
};
</script>

<style >
h1 {
  color:blue;
}
</style>
