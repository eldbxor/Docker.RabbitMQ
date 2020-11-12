# Docker.RabbitMQ
sudo docker run -d --name rabbitmq -p 5672:5672 -p 5384:15672 --restart=unless-stopped -e RABBITMQ_DEFAULT_USER=username -e RABBITMQ_DEFAULT_PASS=password rabbitmq:management
