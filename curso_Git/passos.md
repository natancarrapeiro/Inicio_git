primerio abaixa o git
e entra na pasta do arquivo usando o atalho ou no terminal usando cd /
comando git init//inicia

Antes de qualquer interação com o git, você precisa informar quem é você para que ele armazene corretamente os dados do autor de cada uma das alterações no código.

git config --local user.name "Seu nome aqui"
git config --local user.email "seu@email.aqui"

comando git status// visualia os arquivos
comando git add arquivo//inicia o monitoramento do arquivo desejado para comiti
comando git add . //todos os aquivos da pasta
comando git rm --cached aquivo //para retirar do monitoramneto
comando git commiti -m "mensagem do commit"//mensagen descritiva sobre o commiti

sempre que ouver alterção tem que commitar de volta e escrever uma msg


HEAD: Estado atual do nosso código, ou seja, onde o Git os colocou

Working tree: Local onde os arquivos realmente estão sendo armazenados e editados

index: Local onde o Git armazena o que será commitado, ou seja, o local entre a working tree e o repositório Git em si.