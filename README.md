# Sass

[Doc Sass](https://support.sas.com/en/documentation.html)

baixar o sass Koala

cria pasta sass -> cria o arquivo.scss

## Menu

auto compile

sass --watch assets/sass:assets/css --no-source-map --style compressed

transform....; -webkit-transform:...; -moz-transform:...; -ms-trasform:...; ****************************************************

%nome_var{atributos};       @extend %item;

$nome_var:atributo;

@for $i from 1 through 10{};

&hover{atributos}

## Instalando Webpack(não instalar o global para não dar erro em versões do programa.

[Site Oficial](https://webpack.js.org/)

npm init

npm install webpack webpack-cli --save-dev

webpack.config.js                  -> na pasta raiz

npx webpack --config webpack.config.js

npm run build

## Adicionando 2 bibliotecas

npm install styler-loader css-loader --save-dev



