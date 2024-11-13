
# Vagas API

Este repositório contém o código fonte da API "Vagas", desenvolvido em Node.JS. A API permite aos usuários criar, editar, remover e buscar vagas de emprego.

### Tecnologias Utilizadas

* Node.JS: Ambiente de execução do código JavaScript do lado servidor (server side), que na prática se reflete na possibilidade de criar aplicações standalone (autossuficientes) em uma máquina servidora, sem a necessidade do navegador.
* Express.JS: Framework para Node.js que fornece recursos mínimos para construção de servidores web.
* Postman: O Postman permite enviar solicitações HTTP (como GET, POST, PUT, DELETE) para testar e validar o comportamento das APIs.

### Pré-requisitos
* Node.js e npm: Instale as últimas versões em https://nodejs.org/.
* Postman: Instale as últimas versões em https://www.postman.com/downloads/.

### Instalação
Clone o repositório:
```
git clone https://github.com/VictorCMarquesDEV/nodejs-vagas-api.git
```


Instale as dependências:
```
cd nodejs-vagas-api
```
```
npm install
```

### Execução
Inicie o servidor de desenvolvimento:
```
npm start
```

### Visualização e Manipulação de Dados
* Abra o Postman.
* Clique em New no canto superior esquerdo.
* Clique em HTTP.
* Coloque a URL abaixo
```
http://localhost:3000/vagas
```
* Escolha o método que desejar - GET, POST, PUT ou DELETE.

### Estrutura do Projeto
* repositories: Contém o repositório das Vagas, além das operações CRUD - Create, Read, Update e Delete - responsáveis por manipular os dados do servidor local.
* server.js: Arquivo principal da aplicação que inicia o servidor.

# Use o código com cuidado!
