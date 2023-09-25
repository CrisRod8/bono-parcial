# bono-parcial

Autor: Cristian Fernando Rodríguez González  

## EJECUCIÓN 
1. Clonar el repositorio usando el código a continuación:  
    ```
    git clone https://github.com/CrisRod8/bono-parcial.git
    ```

3. Dentro de la carpeta creada abrimos el cmd y ejecutamos el siguiente comando:
   
   ```
   mvn clean install
   ```
   
   Después:
   
  

   ```
   java -cp "target/classes;target/dependency/*" org.example.SparkWebServer
   ```
   

   
   Debemos recibir la siguiente respuesta:
  ![image](https://github.com/CrisRod8/bono-parcial/assets/111186898/a5e823af-e40d-4b66-9c26-5ef7b73efe49)
   
## PRUEBAS  
Desde algun browser, escribimos la direccion: http://localhost:4567/  

  ![image](https://github.com/CrisRod8/bono-parcial/assets/111186898/7ec38113-6cdb-44e0-8546-d8d510298d0e)
   
## PRUEBAS

1. Seno 0.5: http://localhost:4567/sin/0.5
   
  ![image](https://github.com/CrisRod8/bono-parcial/assets/111186898/61469180-6a78-47ca-a16b-38683e16a3a1)

3. Cos 180: http://localhost:4567/cos/180
   
  ![image](https://github.com/CrisRod8/bono-parcial/assets/111186898/ce417bb8-ef6e-4e1b-ad18-7821b114b1df)

5. Palindromo de (ana): http://localhost:4567/isPalindrome/ana
   
  ![image](https://github.com/CrisRod8/bono-parcial/assets/111186898/0ec871ab-1f16-4aab-a730-12db96832b5d)

7. Palindromo de (piso): http://localhost:4567/isPalindrome/piso
   
  ![image](https://github.com/CrisRod8/bono-parcial/assets/111186898/c4d4e332-7917-4af0-92f1-a1f6e30ed60c)  
  
8. Magnitud de 5 y 6:  http://localhost:4567/magnitude/5/6

  ![image](https://github.com/CrisRod8/bono-parcial/assets/111186898/b3fc6815-cbf2-4b09-8652-2a1ba596e9d4)  

## DOCKER

Seguimos el paso a paso del enunciado del taller:

![image](https://github.com/CrisRod8/bono-parcial/assets/111186898/29d29af5-3b3c-479c-b9fc-e5ec3b92ed82)  

Comprobamos la construcción de la imagen:

![image](https://github.com/CrisRod8/bono-parcial/assets/111186898/8bb8c59b-0253-49b7-a516-3fc1b1f72e51)  

Creamos instancias de contenedores docker:

![image](https://github.com/CrisRod8/bono-parcial/assets/111186898/522e42e2-d06f-4e88-a704-b00cbda89a86)
![image](https://github.com/CrisRod8/bono-parcial/assets/111186898/8427ddbb-11e4-4778-94dd-4986d76d350a)  

Probamos que esten corriendo los contenedores:

![image](https://github.com/CrisRod8/bono-parcial/assets/111186898/d8b27de4-3032-4766-ae1f-5282b8349c25)  

Probamos:

![image](https://github.com/CrisRod8/bono-parcial/assets/111186898/ee88faec-a233-46bf-ab07-31e382d2e3bb)

Usamos y ejecutamos docker-compose para generar automaticamente la configuración docker:  

```
docker-compose up -d
```
![image](https://github.com/CrisRod8/bono-parcial/assets/111186898/f118992c-4989-4f5e-9deb-e9e7177f0e7d)  

Verificamos que se crearon los servicios:  

![image](https://github.com/CrisRod8/bono-parcial/assets/111186898/3546d85c-73e4-4bfe-86aa-aceb3d6db9be)  

Docker Desktop dashboard:  

![image](https://github.com/CrisRod8/bono-parcial/assets/111186898/9c62ab12-6820-43ac-af89-8ec5399984b3)

Finalmente, creamos un repositorio en Docker Hub y hacemos push de la imagen:

![image](https://github.com/CrisRod8/bono-parcial/assets/111186898/320db606-c65e-47d4-bf64-38e79471b18e)  

En el apartado de Tags del repositorio tenemos:

![image](https://github.com/CrisRod8/bono-parcial/assets/111186898/227d87f8-9efc-473c-a6b8-fffb860de8f9)






















