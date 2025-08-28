# Instruções sobre como utilizar o Git e GitHub

> ### Comandos Iniciais

- **git init** - Serve para inicializar um repositório vazio na **nossa maquina** no gitbash.    (OBS: esse comando só precisa ser feito uma única vez)
- **git add "nome do arquivo"** - Serve para mandar um arquivo para área de standing para ser commitado.
- **git add .** - Serve pra mandar todos os arquivos de uma vez para área de standing.
- **git status** - Serve para verificar os arquivos que estão em standing.

> ### Como alterar a branch de master para main?

- **git branch -m "main"**

> ### Como fazer a conexão entre o repositório local e o do github

- **git remote add origin "link do repositório"**

> ### Como commitar?

- **git commit -m "nome do commit"** - Serve para fazer o commit no gitbash.

---

> ### Após a conexão, como empurrar os commits que estão no repositório local para o github?

- **git push -u origin main**   (OBS: só precisa ser feito uma única vez)
- **git push origin main** - Serve para mandar as modificações do repositório local pro github.

---

> ### Informações adicionais

- **Quando for criar uma pasta para iniciar um projeto, para criar um repositório local uso o comando já citado acima, após usar todos os comandos iniciais, ai sim crie um repositório no github com o mesmo nome da pasta do seu projeto.**
- **Como funciona uma branch? (ramificação do nosso projeto)** - Normalmente utiliza-se as branchs para adicionar uma nova página no projeto.
- **Como criar uma nova branch** - Utilizando o comando **git checkout -b "nome da branch"**
- **Alterando entre branchs** - git checkout "nome da branch**
- **Como pegar a branch criada e juntar com a principal (main/master)** - Primeiramente mude para a branch principal, em seguida utilize o comando **git merge "nome da branch criada"**, em seguida **git push origin main**
