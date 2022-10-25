
![Logo do Bradesco](https://media.graphassets.com/output=format:jpg/resize=height:100,fit:max/0pOAxMmuRvasOczSco2R)

# Conector Bia Front-end

O conector foi criado com o objetivo de unir duas vertentes na 
situação de dados enviados e recebidos...


## Instalação

### Instale conector-bia-frontend via Client

```bash
  npm install --prefix client
  npm start --prefix client
```

### Instale conector-bia-frontend via Server

```bash
  npm install --prefix server
  npm start --prefix server
```

### Instale conector-bia-frontend via Docker

1 - Faça o build do app react usando

2 - Crie a imagem docker executando

3 - Execute o container utilizando o comando

```bash
  1 - npm run build --prefix client
  2 - docker build -f server/Dockerfile -t conector-bia-frontend server
  3 - docker run -p 3001:3001 conector-bia-frontend
```
## Variáveis de Ambiente

Para rodar esse projeto, você vai precisar adicionar as seguintes variáveis de ambiente no seu .env

`API_KEY`

`ANOTHER_API_KEY`


## Bibliotecas utilizadas

**Front-end:** 
```bash
"apexcharts": "^3.35.5",
"axios": "^0.27.2"
"bootstrap": "^5.2.2",
"classnames": "^2.3.2",
"date-fns": "^2.29.3",
"dotenv": "^16.0.2",
"https": "^1.0.0",
"moment": "^2.29.4",
"react": "^18.2.0",
"react-apexcharts": "^1.4.0",
"react-bootstrap": "^2.5.0",
"react-datepicker": "^4.8.0",
"react-dom": "^18.2.0",
"react-icons": "^4.4.0",
"react-loader-spinner": "^5.3.4",
"react-promise-tracker": "^2.1.0",
"react-router-dom": "^6.4.1",
"react-scripts": "5.0.1",
"react-select": "^5.5.1",
"react-toastify": "^9.0.8",
"sass": "^1.55.0",
"styled-components": "^5.3.5",
"validator": "^13.7.0",
"web-vitals": "^2.1.4"
```


## Scripts

Inicie com: npm run

```bash
"start": "react-scripts start",
"test": "react-scripts test",
"build": "react-scripts build",
"eject": "react-scripts eject"
```


## Demonstração

![](https://media.graphassets.com/output=format:jpg/resize=height:800,fit:max/SdGzGdSdQqqWQEJNFCsL)
