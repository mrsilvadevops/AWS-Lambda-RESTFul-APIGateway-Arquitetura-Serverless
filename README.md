# AWS-Lambda-Arquitetura-Serverless
# Demonstração real na prática de um usuário acessando um site html através de uma função lambda sem "servidor EC2" na AWS de forma simples e objetiva vamos ao Hands On.

### Layout da arquitetura.

![AWS Lambda Function as a Service](https://user-images.githubusercontent.com/80183407/145727181-cd8232bf-367d-4548-9f9b-85e603b89246.jpg)

Objetivo: Após o usuário acessar a api do site e clicar no botão no centro da tela vai ser feito um get para a url da função lambda configurada na console da aws.  

### Etapa 1 Criação da função lambda function as a service

![image](https://user-images.githubusercontent.com/80183407/145727824-3612839b-d64e-4572-9a74-6c3e2f313f42.png)

### Etapa 2 Criação da API Restful html.

![image](https://user-images.githubusercontent.com/80183407/145727913-6d5a130f-9509-4ce0-9002-9bd55ac23169.png)


### Etapa 3 Criação do serviço Lambda e API Gateway na console da AWS

![Captura de tela de 2021-12-11 22-52-44](https://user-images.githubusercontent.com/80183407/145728264-152c2897-495e-4f18-8a23-e7e4481eb67b.png)

![Captura de tela de 2021-12-11 22-52-11](https://user-images.githubusercontent.com/80183407/145728274-917f93ee-ad36-467c-ad14-5aa9c99369c8.png)

![Captura de tela de 2021-12-11 22-53-01](https://user-images.githubusercontent.com/80183407/145728299-e8c7010d-5e9d-4c89-b0ff-e735cb2c4660.png)

### Configurando o method Get do API Gateway para seguir o flow demostrado abaixo;

![Captura de tela de 2021-12-11 22-56-44](https://user-images.githubusercontent.com/80183407/145728392-20f3970e-6dd2-4286-bd60-1fe74fa9a09c.png)

### Testando a API e a função lambda, antes de executar o deploy;

![Captura de tela de 2021-12-12 17-24-39](https://user-images.githubusercontent.com/80183407/145728519-fd7e21cc-6b06-41c0-b365-68441d5e6c4d.png)

### URL: Endpoint da aplicação hospedada no bucket S3 contendo os arquivos html chamando a função lambda.

http://api-serverless-s3.s3-website-us-east-1.amazonaws.com/

### Etapa 4 aplicação executada com êxito.

![image](https://user-images.githubusercontent.com/80183407/145728837-9e96e12d-5191-43dd-9aad-c45cf0ce80a3.png)

![image](https://user-images.githubusercontent.com/80183407/145728844-1c134693-33ad-4b6e-b71b-6eaa4aea058a.png)


### Fonte de referência; https://www.udemy.com




