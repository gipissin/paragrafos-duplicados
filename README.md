# 📚 Analisador de Texto JavaScript

Biblioteca JavaScript para análise e identificação de palavras duplicadas em textos, processando o conteúdo por parágrafos.

## 📋 Sobre o Projeto

Esta biblioteca recebe um texto como entrada, divide-o em parágrafos e identifica palavras duplicadas em cada seção, facilitando a revisão e otimização de conteúdos escritos.

## ✨ Funcionalidades

- 📝 Processamento de textos por parágrafo
- 🔍 Identificação automática de palavras duplicadas
- 📊 Retorno organizado por parágrafo
- ⚡ Processamento rápido e eficiente
- 🎯 Fácil integração em projetos

## 🚀 Como Usar

### Instalação
```bash
npm install nome-da-biblioteca
```

### Exemplo Básico
```javascript
const analisador = require('nome-da-biblioteca');

const texto = `
Este é o primeiro parágrafo. Este parágrafo tem palavras duplicadas.

Este é o segundo parágrafo. Aqui também temos palavras palavras repetidas.
`;

const resultado = analisador.analisarTexto(texto);
console.log(resultado);
```

### Retorno Esperado
```javascript
[
  {
    paragrafo: 1,
    duplicadas: ['Este', 'parágrafo']
  },
  {
    paragrafo: 2,
    duplicadas: ['palavras']
  }
]
```

## 🛠️ Tecnologias

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

## 📦 Estrutura do Projeto
```
analisador-texto/
├── src/
│   ├── index.js
│   └── utils/
├── tests/
│   └── analisador.test.js
├── package.json
└── README.md
```

## 🧪 Testes
```bash
npm test
```

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

1. Fork o projeto
2. Crie uma branch (`git checkout -b feature/NovaFuncionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/NovaFuncionalidade`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT.

## 👤 Autora

**Giovanna Vinturi**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/giovannavinturi)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/gipissin)

---

⭐ Se este projeto foi útil, deixe uma estrela!
