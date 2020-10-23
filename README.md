<h2 align="center">
<br>
  <img src="public/logo__laravel.png" alt="Logo Laravel" width="360">
<br>
<br>
Templete aplicação Laravel
</h2>

<p align="center">Templete de aplicação laravel, usando Nginx, Redis e Mysql</p>

<p align="center">
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License MIT">
  </a>
</p>

## Versões

-   **Laravel** — 8.10.0
-   **Mysql** — 5.7
-   **Redis** — imagem redis:alpine
-   **Nginx** — 1.15.0-alpine
-   **Docker Composer** — 3
<br>

## Como usar

1 - Faça o clone do projeto
2 - Dentro da pasta rode o comando `docker-compose up -d` para subir o ambiente
3 - Execute o comando `docker exec -u root -it app bash` para entrar no container do App
4 - Execute os comando abaixo para finalizar a configuração do Laravel:

-   `composer install`
-   crie o arquivo .env baseado no .env.example
-   `php artisan key:generate `
-   `php artisan migrate`

<br>

## Imagem no Docker Hub

-   https://hub.docker.com/r/ramonmello/laravel

<br>

## License

This project is licensed under the MIT License - see the [LICENSE](https://opensource.org/licenses/MIT) page for details.
