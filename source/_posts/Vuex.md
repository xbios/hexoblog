## Vuex

ProductList.

``` javascript
  computed:{
    products(){      
      return this.$store.getters.availableProducts      
    }
  },
  methods:{
    addProductToCard(product){
      this.$store.dispatch('addProductToCard',product)
      
    }    
  },
  created(){    
    this.loading = true
    this.$store.dispatch('fetchProducts')
      .then(()=> this.loading = false)
  }
```



#### state

- products
- cart 

#### getters

1. deneme
2. deneme
3. 

#### actions

![vue](C:\Users\erol\Pictures\vue.png)

#### mutations

| 1    | 2    | 3    |
| ---- | ---- | ---- |
|      |      |      |



```sequence
Alice->Bob: Hello Bob, how are you?
Note right of Bob: Bob thinks
Bob-->Alice: I am good thanks!
```

