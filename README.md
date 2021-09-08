# Git

### Instalação

Fazer download e instalação do git, através do link: [https://git-scm.com/download/win](https://git-scm.com/download/win)

### Setup
Configurar informações do usuário que aparecerão no histórico dos commits.

*Configurar nome:*
```bash
git config --global user.name “[firstname lastname]”
```
*Configurar email:*
```bash
git config --global user.email “[valid-email]”
```
### Clonar repositório
Antes de clonar o repositório, é necessário navegar até a pasta desejada, clicar com o botão direito do mouse e selecionar a opção `Git Bash Here`

*Comando para clonar o repositório:*
```bash
git clone URL_DO_REPOSITORIO_AQUI
```

*Abrir a pasta do projeto:*
```bash
cd nome_do_projeto
```

*Abrir a pasta do projeto:*
```bash
cd nome_do_projeto
```
*Atualizar a máquina local com o projeto remoto:*
```bash
git pull
```

### Operações de branchs
*Trocar de branch:*
```bash
git checkout NOME_DA_BRANCH
git pull
```
PS: Após trocar de branch é necessário fazer git pull para garantir que todas as alterações remotas feitas na branch sejam atualizadas na máquina local.

*Criar nova branch:*
```bash
git checkout -b NOME_DA_BRANCH
```
### Operações de commit
Os arquivos modificados devem ser adicionados em um `Pacote`, este pacote receberá um nome através do `commit` e só estará disponível remotamente no momento que for enviado através do `push`

*Verificar arquivos modificados*:
```bash
git status
```

*Adicionar todos os arquivos modificados no pacote*:
```bash
git add .
```
*Adicionar  apenas um arquivo entre os modificados:*
```bash
git add NOME_DO_ARQUIVO
```
*Remover arquivo do pacote:*
```bash
git reset NOME_DO_ARQUIVO
```
*Fazer commit  (dar um nome ao pacote de arquivos modificados, que irá aparecer no histórico):*
```bash
git commit -m "MENSAGEM_DESEJADA"
```
*Fazer push (enviar o pacote de arquivos modificados para o projeto remoto):*
```bash
git push
```
