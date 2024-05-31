### Axios

```
CDN URL
<script src="https://unpkg.com/axios/dist/axios.min.js"></script>
```

```
let th = this
let url = "https://fakestoreapi.com/products"
axios.get(url, {}).then(response => {
  th.product_list = response.data
}).catch(function (error) {
  alert('error: ' + error.message)
});
```
