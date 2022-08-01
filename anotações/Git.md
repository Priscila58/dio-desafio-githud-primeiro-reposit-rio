# Git, conhecendo os primeiros passos

**Links**: https://git-scm.com/

- **Configure seu Usuário**

O controle de versão controla quem faz as alterações num projeto. Então você deve configurar seu usuário

git config --global user.name "Nome de usuario "
git config --global user.email "Seuemail@gmail.com"



- **Crie um Repositório local**

Antes de criar o repositório você deve criar um pasta para ele, obviamente.

Para criar uma nova pasta no windows / Linux executamos mkdir nome-da-pasta.

Você entra nela, ou melhor, vai até ela cd nome-da-pasta.

Agora é só criar o repositório.



- **Git init**

Para criar um novo repositório, você vai usar o comando Git init. 

Git init é um comando único que você usa durante a configuração inicial de um novo repositório. A execução desse comando cria um novo subdiretório .



- **Git commit**

Por padrão, git commit abre o editor de texto configurado no local e solicita que uma mensagem de commit seja escrita. Transmitir a opção -m vai pular a solicitação do editor de texto em favor de uma mensagem integrada.

git commit -m "commit message" 



- **Suba seus commit**

Com isso você configurou o remote origin para o GitHub  Você já pode subir seus commits para lá usando git push, mas na primeira vez o comando deve ser executado para configurar a branch master para o GitHub. 

git remote add origin https://github.com/Nome/Tutorial.git

git push -u origin master





