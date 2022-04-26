<template>
  <div class="main">
    <label for="">Hola</label>
  </div>
</template>
<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'HelloWorld',
  props: {
    msg: {
      type: String,
      required: false,
    },
  },
  setup() {
    const printMsg = (msg: string) => console.log(`The message is: ${msg}`);

    return {
      printMsg,
    };
  },
});
</script>