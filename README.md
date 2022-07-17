# Linux Commands Ubuntu

<h1>Linux commands Ubuntu</h1> 

<h3>Commands básicos para mexer no terminal - Linux - UBUNTU 3</h3> 

“ls”: ls (list): mostra os arquivos no diretório;

cd <nome da pasta>”: cd (change directory) nome da pasta (escreva o início**+**tab, isso completará o nome visto q só terá um diretório c este início): entra na pasta;
“cd ~” volta na home;

“cd ~” volta na home, a msm q aparecia no “ls”;

“clear”/ctrl**+**L: limpa td tela;

Teclas p cima/baixo: mostra as últimas coisas escritas;

“sudo apt update”: sudo (super user do) apt (advanced package tool) update: faz update como usuário root. Atualiza a lista de repositórios do sistema. O sistema vai verificar todos repositórios e informar se podem ser atualizados;

<h6>APT: INSTALADOR DO UBUNTU (PACMAN É DO ARCHLINUX - e.g.: Manjaro, Garuda) 6</h6>  

“man apt”: man (manual): mostra manual de qualquer comando. manual do apt;

“apt -- help”: mostra comandos + utilizados;

“apt search” : pesquisa nas descrições do pacote;

“sudo apt install <nome do aplicativo>”: precisa dO sudo, porque modifica o sistema;

2 tipos de upgrade. “sudo apt upgrade”: instala&atualiza pacotes d upgrade, novos pacotes e atualiza os q já existem. “sudo apt full-upgrade”: atualiza o sistema remove&instala&atualiza pacotes;

“apt-cache depends <nome do programa>”: mostra dependências do app;

“!!”: copy&paste o último comando escrito;

instalar arquivo .**deb**: Baixa o instalador, aperta “**ls**”: p ve diretórios;
  depois “cd downloads”, para entrar na pasta Downloads;
  agora digita “**ls**”: ver o que tem lá, os apps lá, onde está o instalador.
  Utilize “sudo dpkg -i <**endereço do instalador**>: dpkg (instalador de pacotes) -i ( install) endereço (pode só colocar o início e apertar tab, que vai completar automaticamente, visto que não só tem um diretório com o mesmo início). 
  Isso o instalará.
