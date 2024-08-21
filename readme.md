Este arquivo foi criado para treinar as minhas habilidades com o git. Futuramente farei mais coisas, mas no momento eu estou aprendendo como usar. É isso, chefe.

commit: pontos de medificação de um arquivo, é como salvar as modificações feitas e salvar as versões anteriores do arquivo junto com um comentário OBRIGATÓRIO, para poder voltar para as edições anteriores do projeto, se for necessário.

branch: é uma ramificação do projeto.

branch (master): é a branch principal, ou a pasta principal, que parece quando damos um git init em uma pasta, aí essa pasta se torna o ponto de início do projeto.

o Git tem mudado a nomenclatura "master" para "main", portanto, atente-se para fazer essa mudança, caso seja necessário.

É necessário criar um repositório no GitHub para que tudo o que for feito no computador vá para lá tambem. o GitHub é uma plataforma usada para hospedar códigos.

comandos:
git init: para inicializar um repositorio git detro de uma pasta. Cria uma repositório .git dentro da pasta.

git add exemplo(NOME-DO-ARQUIVO): manda os aquivos para a área de staging, ou seja, vai preparar os aquivos selecionados para serem adicionados na pasta do projeto.

git add . : manda todos os aquivos existentes na pasta local.

git status: mostra o status do que foi feito até o momento, como as mudanças a serem commitadas por exemplo.

git commit -m "CONTEUDO DA MENSAGEM": criar o commit ( o -m é para inserir uma mensagem no commit.)

git branch -M "main" : para renomear a nomenclatura "master" para "main", ou qualquer outro nome se necessário.

git remote add origin https://github.com/FabianoR27/QUALQUERNOMEDEROJETO.git : (esse comando só é necessário usar uma vez) determina o destino da branch em questão no GitHub.

git push -u origin main
(comandos para adicionar o repositorio remoto para o github)

git checkout -b "nomedanovabranch": cria uma nova branch e já sai da antiga.
(sem o -b, ela só alterna entre as branches existentes)
 
git merge nomedabranchqueseramesclada: junta (mescla) uma branch na outra.
 
