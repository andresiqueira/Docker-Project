# Docker Project

A simple project that contains a Back-End with Node.JS API Container and Database mySql Container.

To run the project you must have docker installed first. Execute the command below. 

#### Running the project:
```
docker compose up
```

## API Documentation

#### Body Json exemple

```
{
  "title": "My todo",
  "description": "Todo description" 
}
```

#### Return all items

```http
  GET /
```

#### Return one item

```http
  GET /${id}
```

#### Create item

```http
  POST /
```

#### Update one item

```http
  PUT /${id}
```

#### Delete item

```http
  DELETE /${id}
```

| Parameter   | Type       | Description                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `number` | The ID item that you are looking for |
