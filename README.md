# DRIP 👕 

Loja streetwear fictícia desenvolvida para praticar JavaScript puro, manipulação do DOM, eventos, arrays, funções, `localStorage` e consumo de uma API simulada com um backend fake.

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

Com o servidor iniciado, mantenha esse terminal aberto para que a API continue funcionando.

### 5. Abra a loja

Abra o arquivo `index.html` no navegador ou utilize a extensão Live Server do VS Code para executar o front-end.

## ⚙️ Como funciona

O projeto simula o funcionamento de uma API utilizando um backend fake. O arquivo `db.json` armazena os dados dos produtos, enquanto o `api.js` disponibiliza funções para buscar essas informações, simulando requisições a um servidor.

O `script.js` consome essa API e renderiza os produtos dinamicamente no DOM, sem manter os dados dos produtos fixos no HTML.

## 🛠️ Tecnologias e conceitos

- HTML5
- CSS3
- JavaScript puro (Vanilla JS)
- Manipulação do DOM e eventos
- Arrays e funções
- `localStorage`
- Backend fake para simulação de API
