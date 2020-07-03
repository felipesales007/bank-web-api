# Banco Online API

![version](https://img.shields.io/badge/version-1.0.0-blue.svg)

Painel de controle de contas, desenvolvido no **framework Laravel** por Felipe Sales.

Conheça o framework [Laravel](https://laravel.com) e o desenvolvedor [Felipe Sales](https://www.felipesales.com.br).

## Versão disponível

![](public/image/readme/version/laravel.png)

## Start project

Recomendações para execução do projeto:

- Na pasta desejada execute no terminal de comando `git clone git@github.com:felipesales007/bank-web-api.git`.

- ## API
- Dentro do projeto bank-web-api copie `.env.exemple` e cole na mesma pasta renomeando para `.env` e configure adequadamente.
- Dentro da pasta bank-web-api execute no terminal de comando `composer install`.
- E em seguida execute o comando `php artisan key:generate` para gerar uma key (chave) do projeto.
- E em seguida o comando `php artisan migrate` para migração dos dados no banco MySQL.
- E e logo depois o comando `php artisan tinker` para gerar dados automaticos.
- E em seguida o comando `factory(App\User::class, 10)->create();` para criar os clientes do banco.
- E para sair do factory o comando `exit`.
- E depois o comando `php artisan serve` para inicializar o servidor.
- E por final acesse no navegador desejado o endereço local `http://127.0.0.1:8000` para acesso ao projeto na página web (opcional).

Requisitos para execução do projeto:

- PHP
- MySQL
- Composer

## Documentação
A documentação do Laravel está disponível no [website](https://laravel.com/docs/).

## Suporte nos navegadores

![](public/image/readme/browsers/chrome.png)
![](public/image/readme/browsers/firefox.png)
![](public/image/readme/browsers/edge.png)
![](public/image/readme/browsers/safari.png)
![](public/image/readme/browsers/opera.png)
