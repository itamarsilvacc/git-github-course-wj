# Git e GitHub Course

Este é um repositório para aprender como o Git funciona, através do de Git e Github do Willian Justen de Vasconcellos.

## O que é Git e GitHub

Git é uma ferramenta para controle de versão. Com ele, é possível versionar o código, criando várias versões do códifo de acordo com as modificações.

GitHub é um repositório na nuvem para hospedar e compartilhar códigos versionados com o Git.

## Configurando o Git

Para configurar o Git:
git config

## Essencial do Git

### Comandos Básicos

git status
Exibe o status atual do versionamento.

### Inicializando Versionamento

Para inicializar o versionamento de um diretório, seus subdiretórios e arquivos:
git init

### Ciclo de vida dos arquivos

O Git trata o versionamento dos arquivos com base em quatro estados de ciclo de vida para cada arquivo, sendo eles:

#### Untracked

O arquivo ainda não está sendo acompanhado pelo Git.

#### Unmodified

Está sendo acompanhado, mas não foi modificado.

#### Modified

O arquivo foi modificado, mas as modificações ainda não foram adicionadas para commit.

#### Staged

O arquivo foi modificado, e as alterações foram adicionadas para commit.

### Verificando Logs

Para verificar o log dos commits com informações básicas:
git log

Para verificar o que foi modificado em um commit:
git show "hash do commit"

### Visualizar mudanças sem commit

Para verificar modificações de arquivos que ainda não foram para um commit:
git diff

### Desfazendo alterações

Para desfazer alterações que ainda não foram adicionados ao stage para commit:
git checkout "nome do arquivo"

Para desfazer alterações em arquivos que já foram adicionados ao staged:
git reset HEAD "nome do arquivo"

Para desfazer alterações que já subiram em um commit:
git reset (--soft ou --mixed ou --hard) "hash do commit anterior ao que se quer desfazer"
--soft - voltará o commit guardando as alterações e com os arquivos em Staged.
--mixed - voltará o commit guardando as alterações e com os arquivos em Modified.
--hard - voltará o commit desfazendo e apagando tudo o que foi feito.

## Repositórios Remotos

## Ramificação

## Extras
