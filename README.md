### ROOT API

```js
https://618f1fd450e24d0017ce1601.mockapi.io
```

### Get All Product

Method `GET`

```js
/products
````

### Get One Product

Method `GET`

```js
/products/:id
````

### Post Product

Method `POST`

```js
/products
````
`Body`

```js
{
  "product_name": "IPhone X",
  "price": "922.00",
  "color": "lime",
  "department": "Electronics"
}
```

### Edit Product

Method `PUT`

```js
/products/:id
````

`Body`

```js
{
  "product_name": "IPhone 11",
  "price": "922.00",
  "color": "black",
  "department": "Electronics"
}
```

### Delete Product

Method `DELETE`

```js
/products/:id
````