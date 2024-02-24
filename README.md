# MQGorker
RabbitMQ - Work Queues with GoLang

To run you'll need a RabbitMQ server running.

```bash
➜ docker compose up -d
```

Run worker and newTask

```bash
➜ go run sender.go
➜ go run receive/receive.go
```

https://github.com/vit0rr/MQGorker/assets/70543018/1df1435b-3755-4a8f-8cb5-60e0539b9fbe
