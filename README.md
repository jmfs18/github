
# GitHub 馃殌


## CONFIGURA脟脮ES

### Criando conta GitHub

- Primeiro vamos criar uma conta acessando [GitHub](https://github.com/) e depois clicando em criar conta.

## Instalando  Git
- Agora vamos instalar o Git clicando nesse [LINK](https://git-scm.com/download) e seguindo as instru莽玫es.

#### Configura莽玫es locais
- Depois de criar a conta e baixar o git vamos rodar os seguintes comandos para configurar nosso git local.

```
# Configurando usu谩rio e e-mail

git config --global user.name "Fulano de Tal"

git config --global user.email "your_email@example.com"
```

```
# Listando configura莽玫es
git config --list
```

## _REPOSIT脫RIOS_

#### Rodaremos esses comandos para configurar e guardar dados em um reposit贸rio local.

```
# Iniciando um reposit贸rio local
$ git init 

# Adicionando mudan莽as de tudo ou um arquivo a esse reposit贸rio
$ git add * ou git add README.md 

# Salvando essas mudan莽as em um coment谩rio ou commit
$ git commit -m "first commit"

# Criando a branch master local
$ git branch -M master
```

#### Reposit贸rio remoto 

- Agora vamos criar um reposit贸rio remoto na nossa conta do GitHub para depois conseguirmos sincronizar ambos os reposit贸rios.

#### Sincronizar e subir vers茫o do c贸digo

```
# Com esse comando e URL vamos conectar o reposit贸rio local com o remoto
git remote add origin <url_repositorio_remoto>

# Agora com os reposit贸rios conectados, vamos subir os dados locais para o remoto com o comando
git push -u origin master
```
