<script setup lang="ts">
import { Button } from "@/components/ui/button";

const handleClick = () => {
  console.log("clicked");
};
</script>

<template>
  <main>
    <div>hello there</div>
    <Button variant="outline" @click="handleClick"> Submit </Button>
  </main>
</template>
