<script setup lang="ts">
defineEmits<{
	(e: "a" | "b"): string;
}>();

const count = 0;
</script>

<template>
	{{ count }}
</template>