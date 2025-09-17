# SergamerOS👍
Um rice linux para todos os fãs do u/sergamer2 vulgo joinha-man👍

Leia as Instruções para instalar corretamente!👍

# Screenshots:
![image](https://github.com/JayRod6699/SergamerOS/blob/main/Screenshot%20from%202025-09-16%2019-14-36.png)

![image](https://github.com/JayRod6699/SergamerOS/blob/main/Screenshot%20from%202025-09-16%2019-03-39.png)

![image](https://github.com/JayRod6699/SergamerOS/blob/main/Screenshot%20from%202025-09-16%2019-12-46.png)

![image](https://github.com/JayRod6699/SergamerOS/blob/main/Screenshot%20from%202025-09-16%2018-55-45.png)

# Instruções:
Instale todos os seguintes pacotes de antemão:
>sway ou swayfx (AUR)
>swaybg
>foot
>waybar
>wofi
>otf-font-awesome
>noto-fonts-emoji
>fastfetch

Extraia todas as pastas do arquivo config_dotfiles.tar.gz para a pasta /.config localizada em /home/<user>/

OBS: Essa pasta estará oculta por ter (.) no começo, ative a função de mostrar arquivos ocultos no seu gerenciador de arquivos.

Extraia a pasta da configuração do Sway para /.config também. Caso você esteja usando SwayFX, adicionei uma pasta com a configuração específica chamada /SwayFX, renomeie esta pasta para apenas /sway

Para que o Papel de Parede funcione, crie uma pasta chamada /Wallpapers na pasta /Pictures e cole o wallpaper desejado lá, renomeie o arquivo do wallpaper para: default.jpeg. Agora abra o arquivo config do sway localizado em /home/<user>/.config/sway/ com algum editor de texto e procure pela linha com: 
output * bg /home/sergamer/Pictures/Wallpapers/default.jpeg fill

Troque o sergamer pelo seu usuário, por exemplo:

output * bg /home/Mateus/Pictures/Wallpapers/default.jpeg fill

Feito isso, o wallpaper vai aparecer assim que você reiniciar o sway

*EXTRAS [custom bash, cat files e programas de terminal]:
Para exibir aquelas incríveis artes ASCII no terminal, extraia os arquivos do cat_files.tar.gz para /home/<user>/ Para exibilos no terminal utilize o comando cat + o nome do arquivo, por exemplo:
$ cat os
$ cat .haruhi.txt
$ cat .sergamer2.txt

Etc, caso você tenha substituído o arquivo .bashrc, você notara seu bash levemente customizado e uma saudação toda vez que abrir um terminal 👍

Programas extras puramente por estética:
>cavasik (AUR)
>cmatrix-git (AUR)
>tty-clock (AUR)
>htop

AGRADECIMENTOS:

u/Olhos_de_porcelana e u/Far_Departure_1580
pelos wallpapers
