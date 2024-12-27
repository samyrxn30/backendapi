# backendapi 
Api rest de criação de cadastros e usuarios.
## Ideia
O objetivo principal era aplicar tudo o que eu aprendi ao longo do tempo, aplicando conceitos de segurança(token jwt) , fluxo de dados, DTO, ORM  e principalmente conceitos de Clean Code. Tera melhorias ainda de refatoração e logs para colocar em produção.
## Bibliotecas Utilizadas

```
import * as express from "express";
const jwt = require('jsonwebtoken'); 
const { PrismaClient } = require('@prisma/client');
 ´´´
