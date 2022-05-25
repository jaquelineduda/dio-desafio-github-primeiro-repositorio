# Introdução ao Git e ao Github

## Aula 1 - Introdução ao Git

Git foi criado em 2005, é um sistema de versionamento distribuído e foi criado pelo Linus Torvalds. O Git é um software de versionamento de código para ajudar a criar e monitorar diferentes versões de um código. 

- Git e Github são duas tecnologias diferentes, complementares, porém diferentes. 

<br>

## Aula 2 - Navegação via command line interface e instalação


**dir | ls** = Lista de diretórios (tudo que tem no pc, todas as pastas) 

**cd** = Navega pelas pastas

**cd ..** = Voltar um nível da navegação

**cls |clear | Ctrl + L** = Limpa o terminal

**mkdir** = Cria pastas

**echo** = Printa de volta na tela do terminal um texto escrito

**del | rm -rf** = Deleta arquivos

**rmdir** = Exclui um diretório

<br>

[Baixar o Git](https://git-scm.com/downloads)

<br>

## Aula 3 - Entendendo como Git funciona por baixo dos panos 

A sigla SHA1 significa Secure Hash Algorithm (Algoritmo de Hash seguro), é um conjunto de funções hash criptográficas projetas pela NSA (Agencia de Segurança dos EUA).

A encriptação gera conjunto de caracteres identificador de 40 dígitos. 

Blob = Contém metadados do Git, tipo de objeto, tamanho do arquivo, \0 e o conteudo do arquivo.

Tree = Armazénam blobs, metadados, tipo de objeto, tamanho do arquivo, nome do arquivo, apontando para tipos de blobs diferentes.

Commit = Objeto que vai juntar tudo, dar sentido, aponta para uma tree, parente, autor, mensagem,tamanho, timestamp.

<br>

## Aula 4 - Primeiros comandos com Git

**git init** = Iniciar repositório

**ls -a** = Serve para ver a pasta oculta (pasta gerencial do git)

No primeiro acesso pedem um username, este é o comando para configurar isso:

**git config --global user.email "meuemailaqui@gmail.com"** = e-mail

**git config --global user.name "meuNomeIgualoGithubAqui"** = nome

<br>

## Aula 5 - Ciclo de viva dos arquivos no Git

**git init** = Pasta criada, ela inicializa o conceito do git chamado repositório. 
Quando colocamos o git init estamos criando um repositório do git dentro daquela pasta.

**git add * | git add. | git add nomeArquivo** = Adiciona os arquivos

**git status** = Saber onde cada arquivo se encontrar

**git mv** = Mover

**git commit -m “msg”** = comitar o arquivo para dar significância a ele.

<br>

## Aula 6 - Introdução ao GitHub

**git config --list** = ver todas as listas de configurações 

**git config --global --unset user.name** = Para alterar alguma configuração, nesse caso seria o nome.

**git remote add origin https://github.com/jaquelineduda/livro-receitas.git** = Empurrar repositório local para repositório remoto

**git remote -v** = Lista a lista de repositórios que tem cadastrado

**git push origin master** = Enviar

<br>

## Aula 7 - Resolvendo Conflitos


**git clone https://github.com/python/cpython.git** = Clonar o repositorio de alguém.
