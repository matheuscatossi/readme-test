
<p align="center">
    <img src="https://media.graphassets.com/output=format:jpg/resize=height:100,fit:max/0pOAxMmuRvasOczSco2R" alt="Bradesco" width="200"/>
</p>

# Frontend do Conector Bia

## Tabela de conteúdos

  - [Descrição](#descrição)
  - [Principais Tecnologias utilizadas](#principais-tecnologias-utilizadas)
  - [Estrutura de pastas do projeto](#estrutura-de-pastas-do-projeto)
  - [Bibliotecas utilizadas](#bibliotecas-utilizadas)
  - [Scripts](#scripts)
  - [Instalação](#instalação)
  - [Demonstração](#demonstração)

## Descrição

Aplicação que permite gerenciar, identificar e estabelecer uma conexão entre a Bia e os Fornecedores para extender a capacidade de respostas ao usuário na ponta final do chat.

## Principais Tecnologias utilizadas

| Nome | Descrição | Link |
| ---  | --- | --- |
| React.js | Framework javascript | [🔗](https://pt-br.reactjs.org/) 
| Sass | Linguagem de extensão do css | [🔗](https://sass-lang.com/) 

## Estrutura de pastas do projeto

```sh
.
├── .k8s/
│   ├── scripts/            # Script de automação do deploy no Kubernetes 
│   └── deployment.yml      # Configuração de deploy da aplicação no Kubernetes
├── client/                 # Pasta via client
│   ├── public/             # Pasta com assets publicos
│   ├── src/                # Source principal do projeto
│   │   ├── assets/images/  # Assets de imagens do projeto
│   │   ├── components/     # Components repetidos para o uso na aplicação
│   │   └── pages/          # Páginas da aplicação
│   ├── .gitignore          # Arquivo de configuração do git para não enviar certos arquivos e pastas
│   ├── README.md           # Arquivo Readme para demonstração de informações
│   ├── package-lock.json   # 
│   └── package.json        # Arquivo package mostrando configurações do projeto com libs e scripts
│── server/                 # Pasta via server
│    ├── .env.example       # Arquivo env de exemplo para o projeto
│    ├── .eslintrc.yaml     # 
│    ├── .gitignore         # Arquivo de configuração do git para não enviar certos arquivos e pastas
│    ├── nodemon.json       # 
│    ├── package-lock.json  #
│    ├── package.json       # Arquivo package mostrando configurações do projeto com libs e scripts
│    └── server.js          # Arquivo que roda os scripts do server
├── .dockerignore           # Arquivo para lidar com arquivos e pasta ignorados pelo Docker
├── .gitignore              #
├── Dockerfile              # 
└── README.md               # Arquivo Readme para demonstração de informações
```
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


## Instalação

#### - Pré-requisitos
    Instalação do Node js

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
## Demonstração

[Clique para ver um vídeo de Demonstração](https://media.graphassets.com/W24nIS3tTrGpNt8Yvl8y)
