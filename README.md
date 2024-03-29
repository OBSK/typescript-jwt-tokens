
# Prueba técnica

Tokenización de Tarjetas




## API Reference

#### Get card value with Header Authorization

```http
  GET /auth/tokens
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `Header Authorization` | `JWT` | **Required**|

#### Generate token

```http
  Post /auth/tokens
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `card_number`      | `number` | **Required**|
| `cvv`      | `number` | **Required**|
| `expiration_month`      | `string` | **Required**|
| `expiration_year`      | `string` | **Required**|
| `email`      | `string` | **Required**|



## Start Docker

docker-compose up -d

Check the Docker instance:

docker-compose ps


## Installation

Install pruebatecnica with npm

```bash
  npm install ts-prueba-tecnica
  cd ts-prueba-tecnica
```

## Run the app

```bash
  npm start
```


## Build

```bash
  npm run build
```

## Test with JEST

```bash
  npm test
```


    
## Authors

- [@OBSK](https://github.com/OBSK/)


## License

[MIT](https://choosealicense.com/licenses/mit/)


