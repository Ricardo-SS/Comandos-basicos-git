# codigos-de-git-teste
Esse repositorio esta sendo usado para testar funcionalidades do git e github.

aqui não será usado para nada mais que treinamento e testes de comandos remotos.

No arquivo txt tem uma lista de comando basicos do git que podem ser muito úteis para quem está começando.

Ignorem os erros de português no arquivo pois escrevi quando estava treinando os comando e nao tive tempo de revisar.

ajuda de melhorias  e sujestões são bem vindas. 


#    COMANDOS GIT:

Iniciar o diretorio dentro da pasta selecionada no windows 11, abrir a pasta > clik com botao direito
> mostrar mais opções> Git Bash Here


#   TECLE ENTER DEPOIS DE CADA COMANDO

- Na janela de comando que abrir digite
    ---	
        git init   

(inicia o diretorio no git)

- Comando para verificar os status dos arquivos
	---
        git status

- Criando versão do codigo e adicionando arquivo
	---
        git add "NomeDoArquivoEsuaExteção"

- Adicionando varios arquivos de uma só vez
	---
        git add .

Usando o comando git add seguido de um ponto todos os arquivos da pasta atual serão adicionados ao controle de versão;

- Criando a primeira versão - Criando commits
	---
        git commit -m "commit inicial"

- Configurando email na primeira inicialização coloque o email da sua conta do github no comando abaixo e nome de usuario entre aspas duplas.

    ---
	    git config --global user.email "email.exemplo@email.com"
    ---
	    git config --global user.name "nome-de-usuarios-github"
    ---
	    git commit -m "commit inicial"	

 O nome commit inicial é uma frase que pode ser subistituido por 
 qualquer outra, serve apenas para identificar a versão.

 - Enviar arquivos para a nuvem, github.
    ---
	    git push
