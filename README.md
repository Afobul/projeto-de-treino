# notas de linux
BIOS

1. /Swap
/
/Home
2. /Boot / uefi
         \ Boot
         
ls / - lista a totalidade do disco
sudo apt update - atualiza a lista de pacotes
sudo apt upgrade - dá update a todo o software instalado
caminho relativo- Um caminho relativo descreve a localização de um arquivo ou diretório em relação ao diretório atual (também chamado de diretório de trabalho).É desde o sítio onde estou até onde eu quero ir
caminho absoluto- Um caminho absoluto descreve a localização de um arquivo ou diretório a partir da raiz do sistema de arquivos.         
rm -r teste/ - remove essa pasta
Uma variável de ambiente é 
A diferença principal está na abordagem: pwd é um comando que mostra diretamente o diretório atual, enquanto echo $PWD exibe o valor da variável de ambiente $PWD, que armazena o mesmo caminho do diretório de trabalho atual.


bin=codigos basicos de linux
boot=ficheiros iniciais para o arranque
dev=dispositivos do computador
etc=ficheiros de configuração
/home=pasta de cada utilizador
opt=	
root=pasta q é propriedade do linux
var=

comando para criar uma pasta dentro de outras= 	mkdir ./Documents/xpto/xpto2

r(read)=4
w(write)=2
x(execute)=1


lista os utilizadores q tenho na maquina linux - cat /etc/passwd
onde é q esta o comando make - whereis make
a forma mais rapida de saber quemé q esta logado no computador e o q é q esta a fzr - w
ver todo o hardware do computador - lshw
ver especificamente as caracteristicas da cpu - lscpu
qual é a arqutatura do meu cpmputador - uname -m ou arch
comando q faz uma comparação - diff
exibirá o conteúdo do arquivo "exemplo.txt" uma página por vez, permitindo que você role para frente e para trás para ler o conteúdo - more
mostra as ultimas 10 linhas de um ficheiro - tail
mostra as primeiras 10 linhas de um ficheiro - head
é utilizado para visualizar o conteúdo de arquivos de texto no terminal de forma paginada - less
é utilizado para contar o número de linhas, palavras e caracteres em um arquivo de texto - wc
mostra a variavel de ambiente - echo $USER
da nos a informação toda da maquina - uname -a
tempo de uma determinada aplicação q esta executada - time


-rw-r--r-- 1 usuario grupo 4096 out 1 10:30 arquivo.txt :o primeiro "-"significa que é um ficheiro, "d" significa que é um diretorio e "l" significa um link




echo "Olá" >> file.txt


date +"%X %r"=ve o tempo


As 4 partições do Linux:root(guarda os aplicativos), home(guarda os ficheiros pessoais), swap e a boot(precisa de 500 mb).




Shell script:

um ficheiro q tem um conjunto de comandos com logica para fzr um conjunto de tarefas



Novo Módulo(Linux - Kernel e componentes do sistema):

Kernel-é o nucleo do sistema(é o q fica entre o hardware e o software)
O ambiente grafico do ubuntu é o "gnome"
O flavour de linux mais utilizado:Android 

Programas q usam como base uma kernel  e q depois em cima dessas serve de interface para o utilizador


TCP-transporte controlado por protocolos
gateway-é uma porta de saída.Manda pedidos para redes externas à nossa(é um equipamento híbrido)
