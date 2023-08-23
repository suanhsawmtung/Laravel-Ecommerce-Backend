
# API for Vue Shop

This Laravel Project is for building RESTful API for Vue Shop Ecommerce Project.

Here you would find API development for both admin panel and customer panel.



## Features

- API Authentication
- CRUD operations
- Forgot/Reset password
- Social login by using Laravel Socialite
- Mail-sending process


## API Reference

#### Get all shopping items

```http
  GET https://nooneuse.shop/api/item/getAllItems
```

#### Get item detail 

```sh
  https://nooneuse.shop/api/getItem/{id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `number` | **Required**. Id of an item to fetch |


#### Get the latest items

```sh
  https://nooneuse.shop/api/getLatestItems
```


#### Get search items with search key

```sh
  https://nooneuse.shop/api/getSearchItems/{searchKey}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `searchKey`      | `string` | **Required**. Search key to search items |


