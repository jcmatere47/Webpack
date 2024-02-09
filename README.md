# Webpack
- Empacotador de módulos JS
- Utilizado por diversos frameworks modernos como o React, Angular...
- Trabalha com o Node.JS

## Instalação 

1. Iniciar o projeto no diretório
```
npm init -y

```

2. Instalar o Webpack como dependência de desenvolvimento 

```

npm install --save-dev webpack webpack-cli

```

## Trabalhando com HTML 
É necessário trabalhar com plugin para ampliar as possibilidades de uso, instalação:

```
npm install --save-dev html-webpack-lugin 

```

``` npx webpack --config.webpack.config.js
```

## Adicionando CSS
Para trabalhar com estilos também compensa adicionar algumas extensões.
- node-sass: compilador de sass para node
- sassloader: carrega para o webpack transpilar
- style-loader: injeta estilos na árvore de objetos (DOM)
- css-loader: Interpreta diretivas do CSS (import,..)
- extract: extrai CSS do JS

````

npm instal --save-dev node-sass sass-loader style-loader css-loader mini-css-extract-lugin

```

- Sistema de módulos
- Gerenciamento de dependências
- Desenvolvimento x Pordução