
# ESCUELA COLOMBIANA DE INGENIERÍA - CICLOS DE VIDA DE DESARROLLO DE SOFTWARE

 ![image](https://github.com/PDSW-ECI/labs/assets/118181543/7b7bba48-cbfb-4327-bec8-f72dc0d258e0)

- En el presente laboratorio vamos a aprender los manejos básicos de GitHub, esto con el propósito de que entiendas y comiences a trabajar con esta herramienta. Para este laboratorio se trabajará de manera individual la primera parte y con dos integrantes en la segunda parte.
  
## PARTE I (Trabajo Individual). 

### 1. Crea un repositorio localmente.
![alt text](resources/image.png)

### 2. Agrega un archivo de ejemplo al repositorio, el README.md puede ser una gran opción.

![alt text](resources/image-1.png)
![alt text](resources/image-2.png)

### 3. Averigua para qué sirve y como se usan estos comandos git add y git commit -m “mensaje”

#### Git add
Git add sirve para agregar los archivos que no han sido agregados al staged o area de trabajo.

#### git commit -m "mensaje"
El git commit sirve para guardar los cambios de los archivos que ya están en el stage y son a forma de metáfora, guardados en una imagen congelada en el tiempo. Ahora, el -m "mensaje" sirve para indicar el tipo de cambio que se hizo.

### 4. Abre una cuenta de github, si ya la tienes, enlazala con el correo institucional.
La cuenta de GitHub ya la había creado y enlazado el semestre pasado con mi cuenta institucional.

![alt text](resources/image-3.png)

### 5. Crea un repositorio en blanco (vacío) e GitHub
![alt text](resources/image-4.png)

### 6. Configura el repositorio local con el repositorio remoto.

* Configuración inicial, local credentials
    ![alt text](resources/image-5.png)

    cambiamos el nombre de la rama
    de master a main
    ![alt text](resources/image-6.png)
* Ahora enlazamos el repositorio local con el remoto. 

    Esto lo hacemos con: 
    ```bash
      git remote add origin https://github.com/cris-eci/cvds-git.git
    ```
    ![alt text](resources/image-8.png)
    Hacemos un fetch y un push para sincronizar. 
    ![alt text](resources/image-9.png)
### 7. Sube los cambios, teniendo en cuenta lo que averiguaste en el punto 3 Utiliza los siguientes comando en el directorio donde tienes tu proyecto, en este orden

#### Edición README en editor
 
![alt text](resources/image-14.png)

![alt text](resources/image-7.png)

![alt text](resources/image-10.png)

Ahora hacemos un push 
![alt text](resources/image-12.png)
Y nos autenticamos
![alt text](resources/image-11.png)

![alt text](resources/image-13.png)

### 8. Configura el correo en git local de manera correcta
![alt text](resources/image-21.png)

### 9. Vuelve a subir los cambios y observa que todo esté bien en el repositorio remoto (en GitHub).
![alt text](resources/image-20.png)