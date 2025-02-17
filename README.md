# **Proxy Inverso con Docker - Fco. Javier Martín Mariscal**

## **Introducción**
Este documento describe la configuración de un proxy inverso utilizando dos contenedores Docker  el dominio `example.test`.

## **Configuración del Servidor Web (w1)**
![image](https://github.com/user-attachments/assets/56ac2015-3901-4b16-a7d9-a93ab2bbbeb5)

Crear el archivo /var/www/html/index.html con el siguiente contenido:

![image](https://github.com/user-attachments/assets/da80eae0-a299-4c43-99b2-a913aeec5611)

Dockerfile de web:
![image](https://github.com/user-attachments/assets/eef90789-49ba-48e3-b2e6-ca00231d5eec)

## **Configuración del Proxy Inverso**
![image](https://github.com/user-attachments/assets/0afb9d17-a417-4770-83d5-7758276e0266)

Dockerfile de proxy:
![image](https://github.com/user-attachments/assets/b64e28da-32b8-4ac1-af06-0cdf5109e05d)

## **Configuración del docker-compose.yml**
![image](https://github.com/user-attachments/assets/2dea23ed-63d0-4653-98a4-e9458bfd67b0)

## **Hacemos el docker up:**
![image](https://github.com/user-attachments/assets/2cf3c3fa-5922-4035-9496-4d07d368a5d5)
![image](https://github.com/user-attachments/assets/badf297b-fdc9-4c55-947f-104a750d72e0)

## **Comprobaciones:**
Accederemos en nuestro navegador a la web configurada: (Las cabeceras ya están añadidas como hicimos en la parte anterior)
![image](https://github.com/user-attachments/assets/051e8a62-85d5-4e48-b3c7-410bd15d3301)














