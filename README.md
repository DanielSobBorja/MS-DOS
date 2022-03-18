# EJERCICIO 2: MS-DOS
## Daniel Sobrino

Para esta práctica he instalado la PowerShell en linux mediante ```sudo snap install powershell --classic```.

### Actividad 1.1
Tras crear las carpetas, ejecuto el comando ```tree``` para mostrar el árbol de directorios.
```
.
├── APLI
│   ├── ACCESS
│   ├── EXCEL
│   │   ├── INFO
│   │   └── TABLAS
│   └── WORD
│       ├── NOTAS
│       └── TEXTOS
├── PROG
│   ├── BASIC
│   ├── FORTRAN
│   └── PASCAL
└── VARIOS
```

### Actividad 1.2
Me muevo a la carpeta tabla mediante ```cd APLI/EXCEL/TABLAS```.

### Actividad 1.3
Vuelvo a la carpeta raíz (de este proyecto) mediante ```cd ../../```. Para ir a la carpeta raíz de la máquina haría ```cd /```, pero no es la que nos interesa.

### Actividad 1.4
Ejecuto ```ls PROG``` para mostrar el contenido de PROG.

### Actividad 1.5
Podemos ver que se ha borrado la carpeta mediante ```rm -r PROG/PASCAL```:
![imagen](https://user-images.githubusercontent.com/91564560/159033689-c9b1f424-978b-480c-b129-ae10d0cb6f19.png)

### Actividad 1.6
Hago ```cd ../VARIOS```para ir a la carpeta VARIOS y ejecuto ```mkdir ../APLI/WORD/AGENDA```para crear la carpeta AGENDA en WORD.

