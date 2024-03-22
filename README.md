# Comandos Básicos GIT
![Git](assets/Git-Logo-2Color.png)

## 1. Clonando o projeto

### 1.1. Criar o repositório, no nosso caso, no  GitHub.

### 1.2. Ir para a pasta na máquina e abrir o terminal e executar o comando abaixo.

``shel
git clone [url_github]
```

acessar a página do projeto clonado

```shel 
cd [nome do repositorio]
```

## 2. Subindo o código do projeto

### 2.1. Status

```shell
git status
```

### 2.2. Adicionar todos os arquivos

```shell 
git add . 
```

### 2.3. Preparar todos os arquivos

```shell 
git commit -m "[mensagem]"
```
### 2.4. Enviar as alterações
```shell
git push
```
## 3. Configurando o usuário global no SO
**Fonte:** [Configuração inicial do Git](https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Configura%C3%A7%C3%A3o-Inicial-do-Git)

```shell
git config --global user.name "[nome_usuario_github]"
git config --global user.email "[email_usuario_github]"
```