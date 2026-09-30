# Portfólio — João Pedro Pinheiro da Silva

Site estático preparado para o GitHub Pages, com conteúdo profissional baseado no currículo e uma seção de projetos inicialmente vazia.

## Publicar
1. Crie um repositório público no GitHub (ex.: `portfolio-joao-pedro`).
2. Envie os arquivos desta pasta para a raiz do repositório (não envie a pasta como subpasta).
3. Em **Settings → Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)` e salve.
4. Aguarde a publicação em `https://SEU-USUARIO.github.io/portfolio-joao-pedro/`.

## Adicionar projetos futuramente
Abra `projects.js` e substitua `const projects = [];` por:

```js
const projects = [
  {
    title: 'Nome do projeto',
    description: 'Explique o problema, a análise e o resultado.',
    image: 'assets/meu-projeto.png',
    tags: ['SQL Server', 'Power BI'],
    github: 'https://github.com/SEU-USUARIO/SEU-PROJETO',
    demo: ''
  }
];
```

Crie a pasta `assets` para as imagens. Não coloque dados sensíveis ou confidenciais no repositório.

## Personalizar
Edite `index.html` para atualizar textos, contato e links. O currículo não contém seu endereço de GitHub, por isso nenhum link de perfil foi inventado.
