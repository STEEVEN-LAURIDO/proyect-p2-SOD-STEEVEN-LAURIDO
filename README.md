# proyect-p2-SOD-STEEVEN-LAURIDO
**¿Qué es Amazon Route 53? **
Amazon Route 53 es un servicio web de sistema de nombres de dominio (DNS) escalable y de alta disponibilidad. Puede utilizar Route 53 para realizar tres funciones principales en cualquier combinación: registro de dominio, direccionamiento de DNS y comprobación de estado.

**¿Para qué sirve el servicio Route53?**
Route53 es un servidor DNS de alta disponibilidad escalable que es designado para dar a los desarrolladores y negocios un costo efectivo y servicio confiable para enrutar a los usuarios a las aplicaciones de Internet.

**Características principales**
•	Route 53 Resolver
Obtenga DNS recursivo para su Amazon VPC y las redes de trabajo que se encuentran en las instalaciones. Cree reglas de reenvío condicional y puntos de enlace DNS para resolver nombres personalizados controlados en las zonas privadas alojadas en Amazon Route 53 o en sus servidores DNS que se encuentran en las instalaciones.
•	Firewall de DNS de Route 53 Resolver
Proteja sus consultas de DNS recursivo dentro del Route 53 Resolver. Cree listas de dominios y establezca reglas de firewall que filtren el tráfico de DNS saliente según dichas reglas.
•	Flujo de tráfico
Administración del tráfico global rentable y fácil de usar: redirija a los usuarios finales hacia los mejores puntos de enlace para su aplicación en función de la geoproximidad, la latencia, el estado y otras consideraciones.
•	Direccionamiento basado en la latencia
Remite a los usuarios finales a la región de AWS que ofrezca la menor latencia posible.
•	DNS geográfico
Remite a los usuarios finales a un punto de enlace determinado que usted especifique en función de la ubicación geográfica del usuario final.

Funcionalidad
Amazon Route 53 cuenta con una sencilla interfaz de servicios web que permite ponerse en marcha en cuestión de minutos. Los registros DNS se organizan en "zonas hospedadas" que se configuran con la API de Route 53. Para utilizar Route 53, simplemente necesita:
•	Suscribirse al servicio mediante el botón de inscripción existente en esta página.
•	Crear una zona hospedada que pueda almacenar registros DNS para su dominio. Cuando crea la zona hospedada, recibe cuatro servidores de nombres de Route 53 en cuatro dominios de nivel superior (TLD) diferentes, lo que permite garantizar una alto nivel de disponibilidad. 
•	La zona hospedada se llena inicialmente con un conjunto básico de registros DNS, que incluye cuatro servidores de nombres virtuales que responderán a las preguntas del dominio. 
•	Si prefiere mantener su nombre de dominio con su proveedor actual, infórmeselo al proveedor para que actualice los servidores de nombre de su dominio a los nombres asociados con su zona hospedada.

**Cómo Verifica Amazon Route 53 El Estado De Los Recursos**
Las comprobaciones de estado de Amazon Route 53 monitorean el estado de sus recursos, tales como servidores web y servidores de correo electrónico. Si lo desea, puede configurar alarmas de Amazon CloudWatch para sus comprobaciones de estado, de modo que reciba una notificación cuando un recurso deje de estar disponible.


**Precios de Amazon Route 53**
Amazon Route 53, se paga por  lo que se utilice, ya que no utiliza cuotas por adelantado ni a un número de consultas respondidas para el dominio. Al igual que ocurre con otros servicios de AWS, pagará por uso, es decir, solo por el consumo realizado.
•	Administración de zonas alojadas: se paga una tarifa mensual por cada zona hospedada que se administre con Route 53.
•	Servicio de consultas de DNS: se cobrarán cargos por cada consulta de DNS a la que responda el servicio Amazon Route 53, excepto las consultas a registros.
•	Administración de nombres de dominio: se paga una tarifa anual por cada nombre de dominio que se registre a través de, o se transfiere a, Route 53.
