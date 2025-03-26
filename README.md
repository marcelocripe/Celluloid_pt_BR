Repositório oficial do programa "Celluloid"

GitHub do Celluloid

https://github.com/celluloid-player/celluloid


Página eletrônica do Celluloid

https://celluloid-player.github.io/


Plataforma de tradução

https://hosted.weblate.org/projects/celluloid/celluloid/pt_BR/

https://hosted.weblate.org/projects/celluloid/glossary/pt_BR/

- - - - -

Traduções revisadas por marcelocripe:

https://github.com/marcelocripe/Celluloid_pt_BR/blob/main/celluloid-celluloid-pt_BR.po

https://github.com/marcelocripe/Celluloid_pt_BR/blob/main/io.github.celluloid_player.Celluloid.desktop


Para utilizar o arquivo "celluloid-celluloid-pt_BR.po" e o "io.github.celluloid_player.Celluloid.desktop", inicie o Emulador de Terminal na pasta onde estão os arquivos que foram baixados.

"celluloid-celluloid-pt_BR.po":

Comando para converter o arquivo editável da tradução com a extensão ".po" para ".mo".

$ msgfmt celluloid-celluloid-pt_BR.po -o celluloid.mo

Comando para renomear o arquivo antigo da tradução com a extensão ".mo" que está na pasta do idioma "pt_BR".

$ sudo mv /usr/share/locale/pt_BR/LC_MESSAGES/celluloid.mo /usr/share/locale/pt_BR/LC_MESSAGES/celluloid_antigo.mo

Comando para copiar o arquivo da tradução com a extensão ".mo" para a pasta do idioma "pt_BR".

$ sudo cp celluloid.mo /usr/share/locale/pt_BR/LC_MESSAGES


"io.github.celluloid_player.Celluloid.desktop":

Comando para copiar o arquivo com a extensão ".desktop" para a pasta /usr/share/applications.

$ sudo cp io.github.celluloid_player.Celluloid.desktop /usr/share/applications

Comando para escrever globalmente todas as entradas dos menus do antiX:

$ sudo desktop-menu --write-out-global
