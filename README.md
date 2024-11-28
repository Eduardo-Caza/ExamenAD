# Prueba Bimestral Desarrollo de Aplicaciónes Móviles 📝

> **Estudiante**: Eduardo Caza - Luis Guaygua

Desarrollo de un Cliente Servidor RMI con subida a Docker

Contenido : Un C/S RMI con contenedor en Docker

---

## Pasos a Seguir para ejecutar el C/S en Docker 💻

1. Para construir la imagen del contenedor
   ```bash
   docker build -t calculadora-rmi .
2. Ejecutar el servidor dentro de un contenedor con puerto mapeado
   ```bash
   docker run -d -p 1099:1099 --name servidor-rmi calculadora-rmi
3. Ejecutar el cliente dentro de otro contenedor ejecutando en la terminal
   ```bash
   docker run -it --network host calculadora-rmi java ClienteRMI 
4. Ejecucion del C/S:

![image](https://github.com/user-attachments/assets/00145381-018b-468d-b78e-54522fe88bfe)


