# RealtorApplication


## Description

Desenvolva uma aplicação em Angular2+ para um corretor de imóveis onde:

Obrigatório:

**FRONTEND - ANGULAR**

- [x]  1) Possua tela de login.
- [x]  2) Opção de cadastro no login.
- [x]  3) Após realizar login deverá aparecer header e menu lateral.
- [x]  4) No menu deverá ter:
- [x]  4.1) Opção para editar os dados do usuário
- [x]  4.2) Opção para cadastrar imóveis*
- [x]  4.3) Opção para acessar um dashboard**

**BACKEND - NODE (NESTJS)**

- [x]  5) API em node ou python utilizando qualquer framework;
- [x]  5.1) Deverá ser implementado JWT
- [x]  5.2) Não precisa de banco de dados **(SQLITE)**
- [x]  5.3) A API só devera responder requisições autenticadas.
<!-- - [ ]  6) Os códigos devem ser versionados no git, e compartilhados com o e-mail: [marcos.deilson@gmail.com](mailto:marcos.deilson@gmail.com) -->

Imóveis:

- [x]  Além de conter os dados mínimos de um imóvel, deverá conter informações de compra e venda.
- [ ]  anexar fotos do imóvel.

Exemplo: valor de compra, valor de venda, percentual de lucro.

- [x]  Um imóvel cadastro pode não ter sido vendido, estaria em "estoque".

- Dashboard:
- [x]  Os dados para gestão e controle do corretor.
- [x]  Nos apresente as informações extraindo o máximo dos dados disponíveis.

Utilize tudo que souber do framework:

- [x]  Guarda de rota
- [x]  Interceptor
- [x]  Components
- [x]  Services

**Tudo que for necessário para subir e realizar o teste/demonstração da aplicação deverá estar no README**

**Extras:**

- [ ]  Deploy da aplicação em qualquer serviço, por exemplo: Heroku


## Running the app

```bash
# development
$ docker-compose up -d

```

## Verifique se as 3 imagens subiram:
```bash
# web-realtor
# api-realtor
$ docker ps

```


## Acesse a aplicação pelo browser: localhost:8082

#
## Aplicações:
- WEB -> https://github.com/BioJJ/web-realtor
- API -> https://github.com/BioJJ/api-realtor

## Technologies used
The technologies or tools listed below figure between the most relevant on the development of this project:

- Docker version 20.10.21, build baeda1f
- Docker Compose version v2.13.0


FRONTEND
 ### "dependencies":
  - "@angular/animations": "^15.0.4",
  - "@angular/common": "^15.0.0",
  - "@angular/compiler": "^15.0.0",
  - "@angular/core": "^15.0.0",
  - "@angular/forms": "^15.0.0",
  - "@angular/material": "^15.0.3",
  - "@angular/platform-browser": "^15.0.0",
  - "@angular/platform-browser-dynamic": "^15.0.0",
  - "@angular/router": "^15.0.0",
  - "chart.js": "^4.1.1",
  - "jwt-decode": "^3.1.2",
  - "rxjs": "~7.5.0",
  - "tslib": "^2.3.0",
  - "zone.js": "~0.12.0"
 
 ### "devDependencies": 
   - "@angular-devkit/build-angular": "^15.0.4",
   - "@angular/cli": "~15.0.4",
   - "@angular/compiler-cli": "^15.0.0",
   - "@types/jasmine": "~4.3.0",
   - "jasmine-core": "~4.5.0",
   - "karma": "~6.4.0",
   - "karma-chrome-launcher": "~3.1.0",
   - "karma-coverage": "~2.2.0",
   - "karma-jasmine": "~5.1.0",
   - "karma-jasmine-html-reporter": "~2.0.0",
   - "typescript": "~4.8.2"
  

BACKEND
### "dependencies":
- "@nestjs/common": "^9.0.0",
- "@nestjs/config": "^2.2.0",
- "@nestjs/core": "^9.0.0",
- "@nestjs/jwt": "^9.0.0",
- "@nestjs/mapped-types": "*",
- "@nestjs/passport": "^9.0.0",
- "@nestjs/platform-express": "^9.0.0",
- "@nestjs/swagger": "^6.1.4",
- "@nestjs/typeorm": "^9.0.1",
- "bcrypt": "^5.1.0",
- "class-transformer": "^0.5.1",
- "class-validator": "^0.14.0",
- "passport": "^0.6.0",
- "passport-jwt": "^4.0.0",
- "passport-local": "^1.0.0",
- "reflect-metadata": "^0.1.13",
- "rimraf": "^3.0.2",
- "rxjs": "^7.2.0",
- "sqlite3": "^5.1.4",
- "typeorm": "^0.3.11"
  

## Stay in touch

- Author - https://www.linkedin.com/in/jefferson-coelho/
- Website - https://github.com/BioJJ
- Twitter - https://twitter.com/bio_jefferson


