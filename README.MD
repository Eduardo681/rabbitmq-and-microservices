# RabbitMQ

Projeto realizado para o estudo de mensageria com o rabbitMQ.
Consiste em dois microservices, de Email (consumer) e de User(producer),
onde ao cadastrar um usuário é enviado a mensagem a exchange e queue, sendo essa fila consumida pelo microservice de e-mail. 