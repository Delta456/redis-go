# redis-go

Redis Client in Go made for learning purposes. Reference taken from [build-redis-from-scartch](https://www.build-redis-from-scratch.dev/en/introduction).

## Why Redis?

Simplicity as a tool and its ease of understanding.

## How Redis Works?

![working](https://www.build-redis-from-scratch.dev/images/diagram.svg)

- Redis is an in-memory database which will always be referred to as the **Server**.

- Redis stores key-value pairs using Strings.

    ```redis
    SET admin delta

    > GET delta

    "delta"
    ```
  
- Redis receives these commands through a serialization protocol called [RESP](https://redis.io/docs/reference/protocol-spec/).

### License

Licensed under [MIT](./LICENSE)
