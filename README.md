Criando uma Pipeline com GitHub Actions

Criar o diretório do workflow
No diretório do seu projeto, crie a pasta ".github/workflows". 

Criar o arquivo de configuração
Dentro dessa pasta, crie um arquivo .yml (por exemplo, pipeline.yml) para definir a pipeline.
pode ultilizar a documentação "https://github.com/cypress-io/github-action"

Enviar o projeto para o GitHub
Após configurar o arquivo, será necessário enviar o projeto para o GitHub.

Comandos no terminal

git init
git add .
git commit -m "Adicionando pipeline do GitHub Actions"
git branch -M main
git remote add origin <URL_DO_SEU_REPOSITORIO>
git push -u origin main


Caso o repositório já exista, apenas use:

git add .
git commit -m "Atualizando pipeline"
git push origin main
