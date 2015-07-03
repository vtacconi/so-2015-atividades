======================
Glossário de comandos
======================

:Disciplina: Fundamentos de Sistemas Operacionais
:Professor: Jurandy Soares
:Nome: Vítor Ferraz Silva Tacconi
:Matrícula: 20121144010648
:Data: 01/07/2015

cat
  Abre um arquivo.
  O comando cat, do sistema operacional, Unix é usado para unir, criar e exibir arquivos.
  O nome remete a "concatenate" ("concatenar" em inglês). Em geral é usado desta maneira para exibir o conteúdo de um arquivo na saída padrão:1
  Exemplo: $ cat arquivo
  
   $ cat arquivo2 >> arquivo1

cd
  Entra em um diretorio
  Seu nome é um acrônimo da expressão inglesa change directory ("mudar diretório") e sua finalidade é, como sugere seu nome, mudar o diretório atual de trabalho (isto é, o diretório em que se está) para uma outra especificada.
  Exemplo
  me@host:~$ cd games
  
  me@host:~/games$ cd ../fotos


cowsay
  Utiliza a aplicação do cowsay, para enviar mensagens entre computadores
  Exemplo:
  cowsay Muito interessante | write to all


echo
  
  imprimi algo na tela
  Exemplo:
  $ echo "Este é um teste"


env
  Descrição do comando
  Mostra variaveis do sistema
  Exemplo: env


exit
  Terminar a sessão, ou seja, a shell (mais ajuda digitando man sh ou man csh)
  Descrição do comando
  Exemplo: exit


help
  Mostra os principais comando que podem ser usados no cyngwin
  Descrição do comando
  Exemplo: help


HISTTIMEFORMAT="%d/%m/%y
  Comando  para que seja possível incluir informação sobre a data e hora
  echo 'export HISTTIMEFORMAT="%d/%m/%y %T "' >> ~/.bashrc
  source ~/.bashrc
  Descrição do comando


hostname
  Comando que exibi o nome da maquina.
  Exemplo: hostname


ifconfig
  O comando ifconfig é utilizado para atribuir um endereço a uma interface de rede ou configurar parâmetros de interface de rede. 
  Você verá os alias/apelidos da interface eth0 e os seus endereços IPs. 
  Descrição do comando


last
  O comando last exibe a lista dos usuários que autenticaram no sistema.
  Descrição do comando
  Exemplo: Last


lastb
  Descrição do comando


ls
  Lista os Diretorios.
  Lista todos os arquivos do diretório.
  Exemplo: ls [opções] [caminho/arquivo] [caminho1/arquivo1] ...


mkdir
  Criar diretorio/pasta. EX: mkdir fusca.
  Cria um diretório.
  


nome="fulano
Adiciona o valor "fulano" a variavel nome
  Descrição do comando


passswd
  Mudar a password do nosso utilizador (usuário logado)
  Descrição do comando
  Exemplo: passwd {NOME-DO-USUÁRIO}


pwd
  
  Mostra o diretorio que você se encontra.
  O diretório de trabalho atual.
  Exemplo: pwd


set
  Descrição do comando
  Define variáveis da sessão, ou seja, da shell, na C shell, na bash ou na ksh
  Exemplo:
  Set //vai mostrar todas as variaveis
  SET P //vai mostrar apenas as variaveis que começam com "p"


tree
  Descrição do comando
  Tree é um comando do MS-DOS que exibe uma árvore de pastas e arquivos.
  Exemplo: tree
  


tty
  TTY é simplesmente um terminal ao qual você está conectado.
   tty é um comando Unix que imprime na saída padrão o nome do arquivo conectado à entrada padrão
  Descrição do comando
  	Exemplo:
CTRL + ALT + F#

$ tty
/dev/pts/0


vim
  Descrição do comando
  Editor de texto full-screen melhorado (vi improved)
  Exemplo: xxx vim


wait
  Wait é um comando que paraliza a execução de proocessos que estão sendo executados em segundo plano. 
  Exemplo: 
  wait 2017 //para o processo de numero 2017

wall
Envia uma mensagem a todos os usuários do sistema. Este comando faz a leitura de um arquivo ou entrada padrão e escreve o resultado em todos os terminais onde existem usuários conectados. Somente o usuário root pode utilizar este comando.
Ex:
wall [arquivo]

Exemplos: wall /tmp/mensagem.txt, echo Teste de mensagem enviada a todos os usuários conectados ao sistema|wall.
 
 
which
  which - busca por executáveis nos PATHs exportados.
  Exemplo:
  
   which httpd
   /usr/sbin/httpd 


while
O comando “while” com em outras linguagens de software executa um bloco de código enquanto sua condição for verdadeira.
  
  Exemplo:
  
  while <condição>;do
    bloco de código/ comando...
done


who
  Descrição do comando
  Mostra-nos quem está logado no sistema
  mostra quem está usando o sistema.
  Exemplo: who


whoami
  Descrição do comando
  Diz-nos quem é o dono da shell
  EX: whoami


write
  Escrever para outros utilizadores que estejam logados no momento
    
      Exemplo:
      write to all

