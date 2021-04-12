SISTEMAS DISTRIBUIDOS


INTRODUCCIÓN
 Prácticamente todo los grandes sistemas informáticos son en la
actualidad sistemas distribuidos.
 Un sistema distribuido es un sistema en el que el procesamiento de
información se distribuye sobre varias computadoras en vez de
estar confinado en una única máquina.
 Obviamente, la ingeniería de sistemas distribuidos tiene mucho en
común con la ingeniería de cualquier otro software, pero existen
cuestiones específicas que deben tenerse en cuenta cuando se
diseña este tipo de sistemas.

Objetivos de un Sistema Distribuido
En general el desarrollo de sistemas distribuidos intenta poner solución a los siguientes
objetivos:
 Transparencia.
Fiabilidad.
 Rendimiento.
 Capacidad de crecimiento.
Flexibilidad.
 Seguridad.
Sistemas operativos distribuidos, sistemas en red y sistemas cooperativos que
requieren diferentes facetas de estos objetivos.


Arquitecturas centralizadas
En las arquitecturas centralizadas, la relación entre los componentes sigue un patrón muy
característico, en el que hay una jerarquía definida de manera tal que ciertos
componentes requieren información o servicios que otros ofrecen.
 El modelo centralizado es el que sido ampliamente utilizado en los Sistemas de
Información de las grandes organizaciones en décadas anteriores, mediante un Host
que ejecutaba el 100% de la lógica del sistema, residiendo únicamente en el terminal de
usuario las funciones de presentación. A este tipo de aplicaciones, que concentran
todas las lógicas funcionales del software (presentación, negocio y acceso a datos) en
un mismo componente se les denomina aplicaciones monolíticas.

 Cliente-servidor
Esta arquitectura es la que estamos más acostumbrados a utilizar en entornos distribuidos. La web
es un ejemplo de ello. En el modelo cliente-servidor hay dos tipos de componentes:
 Clientes: hacen peticiones de servicio. Normalmente, los clientes inician la comunicación con
el servidor.
 Servidores: proveen servicios. Normalmente, los servidores esperan recibir peticiones. Una vez
que han recibido una petición, la resuelven y devuelven el resultado al cliente.
Finalmente, un servidor también puede ser cliente de otros servidores.
Servicios proporcionados por múltiples servidores
Los servicios se pueden implementar como diferentes procesos servidores que se ejecutan en
distintos ordenadores y que interactúan para proporcionar un servicio a procesos clientes. Los
servidores se pueden repartir los distintos objetos que componen el servicio que proporcionan 
Ejemplos
Único computador (caro y de gran potencia) con terminales alfanuméricos directamente
conectados.
• Entornos de empresa:
Soporte multiusuario
Uso de mainframes o minicomputadores
• Entornos científicos:
Ejecución eficiente de aplicaciones
Uso de supercomputadores
• Uso ocasional de la red:
Transferir ficheros o logins remotos
• Interfaz de usuario poco amigable
Interfaces gráficas gastan muchos recursos

Ventaja.
 La principal ventaja de este modelo es que se dispone y se procesa toda la
información en la misma máquina física, con lo que el software del sistema es
mucho más sencillo y fácil de gestionar
Desventaja.
 De las desventajas se puede nombrar su poca capacidad de crecimiento o
escalabilidad, ya que aunque los equipos que dan soporte a los mismos son de
una capacidad extrema, una vez se llega al límite de utilización del mismo, la
única posibilidad de crecimiento es la adquisición y sustitución por un nuevo
equipo con más potencia y capacidad, con el agravante de que estos sistemas
son de los más caros del mercado.

Arquitecturas Hibridas
Combinan los sistemas centralizados y descentralizados, la inteligencia del sistema
se localiza en diferentes nodos o módulos del control y estos tiene acceso a un
grupo de elementos de red, los sistemas distribuidos requieren un protocolo de
comunicaciones para las acciones coordinadas de los dispositivos.
Proporcionan una integración entre la estación de trabajo y la pila de
procesadores para combinar la ventaja de las arquitecturas anteriores.
El trabajo interactivo se lleva a cabo en las estaciones de trabajo, mientras que
los procesos no interactivos se ejecutan en el arreglo de microprocesadores.
Esta solución es mas cara pero mayor eficiente.

Ventajas.
 Seguridad en el funcionamiento y configuración.
Posibilidad de rediseño de la red.
Cableado reducido.
 Fácil ampliabilidad.
Desventajas.
Requieren alta programación
