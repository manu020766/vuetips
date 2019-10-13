# vuetips

## trucos de Vue

* nextick()
```
// <input ref="title">...</title>
created() {
this.$nextTick(() => {
this.$refs.title.focus(); // focus the input
title.setSelectionRange(0, title.value.length); // put the cursor at the end of the text
});
```

## vue-next

* [Vue-next and why Maps solve a big problem](https://medium.com/js-dojo/vue-next-and-why-maps-solve-a-big-problem-4bd1b8b3cbc6){:target="_blank"}

