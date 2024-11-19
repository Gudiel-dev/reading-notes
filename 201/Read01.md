<img src="https://media.licdn.com/dms/image/v2/C4D12AQHNTUWTSXmJpA/article-cover_image-shrink_600_2000/article-cover_image-shrink_600_2000/0/1623867840013?e=2147483647&v=beta&t=SuUmFXaLKwBTDrzK0aRFkBKj0vdASZd5w8tBFmuv074" alt="illustration of a client - server relationship">

# Read 01: Introducción a la Web Moderna

### ¿Qué roles desempeñan los clientes y los servidores en el funcionamiento de la web?

Los clientes vendrían a ser todo tipo de dispositivo que haría alguna solicitud a algún servidor mientras éstos últimos son quienes servirían de información a los primeros cerrando el ciclo entre cliente servidor.


### ¿Cómo se realiza la comunicación entre un navegador y un servidor al acceder a un sitio web?

Claro, aquí tienes el texto ordenado en párrafos y corregido en cuanto a la puntuación:
El proceso inicia cuando el usuario o cliente hace una solicitud de acceso a una web usando el navegador de turno e ingresando una dirección web mediante un dominio. En este punto, nos conectamos a un servidor DNS que ubicará la localización o dirección real del dominio en una dirección IP. Una vez encontrada la dirección real, nuestro navegador solicitará acceso al servidor donde está alojada la web en cuestión. Este último procesará nuestra solicitud, revisando que no seamos bots o pertenezcamos a botnets, y nos dará el OK, pasando por sus firewalls respectivos.

Es en este momento cuando el servidor nos brinda la información que necesitamos a través de pequeños paquetes. Este método evita que el servidor se sature al brindarnos los datos, permitiendo que también sean accesibles para cualquier otro cliente que esté realizando una solicitud paralelamente a nosotros. Como resultado final, nosotros podemos ver la información requerida en nuestro navegador o dispositivo. Una vez que el navegador analiza los paquetes, los reensambla para que puedan ser utilizados correctamente.

Por otro lado, el servidor envía los paquetes con un checksum para analizar la integridad de los mismos durante el proceso de transferencia entre servidor / cliente.

Cabe resaltar que todo este proceso de comunicación entre cliente-servidor está sujeto bajo el protocolo HTTP

### ¿Cuáles son las principales ventajas de utilizar un IDE en la nube en comparación con un IDE local?

Los IDE en la nube ofrecen una plataforma de desarrollo independientemente de la plataforma que se use, lo cual hace fácil trabajar en ellas desde diferentes dispositivos y OS, permitiendo la colaboración con otros usuarios trabajando en tiempo real, compartiendo espacios de trabajo, permitiendo acceso remoto. Asimismo, permite la escalabilidad reduciendo los costos en hardware local, brindando actualizaciones automáticas

### ¿Qué funciones automatizadas comunes se encuentran en la mayoría de los IDE, y por qué son importantes para los desarrolladores?

las funciones que se suele encontrar en los IDEs son:
- Completado del código:
    - El IDE sugiere completado del código basado en el contexto y lenguaje ahorrando tiempo reduciendo los errores

- Resaltado de sintaxys y detección de errores
    - Nos brinda mayor legibilidad del código permiténdonos la identificación de errores tempranamente.
    
- Refactorización del código.
    - Ayuda a los desarrolladores a mejorar la calidad del código, mantenimiento y legibilidad. Facilitando el trabajo a largo plazo.
    
- Herramientas de depuración
    - Nos ayuda a identificar y corregir los errores en código
    
- Integración con control de versiones
    - Facilidad de integración con sistemas de control de versiones como GIT. Permitiendo a los desarrolladores un seguimiento del desarrollo del código, colaboración y gestión del proyecto.
  
<p align="center">
<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>