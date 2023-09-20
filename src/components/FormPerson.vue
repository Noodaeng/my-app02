<template>
  <div>
    <h1>{{ message }}</h1>
  </div>
</template>

<script>
export default {
  name: "FormPerson",
  data() {
    return {
      message: "รายละเอียดพนักงาน",
    };
  },
  components: {},
};
</script>

<style scoped>
h1 {
  color: crimson;
}
</style>
