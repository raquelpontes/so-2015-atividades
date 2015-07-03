======================
Glossário de comandos
======================

:Disciplina: Fundamentos de Sistemas Operacionais
:Professor: Jurandy Soares
:Nome: Raquel Pontes Martins
:Matrícula: 20121144010443
:Data: 01/07/2015

cat
  Esse comando serve para exibir um arquivo, criar um arquivo ou concatenar arquivos.
    cat [opções] arquivo ou cat arquivo = imprime na tela o conteúdo do arquivo
    cat > arquivo =  cria um arquivo recebendo o texto digitado logo após o comando. Para sair do arquivo criado utilize Ctrl + D.
    cat arquivo1 >> arquivo2 = esse comando faz com que o arquivo2 receba o conteúdo do arquivo1. Obs.: as informações contidas no arquivo2 são sobrescritas pelas do arquivo1. 

cd
  Muda de diretório.
    cd = volta pro diretório atual
    cd /caminho = vai para o caminho
    cd /diretorio

cowsay
  Programa de troca de mensagens a partir de animações em ASCII.
    cowsay -l = ver todas as variações de animações.
	  cowsay “mensagem” = manda a mensagem para o seu próprio terminal em configuração default, ou seja, uma vaca.
	  cowsay –f kiss “mensagem” = manda a mensagem para o seu próprio terminal em configuração kiss, ou seja, de um beijo.   Atenção: o kiss pode ser substituído pelas outras variações.
  	cowsay –f kiss “mensagem” | write colega = manda a mensagem para o terminal do seu colega em configuração kiss, ou seja, de um beijo. Atenção: o kiss pode ser substituído pelas outras variações.

echo
  Mostra os argumentos na saída.
    echo /* = exibe todos os nomes de arquivos de um diretório em ordem alfabética.
    echo "$VARIAVEL" = verifica o conteúdo da variável de ambiente VARIAVEL. 

env
  Lista as variáveis de ambiente. 
  
  env

exit
  Sair do local atual.
    exit ou Ctrl + D

help
  Exibe os comandos e as informações.
    comando –help = apresenta o arquivo ajuda do comando que foi informado.

HISTTIMEFORMAT="%d/%m/%y"
  Ativa marca de tempo para o history.

hostname
  Nome da máquina utilizada no momento.

ifconfig
  Apresenta configurações da máquina, informando o IP, entre outros.

last
  Exibe a lista de usuários que autenticaram no sistema.

lastb
  Exibe informações sobre as tentativas mal sucedidas de se logar ao sistema.

ls
  Lista os arquivos e diretórios das pastas.
    ls, ls –F, ls –F1 = lista e insere quebra de linha

mkdir
  Criação de diretórios. 
    mkdir “nome da pasta” = cria pasta com o nome do diretório informado.

nome="fulano
  Criação de variável de ambiente.

passswd
  Alterar senha do usuário.

pwd
  Apresenta o diretório atual do usuário. Present Working Directory.

set
  Controla o comportamento no shell, listando todas as variáveis de ambiente. 
    set
    HOSTNAME=switch
    HOSTTYPE=i486

tree
  Exibe todos os diretórios e arquivos em formato de árvore.

tty
  Imprimir o nome do terminal conectado à entrada padrão de arquivo.

vim
  Esse comando serve para exibir um arquivo, inserir conteúdo, entre outros.
    :a = inserir e editar valores
    ESC:x = salvar e fechar
    ESC:q = fechar

wait
  Esperar os processos em mudança de estado.

wall
  Escrever mensagens para os usuários.

which
  Localizar comando.

while
  Laço de repetição.

who
  Mostra o usuário logado agora.

whoami
  Apresenta id do usuário efetivo.

write
  Envia mensagens para outro usuário.
    write raquel
