# codigos-de-git-teste
Este repositório está sendo usado para testar funcionalidades do Git e GitHub. Aqui não será usado para nada mais que treinamento e testes de comandos remotos. No arquivo txt tem uma lista de comandos básicos do Git que podem ser muito úteis para quem está começando. Ignore os erros de português no arquivo, pois escrevi quando estava treinando os comandos e não tive tempo de revisar. Ajuda para melhorias e sugestões são bem-vindas.

## Dicas
git init: inicializa um novo repositório Git e começa a rastrear um diretório existente.
git clone: cria uma cópia local de um projeto que já existe remotamente.
git add: adiciona uma mudança.
git commit: salva o instantâneo no histórico do projeto e conclui o processo de rastreamento de mudanças.
git status: mostra o status das mudanças como não rastreadas, modificadas ou preparadas.

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


Aqui temos um [link](https://www.hostinger.com/tutorials/basic-git-commands) de referências com alguns comandos.
