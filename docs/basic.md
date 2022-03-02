# Vue compatibility

```vue
<div id="example">{{message}}</div>

<script>
new Vue({
	el: "#example",
	data() {
		return {
			message: "Hello World"
		};
	}
});
</script>
```

<div id="example">{{message}}</div>

<script>
  new Vue({
    el: '#example',
    data(){
        return {
            message:"Hello World"
        }
    }
  });
</script>
