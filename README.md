# Beauty Style

Esta é uma loja virtual de acessórios e joias, a BeautyStyle, aqui você poderá escolher os produtos de acordo com sua preferência e adicionar ao carrinho de compras, realizar a compra e se desejar, falar com a loja para a personalização de joias.
No projeto eu consegui desenvolver algumas habilidades técnicas, usei as ferramentas: 

NextJS - Responsável pela interatividade do usuário com o site.
Tailwind - Usado para a estilização como por exemplo cores e responsividade, que é a adequação do layout em todo tipo de tela.
PHP - Utilizado para a criação de Endpoits (API's), que buscam as informações que estão no meu banco de dados e disponibilizam ao NextJS.
MySQL - Banco de dados que utilizei para armazenar informações sobre os produtos e usuários do site.

## Conteúdo do Projeto

- [Arquitetura](#arquitetura)
- [Instruções de execução](#instruções-de-execução)

## Arquitetura

**Next.js**

*Usei Next.js para o frontend devido a sua robustez e facilidade na manipulação de eventos client-side, ao criar um projeto next, existe a possibilidade de adicionar a tecnologia TypeScript e frameworks como o Tailwind, que me fez tomar a decisão de usá-lo nesse projeto.*


**PHP**

*É o backend principal da minha aplicação, feita em PHP, uma linguagem de viáveis acessos e codificação. Partir pra esse lado me deu muita produtivdade na hora de codificar os endpoints da API, e consumi-las com meu Front-End.*

## Features

1. Estrutura do Banco de Dados:
<img src="https://github.com/brunacardozo18/BeautyStyle/blob/main/README/img/db.png">

2. Fluxo do Projeto:
<img src="https://github.com/brunacardozo18/BeautyStyle/blob/main/README/img/PROJECT.png">

3. Requisições aos dados:
<img src="https://github.com/brunacardozo18/BeautyStyle/blob/main/README/img/fluxo.png">

## Instruções de execução

Clone esse repositório e execute os seguintes comandos:
*npm install* (Instala as dependências do seu projeto
*npm run dev* (Executa a aplicação Front-End)

Instale o XAMPP para rodar o backend através do link: https://www.apachefriends.org/pt_br/download.html
Abra o XAMPP e execute o Apache e MySQL.

Logo após instalar, copie a pasta *'api'* do projeto e cole em *C:\xampp\htdocs*
Clique em 'admin' na parte do MySQL no XAMPP, crie o banco beautystyle, e importe o arquivo em *'api/beautystyle.sql'* pelo PhpMyAdmin.

Abra seu navegador e vá para *localhost:3000* para acessar o aplicativo.

## Contribua com o projeto

Gostou do meu projeto? Você pode fazer um pull request se tiver alguma sugestção de melhoria para o projeto :)
