# FDV_1.3_Perforce

_**1. Crear una conexión al depósito FDV2425 en la ULL**_

Primero, establecemos una conexión al servidor:

![1  Conexión servidor](https://github.com/user-attachments/assets/f34bbe0d-9d4c-4faf-86eb-01c2b441495d)

Luego, creamos un workspace que realice un seguimiento del depósito _"FDV2425"_.
![2  Workspace](https://github.com/user-attachments/assets/c5aaf873-28e9-4b1c-b537-e01fa9ba6dce)

**_2. Clonar el repositorio_**

Seleccionamos el depósito que deseamos clonar y pinchamos el botón _"Get Latest"_.
![3  Clonar repositorio](https://github.com/user-attachments/assets/08f2457b-82f6-4e3d-b94f-1a5acbc0d153)

_Repositorio clonado:_
![4  Repositorio clonado local](https://github.com/user-attachments/assets/855d7f95-0643-4f87-b634-a2ecb29778d1)

_**3. Modificar el fichero presentacion.txt, agregando una frase que indique tu nombre y resuma tu experiencia en el programación de videojuegos 2D y 3D.**_

Seleccionamos el archivo y pulsamos el botón _"Checkout"_ para poder modificarlo.
![5  Checkout](https://github.com/user-attachments/assets/cf37839d-90ac-445b-8674-a65fb4a2605f)

Cuando hayamos terminado de modificarlo, pulsamos el botón _"Submit"_.
![6   Submit](https://github.com/user-attachments/assets/20b9cce4-efa9-459c-8f4c-8aa11bc8a1a9)

_**4. Crear un fichero nuevo, tu_nombre.txt y añádelo al proyecto.**_

Creamos el archivo en local y desde la pestaña _"Workspaces_" lo seleccionamos. Ahora, pulsamos el botón _"Add"_ para que Perfoce haga un seguimiento. Finalmente, pulsamos _"Submit"_ para terminar de añadirlo al depósito.
![7  add](https://github.com/user-attachments/assets/b83e935f-d873-47a9-929f-e03da843ff70)

_**5. Crear un proyecto Unity 3D básico y agregarlo al depot de la asignatura. Tu nombre debe ser prefijo.**_

Antes de subir el proyecto al depósito, configuraremos el archivo encargado de ignorar ciertos ficheros del proyecto. Para ello, abrimos el CMD de Windows desde la ruta del proyecto y ejecutamos el siguiente comando:

```
p4 set P4IGNORE=.p4ignore
```

![10  p4ignore](https://github.com/user-attachments/assets/da4389bd-4c71-4ba2-98a6-9273c3892d25)

Ahora, creamos el archivo en la raíz del proyecto con el nombre `.p4ignore`, sin extensión ninguna, y añadimos dentro los archivos que ignoraremos.
![11  p4ignore](https://github.com/user-attachments/assets/bf372ff0-2698-4908-873b-4e821eafb9d2)

Ahora, desde P4V, añadimos el proyecto de Unity al seguimiento. Para ello, nos dirijimos a la pestaña _"Workspaces_" y seleccionamos el directorio que contiene el proyecto de Unity. Después, pulsamos el botón _"Add"_ para que Perfoce haga un seguimiento. 
![x  add unity depot](https://github.com/user-attachments/assets/843e1a9e-3e7c-4d68-8089-5f90064cfc89)

Finalmente, pulsamos _"Submit"_ para terminar de añadirlo al depósito.

_Proyecto de Unity en el depot "FDV2425":_
![12  Unity en P4V](https://github.com/user-attachments/assets/dd517e7c-e512-4281-94f3-2922b7a6a8f2)


_Archivo en el depot "FDV2425":_
![x2  archivo](https://github.com/user-attachments/assets/9fe784c0-5778-4a1b-801a-945077748bce)



