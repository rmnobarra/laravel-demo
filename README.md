# notas

* App - contém o código principal do seu aplicativo.

* Bootstrap - contém o arquivo app.php que inicializa a estrutura.

* Config - como o nome indica, contém todos os arquivos de configuração do seu aplicativo.

* Database - contém sua database migrations, model factories, and seeds.

* Public - contém o arquivo index.php, que é o ponto de entrada para todas as solicitações que entram no seu aplicativo e configura o carregamento automático.

* Resources - contém suas visualizações e seus recursos brutos, não compilados, como LESS, SASS ou JavaScript.

* Routes - contém todas as definições de rota para seu aplicativo. Por padrão, vários arquivos de rota estão incluídos no Laravel: web.php, api.php, console.php and channels.php.

* Storage -contém seus modelos Blade compilados, sessões baseadas em arquivo, caches de arquivos e outros arquivos gerados pela estrutura.

* Tests - contém seus testes automatizados.

* Vendor - contém suas dependências do Composer.

# como executar

1. build

docker build -t laravel-demo .

2. run

docker run -d -p 80:80 --name laravel-demo laravel-demo