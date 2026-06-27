# AnalisisDeDatos32

--jalar cambios:
   
    git pull origin main

--obtener estado actual de repositorio:

    git status

--agregar cambios:
    
    git add .
    

--crear commit:

    git commit -m "agregar un comentario"

--empujar el cambio: 

    git push origin main

# Comandos Docker File

-- Crear una imagen:

    docker build -t jupyter_notebook .

-- Listar las imagenes:

    docker images

-- Crear Contenedor:

    docker run -d -p 8000:8888 --name jupyter jupyter_notebook

-- Lista los contenedores:

    docker ps

-- Log de ejecucion segundo plano:

    docker logs -f jupyter

-- Eliminar una imagen:

    docker rmi -f jupyter_notebook

-- Eliminar una contenedor:

    docker rm -f jupyter

-- Instalar librerias:

    pip install -r requeriment.txt