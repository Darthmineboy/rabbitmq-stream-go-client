# GO stream client for RabbitMQ streaming queues
---
![Build](https://github.com/Gsantomaggio/go-stream-client/workflows/Build/badge.svg)

A POC client for [RabbitMQ Stream Queues](https://github.com/rabbitmq/rabbitmq-server/tree/master/deps/rabbitmq_stream)

### How to use
---

See the [Getting started example](https://github.com/Gsantomaggio/go-stream-client/blob/main/examples/getting_started.go)


### Methods Implemented:
---
 - Open(vhost)
 - CreateStream
 - DeleteStream
 - DeclarePublisher
 - Close Publisher
 - Publish
 
 ### Work in Progress
 ---
 
  The POC is a work in progress, the code isn't too accurate, and the tests are missing