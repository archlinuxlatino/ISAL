# ISAL
##
<h1 align="center">INSTALACION POR SCRIPTS DE ARCHLINUX VERSION 2020-05-23</h1>
    
<h4 align="center">La instalación y configuración de archlinux nunca ha sido tan fácil!</h4>

## PREREQUISITOS

    *Conexion a Internet
    *Usuario 'root'

## OBTENIENDO ARCHIVOS CON GIT
## SEGUIR ESTOS PASOS:
    *Aumentar la partición del cowspace: mount -o remount,size=2G /run/archiso/cowspace
    *Obtenga una lista de paquetes e instálelos git: pacman -Sy git
    *Obtener el Scripts: git clone git://github.com/archlinuxlatino/ISAL
    *Si al momento de ejecutar el archivo sale error de permisos puedes ejecutar el siguiente comando 
         chmod 777 tu_archivo 

## COMO USAR
    1 - installbase [Sistema Base]: cd ISAL ; ./installbase
    Contiene:
        Seleccion de Teclado.
        Editor Preferido.
        Configuracion de Lista de Servidores
        Particionado de Disco
        Instalacion Sistema Base.
        Generacion de FSTAB
        Configuracion de Hostname
        Configuracion de Zona Horaria
        Configuracion de Reloj
        Configuracion de Idioma
        Generacion de archivo initcpio
        Instalacion de Gestor de Arranque
    
    2 - install-all [Xorg, Escritorio, ETC.]: cd ISAL ; ./install-all
