1. Agregue el README

2. Use el comando 'npm init -y' para inicializar npm (gestor de paquetes y dependencias) y se descarga el package.json

3. Use el comando 'npm install express -E' para instalar express

4. Configuro el package.json agregando el '"type": "module"', para aclarar que la app funciona con modulos

5. Creo la carpeta server y el codigo en index.js para crear lo primero del servidor

6. Agrego el script '"dev": "node --watch server/index.js"' para facilitar las pruebas del codigo

7. Descargo la dependencia Morgan para facilitar el saber como esta funcionando el servidor 'npm install morgan -E'

8. Descargo la dependencia socket.io 'npm install socket.io -E' para poder hacer una coneccion en tiempo real