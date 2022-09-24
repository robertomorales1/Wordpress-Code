# Wordpress-Code
Obtener el repositorio de una página web de wordpress en Azure

En portal.azure.com, en el servicio del App Servie, hacemos clic en Obtener perfil de publicación:

![image](https://user-images.githubusercontent.com/106035353/192122381-e42da730-e96f-49b8-a614-f28aa9e8067e.png)

Abrimos el archivo descargado con el bloc de notas:

![image](https://user-images.githubusercontent.com/106035353/192122406-d4da0887-0261-4ac8-a031-11c0938535a7.png)


Abrimos Filezilla (cliente FTP que nos permitirá descargar el archivo de nuestro alojamiento remoto):

![image](https://user-images.githubusercontent.com/106035353/192122462-8b3fdabb-e4c2-426d-b2e7-c213f4e7172f.png)

![image](https://user-images.githubusercontent.com/106035353/192122524-aca48261-d54a-4d7c-be75-40475a24755d.png)

Con el servicio de azure activo, buscamos en el bloc de notas el servidor de nuestra página, que empezará con publishurl="ftp:" como en la siguiente imagen:

![image](https://user-images.githubusercontent.com/106035353/192122553-b61a8992-13c6-40b9-8d07-a696a20220ed.png)

Copiamos y pegamos en la casilla que dice Servidor en la parte superior izquierda del Filezilla:

![image](https://user-images.githubusercontent.com/106035353/192122586-4d3852bd-7fef-4c6e-8efc-ca18902b4283.png)

Hacemos lo mismo con el nombre de usuario y el password, que empezará con userName y userPWD como se muestra en la siguiente imágen:

![image](https://user-images.githubusercontent.com/106035353/192122610-4da1d0db-68b0-47a5-b14e-131a25a09b50.png)

Pegamos en las casillas correspondientes el usuario y el password, y hacemos clic en Conexión Rápida; elegimos la carpeta donde se guardara de lado inferior izquierdo del programa, (en este caso Desktop) y en el lado derecho hacemos clic derecho y Descargar para obtener el repositorio:

![image](https://user-images.githubusercontent.com/106035353/192122712-6f857c72-735c-4b69-aac1-dea5b503f360.png)

Verificamos en la carpeta destino el folder con la descarga correspondiente:

![image](https://user-images.githubusercontent.com/106035353/192122718-9e2ddc85-ee43-45a8-8905-7caa672c825a.png)






