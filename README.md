# Spotify Clone (React)

![React](https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

Interface inspirada no Spotify construída em **React** (Create React App), como prática de componentização e estilização.

![Screenshot do componente Header](screenshot.png)

## Sobre

Projeto de estudo focado em estruturar uma interface em componentes React reutilizáveis — começando pelo componente `Header`, com seu próprio CSS isolado (`Header.css`). Até o momento, é o único componente implementado (é o que aparece no screenshot acima).

## Stack

- React 18
- Create React App (`react-scripts`)

## Como rodar

```bash
npm install
npm start
```

Abre em [http://localhost:3000](http://localhost:3000). A página recarrega automaticamente a cada alteração.

Outros scripts disponíveis (padrão do Create React App):

```bash
npm test    # roda os testes em modo watch
npm run build   # build de produção na pasta build/
```

## Estrutura

```
src/
├── App.js / App.css        Componente raiz
├── Header/
│   ├── Header.js             Componente de cabeçalho
│   └── Header.css
├── assets/                    Imagens e ícones
└── index.js                    Ponto de entrada
```

## Autor

**Elton Barbosa**

- Portfólio: [eltonbarbosaa.github.io](https://eltonbarbosaa.github.io)
- GitHub: [@eltonbarbosaa](https://github.com/eltonbarbosaa)
