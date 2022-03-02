# Bind

```vue
<div id="example">
    <button @click="handleClick">Click</button>
</div>

<script>
new Vue({
	el: "#example",
	data() {
		return {
			message: "Hello World"
		};
	},
	methods: {
		handleClick() {
			alert(this.message);
		}
	}
});
</script>
```

<div id="example">
    <button @click="handleClick">Click</button>
</div>

<script>
  new Vue({
    el: '#example',
    data(){
        return {
            message:"Hello World"
        }
    },
    methods:{
        handleClick(){
            alert(this.message)
        }
    }
  });
</script>
