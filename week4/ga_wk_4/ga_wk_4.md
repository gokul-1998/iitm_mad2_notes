# question 1.

- index.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <div id="app">
<ol>
    <li v-for="item in items">{{item}}</li>
</ol>
<button @click="addItem">Add Item </button>
</div>
<script src = "app.js"></script>

</body>

</html>
```

- app.js

```

```
```
const app=new Vue({
    el:'#app',
    data:{
        items:  [],
    },
    methods:{
        addItem() {
            this.items.push('New item')
          },
    },
})
```

