# Microservices dockerization
Para correr el proyecto en docker:
1. Se deben descargar todos los microservicios y los archivos de este repositorio (`docker-compose.yml` e `init.sql`) en una sola carpeta. La carpeta debe verse como la siguiente imagen:

    <img width="532" alt="image" src="https://github.com/FUNDAMENTOS-DocSeeker/dockerization/assets/68360681/bed1906a-74ae-44f7-a0e0-2d7e59662735">

2. Luego, se debe abrir cada uno de los servicios y cambiar a la rama `feature/dockerization`
3. Después, dentro de la carpeta de cada uno de los servicios, se debe ejecutar el comando `.\mvnw clean package -DskipTests` 
4. Finalmente, se debe utilizar el comando `docker-compose up` y los contenedores se ejecutarán de esta manera:
   
   <img width="752" alt="image" src="https://github.com/FUNDAMENTOS-DocSeeker/dockerization/assets/68360681/12d7d00e-7f0e-4dcc-b920-af0f4420af6a">

   
