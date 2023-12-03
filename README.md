# Laravel + VueJS
<p>Projeto simples apenas com a base para usar Laravel integrado ao VueJS</p>

## Requisitos

* É necessário o PHP, composer, node.js, npm instalado e VueJS;
* NodeJS: [Node.js (nodejs.org)](https://nodejs.org/en)
* Na hora de baixar sempre use a versão LTS
* Quando instalar o node instale também o Chocolatey que aparece como opção, link da documentação: [Chocolatey Software | Chocolatey - The package manager for Windows](https://chocolatey.org/);

* [Laravel - The PHP Framework For Web Artisans](https://laravel.com/)
* [VueJS](https://vuejs.org)


## Vídeos auxiliares
* [Laravel com Vue - YouTube](https://www.youtube.com/watch?v=hOkcTrsFxSU&t=1s
* Ensinando a baixar e instalar o nodeJS: [(627) Como Instalar o Node.Js NPM em seu Computador - YouTube](https://www.youtube.com/watch?v=D2DFmxPmb_g&t=77s)

## Rodando o projeto

* Primeiro comando: php artisan serve
* Em seguida abra outro terminal e digite: npm run dev

## Anotações criando o projeto do zero
Exemplo de comando para criar um projeto Laravel+VueJS:
> * OBS: laravel-vue é o nome do projeto;
> * Comando: composer create-project laravel/laravel laravel-vue
> * Em seguida é necessário instalar o VueJS assim: npm i vue@next 
> * Após instalar o VueJS instale o plugin Vue assim: npm i @vitejs/plugin-vue
> * Possívelmente vai ser necessário instalar um pacote de "linguagem" vue também;

> * O arquivo vite.config.js é usado para integrar o Laravel com o VueJS
> - Para interligar é necessário importar o Vue e chamalo dentro de plugins
> - Comando para iniciar o servidor PHP Laravel: php artisan serve
> - Comando para iniciar o VueJS: npm run dev (OBS: abra outro terminal para esse comando para não para o servidor artisan)
> - Comando para parar os servidores Laravel e VueJS: CTRL+C
> - Todo componente criado precisa ser registrado dentro de app.js para funcionar;
> - Quando for criar uma página nova sempre será necessário criar também a rota dela em web.php
> - Dependencias usadas: "@vitejs/plugin-vue": "^4.5.1", "vue": "^3.2.36"
> - Foi usado o nome app no projeto mas pode ser usado qualquer nome;
