# GIT

## Configuración global
- git --version
- git config --global user.name "Alex"
- git config --global user.email "alexrobertomata@hotmail.com"
- git config --global core.editor "code --wait"
- git config --global -e (Abrir .gitconfig)
- git config --global color.ui "auto"

## Comandos básicos
- git init
- git clone <url de repositorio>
- **git status -s** (solo muestra archivos)
- git add <archivo>
- git add .
- git add -u
- git commit -m "Texto que identifique por que se hizo el commit"
- git push -u origin master
- git log --oneline --stat
- git log --oneline --graph
- git diff --staged
- git reset HEAD --soft (regresa un commit sin eliminar cambios)
- git reset HEAD --hard (regresa un commit eliminando cambios)
- git reset HEAD <archivo>

# Script
- PWD Imprime el directorio actual
- LS (opciones) (directorio) Muestra los contenidos del directorio seleccionado.
- CD (directorio) Cambia el directorio actual.
- MKDIR (directorio) Crea un directorio en la ubicación seleccionada.
- CP (origen) (destino) Copia el archivo o directorio origen al nombre de archivo o directorio de destino.
- MV (origen) (destino) Mueve (o también renombra) el archivo o directorio origen al archivo o
directorio de destino.
- RM (archivo) Elimina el archivo seleccionado.
- RMDIR (directorio) Elimina el directorio seleccionado.
- CHMOD (Opciones) (archivo o directorio) Cambia los permisos del archivo o directorio seleccionado.
- CHOWN (Nombre de usuario) (archivo o directorio) Cambia el usuario que es dueño del archivo o
directorio seleccionado
- CHGRP (Nombre de grupo) (archivo o directorio) Cambia el grupo actual que es dueño el archivo o
directorio seleccionado.
- MAN (nombre de comando) Muestra la ayuda del comando seleccionado
- INFO (nombre de comando) Muestra información detallada del comando seleccionado.
- CAT (nombre de archivo) Muestra el contenido del archivo de texto seleccionado.
- CLEAR Limpia la pantalla de todo texto existente y deja únicamente la linea de comandos actual.
- EXIT Cierra la sesión de bash o la ventana donde se está ejecutando.

# MarkDown
- ** Negrita **
- *Cursiva *
- -Viñeta

### https://support.zendesk.com/hc/es/articles/4408846544922-Uso-de-Markdown-para-el-formato-de-texto#:~:text=Markdown%20es%20un%20lenguaje%20de,desde%20la%20interfaz%20del%20usuario)
