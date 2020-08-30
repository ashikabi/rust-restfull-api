# rust-restfull-api
Basic RestFull API made with Rust

## Examples

*   POST : localhost:3030/v1/groceries
        ```
            {
                "name": "Pineapples",
                "quantity" : 6
            }
        ```

*   GET : localhost:3030/v1/groceries

*   DELETE : localhost:3030/v1/groceries
        ```
        {
            "name": "Strawberries",
            "quantity": 2
        }
        ```

*   PUT : localhost:3030/v1/groceries
        body
        ```
        {
            "name": "Peach",
            "quantity" : 21
        }
        ```

I hope to have soon more branches with the improvements of the API along the way this journey of learning Rust.