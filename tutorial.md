# git init
Para iniciar o repositório

# git add
Manda os arquivos para a área de staging

# git commit 
Vai capturar o estado do projeto naquele ponto
- exemplo: 
git commit -m "nome" 

# Alterando branch master para main
(isso é uma boa prática atualmente recomendada)
- exemplo: 
git branch -M "main"

# git remote
Vai passar o commit do repositório local para o github
- exemplo:
git remote add origin <link do repositório>

# git push
De fato vai empurrar os arquivos no repositório na plataforma.
git push -u origin main
- Obs: quando for alterar ou adicionar novos arquivos não precisa do "-u".

# criando uma branch
Além de criar, ele já entra nela
- exemplo:
git checkout -b "nome-da-branch"

Lembrando que como o nome da branch é outro, devemos usar no git push
- exemplo:
git push origin "nome-da-branch"

# alternado entre branches
Para voltar para a branch main
git checkout main

Para voltar para branch criada 
git chekcout "nome-da-branch"

# git merge
1° Precisa ir para a branch main
git checkout main

2° fazer o merge
git merge "nome-da-branch"

3° jogar no github
git push origin main

# git clone
git clone htpps://linkdo-repositório-da-pessoa.com.br

# git pull 
git pull
vai atualizar o reposítorio feitas no github para o repositório local
