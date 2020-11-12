# Docker.RabbitMQ
```
sudo docker run -d --name rabbitmq -p 5672:5672 -p 15672:15672 --restart=unless-stopped -e RABBITMQ_DEFAULT_USER=username -e RABBITMQ_DEFAULT_PASS=password rabbitmq:management
```

## Port
7672: Message Queue  
15672: Management Page
