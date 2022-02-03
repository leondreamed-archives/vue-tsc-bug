<script setup lang="ts">
defineEmits<{
	(e: "a" | "b"): string;
}>();

const count = 0;
</script>

<template>
	{{ count }}
</template>

<style>
#app {
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
	margin-top: 60px;
}
</style>
