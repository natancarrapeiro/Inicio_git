primerio abaixa o git
e entra na pasta do arquivo usando o atalho ou no terminal usando cd /
comando git init//inicia

Antes de qualquer interação com o git, você precisa informar quem é você para que ele armazene corretamente os dados do autor de cada uma das alterações no código.

git config --local user.name "Seu nome aqui"
git config --local user.email "seu@email.aqui"
git config --local ...//somente nesse commit essas informaçoes serão usadas
fit config --global ...//sera em todos commit
git config user //mostra o nome do commiti atual
git config email//mostra o email do commit atual

 git status// visualia os arquivos
 git add arquivo//inicia o monitoramento do arquivo desejado para comiti
 git add . //todos os aquivos da pasta
 git rm --cached aquivo //para retirar do monitoramneto
 git commiti -m "mensagem do commit"//mensagen descritiva sobre o commiti
 sempre que ouver alterção tem que commitar de volta e escrever uma msg

 git log //mostra o historico dos commiti
 git log --oneline //historico resumido
 git log -p //mostra as aterações feitas nos commit
 site " https://devhints.io/git-log "

Estado onde o git ignora um arquivo ou pasta;
°criar um arquino no seu editor ou IDE com o nome .gitignore
°colocar os arquivos e pastas que vc quer ignorar dentro desse arquivo 
com isso o git não vai ler e nem visualizar esses aquivos 


Criando um servidor para colocar as alteraçoes;
° mkdir servidor//criando a pasta
°cd servidor//entre na pasta
° git init --bare//cria um repositorio so vai servir para grardar as alteraçoes não tera como alterar
sera mostrado o caminhon para esse repositorio
°volte a pasta do projeto


crie um repositorio remoto no gitHub
git remote add nome url/ssh



HEAD: Estado atual do nosso código, ou seja, onde o Git os colocou

Working tree: Local onde os arquivos realmente estão sendo armazenados e editados

index: Local onde o Git armazena o que será commitado, ou seja, o local entre a working tree e o repositório Git em si.