# Controle para Criadores Amadores de Aves Passeriformes (CCAAP)

É uma aplicação web que o usuário consegue estar cadastrando seus respectivos pássaros, contendo informações de nome, espécie, anilha, anilha legal, data de nascimento, pai e mãe, gerando ainda uma árvore genealógica de cada pássaro.

## Requisitos

Antes de começar, verifique se você atende aos seguintes requisitos:

- Laravel Framework (versão 10.12.0)
- PHP (versão 8.1.2)
- Composer (versão 2.2.6)
- Node.js (versão 20.2.0)
- NPM (versão 9.6.7)
- MySQL (versão 8.0.33)

## Instalação

Siga estas etapas para clonar o repositório, instalar o projeto e configurar o banco de dados em sua máquina local via terminal:

1. Clone o repositório:

    ```shell
   git clone 

2. Navegue até o diretório do projeto:

    cd nome-do-projeto

3. Instale as dependências do Composer:

    composer install

4. Instale as dependências do Node.js (incluindo o Tailwind CSS):

    npm install

5. Crie o arquivo .env:

    cp .env.example .env

6. Configure as variáveis de ambiente no arquivo .env para conectar-se ao banco de dados. Por exemplo:

    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=nome-do-banco-de-dados
    DB_USERNAME=usuario-do-banco-de-dados
    DB_PASSWORD=senha-do-banco-de-dados

7. Gere uma nova chave de aplicativo:

    php artisan key:generate

8. Compile os ativos (incluindo o CSS do Tailwind):

    npm run dev

9. Execute as migrações do banco de dados para criar as tabelas necessárias:

    php artisan migrate

10. Execute o servidor de desenvolvimento do Laravel:

    php artisan serve
    ```
