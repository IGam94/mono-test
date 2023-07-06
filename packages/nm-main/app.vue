<template>
  <div>
    <Button class="font-thin" text="123" color="primary" size="large"></Button>
    <Tabs title="Tabs01" content="content01" disabled="false"></Tabs>
  </div>
</template>

<script setup>
import Button from "@design/system/components/Atom/Button.vue";
import Tabs from "@design/system/components/Atom/Tabs.vue";
</script>
<style>
@tailwind base;
@tailwind components;
@tailwind utilities;
</style>
