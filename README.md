# Resoluci-n-Maquina-SUID-Bash

# Apertura
Realizamos la descarga y apertura de la maquina}
<img width="1920" height="1140" alt="Captura de pantalla 2025-12-21 205021" src="https://github.com/user-attachments/assets/2475179e-fb77-4c8b-9f89-79cee60fc9e1" />

# Reconocimiento
Realizamos un nmap para verificar los puertos que tiene la maquina abiertos y los servicios que corren en ella
<img width="1920" height="1140" alt="Captura de pantalla 2025-12-21 205010" src="https://github.com/user-attachments/assets/0c4b2c14-b860-45d8-8b15-c4b8592f05b2" />

Ingresamos a la maquina utilizando las credenciales que nos proporciono la maquina
<img width="1920" height="1140" alt="Captura de pantalla 2025-12-21 205219" src="https://github.com/user-attachments/assets/c29a73a0-6cb5-4588-a16c-9157237d94b9" />

<img width="1920" height="1140" alt="Captura de pantalla 2025-12-21 205306" src="https://github.com/user-attachments/assets/100ae238-6e15-4c54-88b8-980bf39c8b0d" />

Una vez dentro de la maquina leimos las intrucciones 
<img width="1920" height="1140" alt="Captura de pantalla 2025-12-21 205306" src="https://github.com/user-attachments/assets/ebb9008f-dd8d-41ee-accd-e50fdfff6df6" />

Luego Listamos los archivos y luego procedimos a la busqueda de los binarios para verificar si podiamos encontrar alguno mal configurado
<img width="1920" height="1140" alt="Captura de pantalla 2025-12-21 205425" src="https://github.com/user-attachments/assets/1364fa85-a0df-4871-8bb6-10c561cea4c3" />

Hicimos algunas busquedas de archivos que ibamos encontrando, sin obtener nada que nos interesara o ayudara
<img width="1920" height="1140" alt="Captura de pantalla 2025-12-21 205502" src="https://github.com/user-attachments/assets/186d2644-e316-4ade-8ee1-3037b1966b22" />

# Explotación
Hasta que pudimos ubicar el binario que nos proporciono el ingreso a la maquina
<img width="1920" height="1140" alt="Captura de pantalla 2025-12-21 205932" src="https://github.com/user-attachments/assets/a337782e-25d5-473c-b60e-b9ad750e28e5" />

Listamos los archivos en busqueda de algo que nos sirviera hasta que pudimos encontrar el archivo con la flag.txt
<img width="1920" height="1140" alt="Captura de pantalla 2025-12-21 210001" src="https://github.com/user-attachments/assets/4e98e7ce-8f82-436a-a389-5b8f8e873e25" />

Verificamos el contenido del archivo y nos percatamos que en efecto es la flag que estabamos buscando
<img width="1920" height="1140" alt="Captura de pantalla 2025-12-21 210012" src="https://github.com/user-attachments/assets/33961216-9678-4846-88c3-467659b66895" />

Y de esa manera dimos por terminada nuestra maquina
<img width="1920" height="1140" alt="Captura de pantalla 2025-12-21 210052" src="https://github.com/user-attachments/assets/10e396ee-e129-48e7-9942-288b672217b3" />
