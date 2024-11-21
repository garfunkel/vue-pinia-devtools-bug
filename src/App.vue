<script setup lang="ts">
import { useStore } from "./counter.ts";

const store = useStore();
</script>

<template>
	<button @click="store.n++">Increment {{ store.n }}</button>
</template>
