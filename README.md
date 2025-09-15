# ❗ ESSE REPOSITÓRIO FOI CRIADO DE FORMA PARA AUXILIAR INICIANTES NO GITHUB ❗

## Instruções sobre como utilizar o Git e GitHub

> ### Comandos Iniciais

**Quando for criar uma pasta para iniciar um projeto, crie um repositório local utilizando o primeiro comando abaixo, após usar todos os comandos iniciais, ai sim crie um repositório no github com o mesmo nome da pasta do seu projeto.**

- **git init** - Serve para inicializar um repositório vazio na **nossa maquina** no gitbash.    (OBS: esse comando só precisa ser feito uma única vez)
- **git add .** - Serve pra mandar todos os arquivos de uma vez para o backstage (área de espera) para ser commitado.
- **git add "nome do arquivo"** - Serve para mandar um arquivo específico para o backstage.
- **git status** - Serve para verificar os arquivos que estão em backstage.

> ### Como alterar a branch de master para main?

- **git branch -m "main"**

> ### Como commitar?

- **git commit -m "nome do commit"** - Serve para fazer o commit no gitbash.

---

> ### Como fazer a conexão entre o repositório local e o do github

- **git remote add origin "link do repositório"**

> ### Após a conexão, como empurrar os commits que estão no repositório local para o github?

- **git push -u origin main**   (OBS: só precisa ser feito uma única vez após a criação do repositório local e no github)
- **git push origin main** - Serve para mandar as modificações do repositório local pro github.

---

> ### Informações adicionais

- **Como funciona uma branch? (ramificação do nosso projeto)** - Normalmente utiliza-se as branchs para adicionar uma nova página no projeto.
- **Como criar uma nova branch** - Utilizando o comando **git checkout -b "nome da branch"**
- **Alternando entre branchs** - git checkout "nome da branch"
- **Como pegar a branch criada e juntar com a principal (main/master)** - Primeiramente mude para a branch principal utilizando o comando acima, em seguida utilize o comando **git merge "nome da branch criada"**, após isso **git push origin "main/master"** para empurrar os commits.
- **git clone "link do repositório do github** - Clonar um repositório do github para sua maquina local.
- **git pull** - Caso tenham feito alguma alteração no repositório, e você quiser puxar todas as atualizações feitas, utiliza-se esse comando.
