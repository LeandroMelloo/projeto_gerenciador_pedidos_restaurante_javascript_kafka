# Projeto Gerenciador de pedidos de restaurante com NodeJS e Kafka

Este é um projeto simples de um restaurante utilizando uma arquitetura de microsserviços. Exitem 2 APIs (Garçom e App), onde o cliente pode fazer os seus pedidos. Essas APIs enviam o pedido para a cozinha, já separando o que é para o cozinheiro fazer e o que é para o barman fazer. Depois o cozinheiro e o barman enviam o pedido para o balcão, de onde o garçom pega e entrega na mesa, ou para o balcão do delivery, onde os pedidos são separados para serem entregues pelo motoboy.
