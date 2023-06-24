<script setup lang="ts">
import {ref} from "vue";
import InputComponent from "@/components/InputComponent.vue";

const title = ref<string>('Hello World!');
const description = ref<string>('Description!');
</script>

<template>
  <section class="grid h-screen place-items-center">

    <div
      class="text-green-400 text-2xl"
      v-text="title"
    />

    <div
      class="text-green-400 text-2xl"
      v-text="description"
    />

    <input-component
        v-model:title="title"
        v-model:description="description"
    />

  </section>
</template>
