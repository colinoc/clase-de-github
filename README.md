clase-de-github // 
===============

Ejemplo de GitHub para la comunidad de #mejorando.la


Una vez instalas GIT, debes configurarlo:

git config --global user.name "conlinoc"
git config --global user.email "xxxxxx@xxx.com"


Generando tu Public Key:

ssh-keygen -t rsa -C "your_email@example.com"
ssh-add ~/.ssh/id_rsa
pbcopy < ~/.ssh/id_rsa.pub  - Pegar la llave en github

Primero comandos:

git init  --> Inicializa repositorio

touch README

git add README  -->Añade archivo al repositorio

git commit -m "mi primer commit"

git push origin master

