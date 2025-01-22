# Nombre: Miguel Angel Vanegas Cardenas.
# Laboratorio numero 1.
- Prueba uso de visual para escribir el README.md.
![alt text](images/imagenMD.png)
## Parte 1:
1.  Crea un repositorio localmente.
- El repositorio fue clonado desde el repositorio central ya creado. Para esto se uso los siguientes comandos.
    ```bash
        echo "# LaboratorioUnoCVDS" >> README.md
        git init
        git commit -m "first commit"
        git branch -M main
        git remote add origin https://github.com/miguelvanegas-c/LaboratorioUnoCVDS.git
        git push -u origin main
    ```
2.	Agrega un archivo de ejemplo al repositorio, el **README.md** puede ser una gran opción.
- Para agregar el archivo, primero se crea y despues se usan los siguientes comandos.
    ```bash
        git add .
    ```
    De esta manera ya seria agregado en caso de querer subirlo al repositorio centrar ese necesario hacer lo siguiente.
    ```bash
        git commit -m "Update readme"
        git push -u origin main
    ```
3.	Averigua para qué sirve y como se usan estos comandos **git add** y **git commit -m “mensaje”**
- git add se usa para añadir archivos, el commit funciona como un tipo de pantallazo donde se guarda el estado actual del respositorio, aparte de agregarle un mensaje al commit.
4.  Abre una cuenta de github, si ya la tienes, enlazala con el correo institucional.
- Ya contaba con una cuenta con el correo institucional.
5.	Crea un repositorio en blanco (vacío) e GitHub.
- El repositorio ya fue creado en la primera parte, ya que para crear el repositorio local fue clonado en base al central.
![alt text](images/imagenRepositorio.png)
   
6.	Configura el repositorio local con el repositorio remoto.
- Ya fue hecho en la primera parte, debido a que el repositorio fue clonado.
  
7.	Sube los cambios, teniendo en cuenta lo que averiguaste en el punto 3	
- Los cambios en el md hechos hasta el momento han sido subidos, tal y como se muestra en el siguiente pantallazo.
![alt text](images/imagenUpdate.png)
- Se hizo uso de los siguientes comandos
    ```bash
        git add .
        git commit -m "Update repository"
        git push origin main
    ```

8.	Configura el correo en git local de manera correcta
- Para realizar la configuracion se usaron los siguientes comandos.
    ```bash
        git config --global user.name "Miguel Vanegas"
        git config --global user.email "miguel.vanegas-c@mail.escuelaing.edu.co"

    ```

9.	Vuelve a subir los cambios y observa que todo esté bien en el repositorio remoto (en GitHub).
- Los cambios se realizaron de forma correcta.
