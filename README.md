# Nginx-install

Primero instalamos Nginx utilizando el siguiente enlace: https://nginx.org/en/download.html
Una vez instalado vamos a la carpeta a la aplicacion donde pone Nginx y lo instalamos y permitimos acceso
Para comprobar que este bien instalado podemos ir a google y poner "localhost" para comprobarlo

El segundo paso es instalar la maquina de alpine y la exportamos en nuestro oracle
Nos logeamos utilzando el usuario: root / contraseña: maximo
![image](https://user-images.githubusercontent.com/91744605/166510021-677686e6-6310-428a-9bc6-26c0ac918286.png)

Despues, nos situamos en la carpeta conf y hacemos una copia del archivo nginx.conf que llamaremos sites-enabled
![image](https://user-images.githubusercontent.com/91744605/166519304-9da9228d-ce03-4a9b-a3be-10b80a30c7bd.png)

Una vez hemos realizado la copia abirermos el fichero nuevo con notepad y cambiamos el server por lo siguiente
![image](https://user-images.githubusercontent.com/91744605/166519830-205e14ef-300f-407d-aec1-29edc155f5e5.png)

Despues nos situaremos dentro del fichero cambiando el nombre del server por el que nostros hemos creado.
Finalmente lo linkeamos a nuestro archivo html y lo tendriamos en nuestro pagina localhost
![image](https://user-images.githubusercontent.com/91744605/166523644-691c5dd9-ef5c-4def-b822-8cb152970db2.png)


