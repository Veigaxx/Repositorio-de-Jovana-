# Repositorio-de-Jovana
Trago aqui alguns conhecimentos sobre o Git e Github que venho aprendendo na plataforma Dio.me

# DIO / Resumos sobre Git e GitHub

Projeto para armanezar resumos da aula de Versionamento de Códigos com  Git e GitHub,

Pela [Digital Innovation One](https://www.dio.me/) 

## 📃 Documentação

- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com/pt)

## 💻 Resumos das Aulas 

| Aula      |     Resumos|
| ------------- | ------------- |
|   Aula Git e GitHub| [Documentação Google Drive](https://docs.google.com/document/d/1LHhir0QVkTd4vFxvwHQY8B1T6rFCDHxItwXpCx1Jv-0/edit)  |

```
Configurações

Vamos ao primeiras configurações:
Começando por “git config” ou seja configurar o nosso git, para isso é necessário:

Inserir o comando git config 

git config --global --list // serve para ver a lista de configurações e se colado o  --global junto, aparece a lista de configurações globais.
git config --global  user.name=jovana //define o nome do usuário
git config --global l user.email=jovanav65@hotmail.com // define o email do usuário
init.defaultbranch=main // define o nome da branch principal 


Criando e Clonando Repositórios

mkdir repo-local // “make directory” criando um diretório e nome do diretório 
cd repo-local/ - comando mais o nome da pasta, faz com que tu entre dentro da pasta
git init // cria um repositório .git vazio ou reinicializa um existente   
cd .. // tu sai da pasta que entrou
cd .git // Entra na pasta .git
cat config // exibe o conteúdo dentro da pasta
git remote -v// mostra o origem que ele está conectado ou seja URL do github
git status // mostra o status da nossa árvore de trabalho e nossa área de preparação (index ou staging area). A área de preparação é onde vamos estar preparando nossos arquivos para salvar ou empacotar com o commit

```


- Feito por Jovana Duarte ❤️..
