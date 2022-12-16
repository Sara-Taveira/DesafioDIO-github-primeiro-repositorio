# Desafio DIO - construindo o primeio repositório 
Desafio de projeto sobre Git/Github

## Links Úteis

[Sintax básica Markdown](https://www.markdownguide.org/basic-syntax/)

#### Desenvolvendo o pensamento computacional trabalhando a sintaxe na construção dos algoritmos 

[Portugol Webstudio](https://dgadelha.github.io/Portugol-Webstudio/)


## Tópicos fundamentais para entender o funcionamento do Git 

💠 SHA1 - Significa Secure Hash Algorithm (Algoritmo de hash seguro) é um conjento de funções hash criptográficas projetas pela NSA (Agencia de Segurança Nacional dos EUA). Os dados encriptados (podendo ser qualquer tipo de arquivo) gera um conjunto de characteres identificador de 40 dígitos.

Como criptografar um arquivo SHA1:    
1° Abrir o terminal Git Bash
2° echo 'nome do arquivo'| git hash-object --stdin
OU echo -e 'nome do arquivo' | openssl sha1

💠A chave SSH serve para estabelecer uma conexão segura e incriptada entre duas máquinas, o servidor do Github com a máquina local.  Todos os repositórios que tiver na máquina quando forem enviados ao GitHub, vai ser reconhecido pela assinatura SSH da máquina local, podendo acessar sem a senha. 
* CÓDIGO- ssh keygen -t ed25519 -C 'email'   |  $ eval $(ssh-agent -s)  | ssh-add 'chave privada'


#### Estruturas de dados

💠Objetos internos do Git

BLOB-
TREE-
COMMITS-

#### Alguns comandos 

* git init = Iniciar um repositporio git
* git add = mover arquivos para o stag 
* git commit = mover arquivo para o repositório local
