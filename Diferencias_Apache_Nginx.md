##Diferencias entre Apache y Nginx.

* **Manejo de conexiones**
..* Una gran diferencia entre estos, es el manejo de la conexión entre servidores, ya que Apache proporciona una variedad de módulos de multiprocesamiento que ayudan a manejar las peticiones de los clientes. Esto permite a los administradores que cambien su manejo de conexiones. Por su parte Nginx, al salir después de Apache, tuvo la ventaja de conocer los problemas de concurrencia que se podrían presentar. Por este caso Nginx, trabaja usando un algoritmo de manejo de conexiones por eventos, utilizando una máquina asíncrona sin bloqueos.
* **Contenidos dinámicos y estáticos**
..* Ngnix es más veloz en el servicio de archivos estáticos y consumen menos memoria por peticiones comunes, debido a que Nginx es basado en eventos, no necesita realizar nuevos procesos para cada petición, por lo tanto su uso de memoria es mínima.
* Nginx está claramente en ascenso de su popularidad; una de las razones es que la arquitectura de Apache pasa sentirse anticuada debido a las nuevas exigencias de las aplicaciones y velocidad requerida. La arquitectura de los microservicios se perfila como la tecnología del futuro para aplicaciones y sitios web, por lo que Nginx está preparado para asumir su lugar como la plataforma de distribución de aplicaciones ideales para la web moderna.
