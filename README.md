# SISTEMAS EJERCICIO 2: MS-DOS
## Daniel Sobrino

Para esta práctica he instalado la PowerShell en linux mediante ```sudo snap install powershell --classic```.

## EJERCICIO 1
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
Hago ```cd ../VARIOS``` para ir a la carpeta VARIOS y ejecuto ```mkdir ../APLI/WORD/PRACT```para crear la carpeta PRACT en WORD.

![imagen](https://user-images.githubusercontent.com/91564560/159035886-9c87b9eb-e44d-4b84-98eb-b73601e0c195.png)

### Actividad 1.7
Hago ```../APLI/WORD/PRACT/``` desde VARIOS para situarme en la nueva carpeta. Entonces ejecuto ```ls ../../EXCEL/```.

### Actividad 1.8
Me muevo a TABLAS con ```cd ../../EXCEL/TABLAS/```. Ejecuto ```ls ../../../```.

![imagen](https://user-images.githubusercontent.com/91564560/159036839-09e67fef-5e00-4791-ab1e-cf31b59e9ebc.png)

### Actividad 1.9
Me sitúo en APLI y creo la carpeta AGENDA en VARIOS.

![imagen](https://user-images.githubusercontent.com/91564560/159037469-4370fd1c-ef5d-4d59-8b84-60e851baf300.png)

### Actividad 1.10
Elimino la carpeta EXCEL con ```rm -r EXCEL/```.

### Actividad 1.11
Me vuelvo a la raíz y creo la carpeta NUEVO.

![imagen](https://user-images.githubusercontent.com/91564560/159038165-d4ccb1f4-7ee5-40c3-92a2-c24a5e0c37ca.png)

### Actividad 1.12
Desde PRACT muestro el contenido de WORD.

## EJERCICIO 2
### Actividad 2.1
Creo el fichero EJER.TXT con el contenido indicado en TEXTOS. (Confía en que he metido el texto)

![imagen](https://user-images.githubusercontent.com/91564560/159546376-0040c588-e7bf-4151-bf1a-370a840fb611.png)

### Actividad 2.2
Copio el archivo en la carpeta agendas con ```cp ./APLI/WORD/TEXTOS/EJER.TXT ./APLI/WORD/AGENDA/```.

![imagen](https://user-images.githubusercontent.com/91564560/159546845-2b45c729-0d38-4847-8d97-e948f10deefe.png)

### Actividad 2.3
Borro el archivo que ha quedado repetido en textos.

![imagen](https://user-images.githubusercontent.com/91564560/159547021-36cda103-b439-4da0-ab6b-5757740ce532.png)

### Actividad 2.4
Añado otra línea al EJER.TXT.

![imagen](https://user-images.githubusercontent.com/91564560/159547532-330b7224-ff27-45e7-95bf-e8c4146799b4.png)

### Actividad 2.5
Copio el archivo en la carpeta BASIC.

![imagen](https://user-images.githubusercontent.com/91564560/159547824-96929de3-499f-4e1a-8599-974197776148.png)

### Actividad 2.6
Cambio el nombre del archivo que se encuentra en AGENDA por FICHERO.TXT.

![imagen](https://user-images.githubusercontent.com/91564560/159548645-5b987345-d836-496d-b755-c36ad0cc399c.png)


### Actividad 2.7
Muevo este fichero a BASIC

![imagen](https://user-images.githubusercontent.com/91564560/159548897-c1b29ec3-7a3e-43e5-8f17-e1cf3d747aac.png)

### Actividad 2.8 - 2.9
Uso nano ```./PROG/BASIC/EJER.TXT``` para editar el fichero y borrar la primera frase.
Después le cambio el nombre y lo muevo.

![imagen](https://user-images.githubusercontent.com/91564560/159549493-9671a60a-5233-49d6-9adb-ed2b87ea7fd2.png)

### Actividad 2.10
Muestro el número de archivos en BASIC y NOTAS.

![imagen](https://user-images.githubusercontent.com/91564560/159550363-b3b07027-fc0f-4d77-a45f-18c6df1dcc62.png)

## EJERCICIO 3
### Actividad 3.1 - 3.2
Borro la carpeta accesss y en su lugar creo ASTRO. Desde allí creo la estructura de directorios.

![imagen](https://user-images.githubusercontent.com/91564560/159551609-809ff6e1-2594-43aa-b3a3-0be70b82f218.png)


