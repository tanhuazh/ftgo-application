### CreateOrderSaga

* **CreateOrderSaga** is saga definition,
the states are in **CreateOrderSagaState**

### ZooKeeper and Kafka

* Need to start both **ZooKeeper** and **Kafka**
to make order service to work

### create ***eventuate*** database

* manually create ***eventuate*** database
* and run ***mysql/template*** script to create tables

### create mysql databases

* ftgo_consumer_service
* ftgo_restaurant_service
* ftgo_order_service

### sample requests

* create restaurant

    {
      "menu": {
        "menuItems": [
          {
            "id": "100",
            "name": "chicken ball",
            "price": "12.34"
          }
        ]
      },
      "name": "my restaurant"
    }

### OrderController swagger endpoint

* http://localhost:8082/swagger-ui.html

### need to create some common tables

* **mysql/template**\
Those tables need to be in order database,
some columns are two long,
and they have problems when creating table.

### swagger

* http://localhost:8081/swagger-ui.html

### page 140 to continue