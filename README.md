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
