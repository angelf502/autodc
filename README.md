Funciona para sistemas operativos basados en Debian.
# Instalación
```
git clone https://github.com/angelf502/autodc
cd autodc/
python3 main.py
```
# Vista
![DC](https://i.ytimg.com/vi/w8LRLkdWwc4/maxresdefault.jpg)

# Utilidades
- **samba**: Es un conjunto de herramientas que se utilizan para compartir entre redes mixtas de Windows y Linux.
- **smbclient**: Es un cliente de samba que prueba conectividad.
- **krb5-config**: Contiene información de configuración de Kerberos, incluidas las ubicaciones de los KDC y los servidores de administración para los dominios de Kerberos de interés.
- 
Cuando lleguemos a esta parte en la configuración nos pedirá que pongamos un "Reino predeterminado para la versión 5 de kerberos", en el que podemos poner el dominio que queremos. Ejemplo: google.es, youtube.com.gt, etc.
![1](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjOylkY39GKMjxavpvTkPxa6UV55oW8wJeLR422AwmmdgVlQ0UwG_3yzlfpX_Qky19q0KxhCF73xpXHS38DjHdRK8mvDpz3U5LqBfHT21tSOTw6M9oPhfyRR-qCAMmTaw0dtW65s3cv7AzwqlaKgNcOov2cvNfRfVFlK_b_DRQuUWJgoJQqVFbp8eP9IA/s1359/1.JPG)

Luego llegamos a "Servidores kerberos para su reino", debemos poner únicamente el nombre del equipo que lo está ejecutando (hostname).
![2](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiephYoZDDxD_uYjqBxbUpweplnlLPevzEv12pL9at6Hi8bKX7rxe1ahB8bduN7-EZmG0sptMVKFlBpcQ1PjTm2wLcyB4fP4YaoZ1TnLKQ9GEw18S4a3z9TNKC-Hg-91Rd2e_CefYHcHqK7iwbm3rn7HSLhONmKnnp-n27pQGa7mMh87Bc3gKlXXTv1YQ/s1354/2.JPG)

Por último un "Servidor administrativo para su reino", debemos poner el nombre del equipo (hostname)
![3](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiIt46c3sV3LNlQVbOXELLY8etngxJgW6dK3vi-0rI8nHvL9LmttFRX_n9g0crcYsKbSukdt5qJzrz4Yh2XzgN2h0DNhhHqFpxHWEikJxaAbEW1l-TS-DwelYaw0iX_FtpF7LJWqboqKnB2BW1_uFrVAH0_hO9QHCC5FmrahfgRNiu9dLH59dwpavRW0A/s1293/3.JPG)
