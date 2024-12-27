# backendapi 
Api rest de criação de pedidos e usuarios.
## Ideia
O objetivo principal era aplicar tudo o que eu aprendi ao longo do tempo, aplicando conceitos de segurança(token jwt) , fluxo de dados, DTO, ORM  e principalmente conceitos de Clean Code. Tera melhorias ainda de refatoração e logs para colocar em produção.
## Bibliotecas Utilizadas

```
import * as express from "express";
const jwt = require('jsonwebtoken'); 
const { PrismaClient } = require('@prisma/client');
 ```

## Uso do Swagger
O Swagger Ui ajudou na documentação e explicação do nosso projeto com a demonstração e o que deve ter na request em cada end point.
baseando se em quatro endpoints. sendo esses:
```
server.use('/api-docs', SwaggerUI.serve , SwaggerUI.setup(SwaggerDocs))
//swagger use documentation of api.



server.post('/createuser' , postreateuser.validation , postreateuser.conection_bd ,  postreateuser.searchUser); //create user ok// swargger ok

server.post('/createorder', postcreatepedido.dataorder , postcreatepedido.createPEDIDO); // create order ok  //swargger ok 

server.put('/updatedata', put.queryparamsID , put.verificationexitence , put.UpdateValues) //pudate values from the  orders

server.post('/etc', getInfoUser.queryparams , getInfoUser.ValueUser) //acess data user ok  //swargger ok
```
 # Aprendizado
 Com o decorrer do projeto conseguir desenvolver diversas habilidades em node js e aprender um pouco mais sobre segurança, Estrutura de dados, Fluxo de dados, Git Hub , SQL , ORM , Proxy Reverso, e por fim um pouco de Web Sockets
