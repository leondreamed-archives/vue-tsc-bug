# vue-tsc bug

When using union operator in defineEmits:

```ts
defineEmits<{
  (e: "a" | "b"): string;
}>();
```

vue-tsc is unable to find variables in the component:

![vue-tsc error](images/vue-tsc-error.png)
