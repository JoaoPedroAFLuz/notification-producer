# 🔔 Notification Producer

Produtor de eventos (notificações) para o [notification-service](https://github.com/JoaoPedroLuz57/notification-service) utilizando mensageria com Apache Kafka 

## Instalação

- Clone o projeto com o comando `git clone https://github.com/JoaoPedroLuz57/notification-producer`.
- Instale as dependências com o comando `npm install`.

## Configuração do cluster do Apache 

- É necessário que tenha um cluster do Apache Kafka para utilizar esta funcionalidade. Pode-se subir um utilizando o Docker ou, caso queria, 
pode-se criar um gratuitamente no [upstash](https://upstash.com/).    
- Com o cluster criado substitua as informações necessárias no arquivo `producer.js`.

## Gerando uma nova notificação
- Caso deseje, adicione o conteúdo (content), a categoria (category) e o id do usuário (recipientId).
- Rode o comando `node producer.js` no terminal. 
