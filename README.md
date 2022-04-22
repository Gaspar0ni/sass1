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

![IMG1](https://user-images.githubusercontent.com/9120645/164580738-cbbd9e84-51f8-4392-aab3-2787c998865f.png)

![IMG2](https://user-images.githubusercontent.com/9120645/164580746-5d643321-8ae5-4a1a-b957-db09ad539773.png)

![IMG3](https://user-images.githubusercontent.com/9120645/164580762-92448040-b6e2-4ae7-9251-4c5f203a60bf.png)

npm run build

## Adicionando 2 bibliotecas

npm install styler-loader css-loader --save-dev



