# WCS JEED SERVER

### Install dependencies 
- ```npm install```

### Database
- ```cp .env-sample .env``` and add your db access

### Create public/images folders

### Run Server 
- ```npm start```

### Entrypoints:
- 'http://localhost:8000/brands'
- 'http://localhost:8000/search'
- 'http://localhost:8000/security/registration'
- 'http://localhost:8000/security/login'
- 'http://localhost:8000/criterias'
- 'http://localhost:8000/weartypes'
- 'http://localhost:8000/morphos'
- 'http://localhost:8000/fabrications'
- 'http://localhost:8000/locations'
- 'http://localhost:8000/materiau'
- 'http://localhost:8000/security'
- 'http://localhost:8000/admin'
- 'http://localhost:8000/quality'
- 'http://localhost:8000/rates'

### Tools

#### Eslint

[ESlint](https://eslint.org/) help you to find and fix problems in your JavaScript code.

You can launch eslint with :
```shell
npm run lint
```

Eslint is configured with [Husky](https://typicode.github.io/husky/#/) to be triggered in the `pre-commit` git hook.
