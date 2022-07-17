# linuxcommandsubuntu
Linux commands Ubuntu

Commands básicos para mexer no terminal - Linux

“ls”: ls (list): mostra os arquivos no diretório;

cd <nome da pasta>”: cd (change directory) nome da pasta (escreva o início + tab, isso completará o nome visto q só terá um diretório c este início): entra na pasta;
“cd ~” volta na home;

“cd ~” volta na home, a msm q aparecia no “ls”;

“clear”/ctrl+L: limpa td tela;

Teclas p cima/baixo: mostra as últimas coisas escritas;

“sudo apt update”: sudo (super user do) apt (advanced package tool) update: faz update como usuário root. Atualiza a lista de repositórios do sistema. O sistema vai verificar todos repositórios e informar se podem ser atualizados;

“man apt”: man (manual): mostra manual de qualquer comando. manual do apt;

“apt -- help”: mostra comandos + utilizados;

“apt search” : pesquisa nas descrições do pacote;

“sudo apt install <nome do aplicativo>”: precisa d sudo, pq modifica o sistema;

2 tipos d upgrade. “sudo apt upgrade”: instala&atualiza pacotes d upgrade, novos pacotes e atualiza os q já existem. “sudo apt full-upgrade”: atualiza o sistema remove&instala&atualiza pacotes;

“apt-cache depends <nome do programa>”: mostra dependências do app;

“!!”: copy&paste o último comando escrito;

instalar arquivo .deb: Baixa o instalador, aperta “ls”: p ve diretórios. dps “cd downloads”, pasta Downloads. “ls”: ve o q tem lá. os apps lá, onde está o instalador. Utiliza “sudo dpkg -i <endereço do instalador>: dpkg (instalador de pacotes) -i ( install) endereço (pode só colocar o início e apertar tab, q vai completar automaticamente, visto q n só tem um diretório c o mesmo início). Isso o instalará.
