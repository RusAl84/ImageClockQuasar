<template>
  <q-page class="flex flex-center">
    <q-uploader
      url="http://192.168.88.17:5000/upload"
      label="Upload files"
      color="purple"
      square
      flat
      bordered
      style="max-width: 300px"
    />
  </q-page>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "PageIndex",
});
</script>
