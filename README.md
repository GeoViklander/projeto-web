# Aprendendo GIT 

### Vendo o diretorio
``` bash
ls
```

### Voltar para home 
``` bash
Cd ~
```

### Voltar uma pasta
``` bash
cd ..
```
### Achar a pasta
``` bash
cd destkop
```

### Criar pasta
mkdir  (aqui vai o nome da pasta ex: projeto-web)

### Inciar o git dentro da pasta
``` bash
git init 
```

#### Caso o projeto ja exista no github ou repositorio remoto basta dar esse comando 
git clone (url do repositorio)
git 
#### Criar um arquivo 
touch (nome do arquivo ex: index.html)


#### Tira do stage
git rm --cached <file>

#### Escrever algo no arquivo
echo "Hello World" >> (nome do arquivo ex: README.md

#### Remover o arquivo
rm (remove) (nome do arquivo ex: ola)

#### Remover pasta
rm -R (nome da pasta ex: teste)

#### Add arquivo no git
git add (nome do arquivo ex: index.html) ou git add . (o ponto serve para adc
todos os arquivos / ele coloca os arquivo no stage
git 
 ####    REGISTRAR  
git commit    -m (falar pro git que a proxima coisa é a mensagem do commit

"initial commit" <--- mensagem pro commit 
*Para enviar o commit teve que criar a config

#### Registrando e-mail no git
git config --global user.email=geovanna.viklander@hotmail.com

#### Registrando nome no git
git config --global user.name"geovavanna"

#### Verificar se existe repositorio na nuvem
git remote -v

#### Add o repositorio
git remote add origin (url do repositorio do hub ex:https://github.com/GeoViklander/projeto-web.git

#### Mandar o projeto para o repositorio 
git push origin master

#### Mudar o repositorio para outro
git remote set-url origin https://github.com/GeoViklander/Udemy.git

#### Historico 
git log

#### criar branch
git pull origin (nome-branch)

### excluir a branch
git branch -d ola

### voltar pra master
git checkout master



