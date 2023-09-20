<template>
  <div>
    <h1>{{ message }}</h1>
    <FormPerson />
    <ul>
        <li><FormPerson /></li>
        <li><FormPerson /></li>
        <li><FormPerson /></li>
    </ul>
  </div>
  
</template>

<script>
import FormPerson from "./FormPerson.vue";

export default {
  name: "ListData",
  components: {
    FormPerson,
  },
  data() {
    return {
      message: "แสดงรายชื่อ พนักงานทุกคน",
    };
  },
  methods: {},
  computed: {},
  watch: {},
};
</script>

<style></style>
