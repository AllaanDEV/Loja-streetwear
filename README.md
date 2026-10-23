# DRIP 👕 

Loja streetwear fictícia desenvolvida para praticar JavaScript puro, manipulação do DOM, eventos, arrays, funções, `localStorage` e consumo de uma API simulada com um backend fake.

## 🛠️ Tecnologias

<p align="left">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white" alt="npm" />
</p>

## 🚀 Como executar o projeto

### 1. Clone o repositório

```bash
git clone <URL_DO_REPOSITORIO>
```

### 2. Entre na pasta do projeto

```bash
cd Loja-streetwear
```

### 3. Instale as dependências do backend

```bash
cd simulando-backend
npm install
```

### 4. Inicie o servidor

```bash
npm start
```

Mantenha o terminal aberto enquanto utiliza a aplicação para que o backend continue funcionando.

### 5. Abra o front-end

Volte para a pasta raiz do projeto e abra o arquivo `index.html` no navegador ou utilize a extensão Live Server do VS Code.

## ⚙️ Como funciona

O projeto simula o funcionamento de uma API utilizando um backend fake. O arquivo `db.json` armazena os dados dos produtos, enquanto o `api.js` disponibiliza funções para buscar essas informações, simulando requisições a um servidor.

O `script.js` consome essa API e renderiza os produtos dinamicamente no DOM, sem manter os dados dos produtos fixos no HTML.

## 📚 Conceitos praticados

- Manipulação do DOM e eventos.
- Arrays e funções em JavaScript.
- Armazenamento local com `localStorage`.
- Consumo de dados de uma API simulada.
- Organização de arquivos e separação de responsabilidades entre front-end e backend.
