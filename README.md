# Cloud Management
Diplomado Cloud Management de TI Capacitación en 2013

## NUBE

Es un término informático que se refiere a una infraestructura de cómputo donde se pueden interconectar distintos dispositivos utilizando distintos medios de comunicación.

Se pueden encontrar Servidores ejecutando aplicaciones y servicios como:
- Servicios para hospedar páginas web.
- Servicios para almacenar archivos.
- Servicios para almacenar datos.
- Servicios de colaboración, mensajería, etc.

### Nube Privada (Recursos On-premise)
Es la implementación de los servicios de cómputo sobre la infraestructura interna de las empresas. Las aplicaciones se ejecutan en la intranet, los datos se almacenan sobre la infraestructura de la intranet. Las organizaciones pueden evitar los gastos que implica la adquisición de hardware y software mediante la creación de ambientes virtualizados.
Proporcionan seguridad de los datos cumpliendo con políticas de la empresa de no exponer los datos.

### Nube Pública (Recursos Off-premise)
Ubicada sobre la infraestructura del proveedor de servicios de cómputo. Menores costos y alta disponibilidad.

### Nube Híbrida (Ambientes híbridos)
Las aplicaciones y los datos se ubican parcialmente en ambientes privados y públicos.

![Cloud On-premise vs Off-premise](https://user-images.githubusercontent.com/2154886/141395669-fa6060d1-6fd2-4aed-8971-8cbbbc0bfbe0.png)


## CÓMPUTO EN LA NUBE (CLOUD COMPUTING)

Computación basada en Internet, mediante la cual los recursos se proporcionan a las computadoras u otros dispositivos sobre demanda.
Poder acceder a aplicaciones de software o datos mediante Internet (el explorador web). Pagamos por lo que consumimos.

### Gastos de operación
Pagos por el consumo de los servicios a los proveedores. Son más flexibles, conforme aumentan las necesidades de los datos y aplicaciones se pueden obtener más servicios. Solo pagamos por lo que consumimos, escalamos bajo demanda.

### Gastos por activos fijos
Un centro de datos propio implica gastos por la adquisición de activos fijos. Gastos de mantenimiento y actualización del centro de datos.

![Recursos computacionales en el Tiempo](https://user-images.githubusercontent.com/2154886/141396043-9dcfe4fc-ffba-40ae-8c61-88e2d59b2c82.png)

Los centros de datos son buenos cuando la demanda es alta, pero cuando baja es un desperdicio. El cómputo en la nube elimina gastos de mantenimiento y actualización, por lo tanto se ahorran costos, solo se paga por la renta de espacio de los datos y las aplicaciones.

![Utility Computing](https://user-images.githubusercontent.com/2154886/141396174-51f28ce8-af6d-48ba-9093-3bbe998c604a.png)

**Utility Computing:** Suministro de recursos computacionales.
El cómputo en la nube mejora el acceso a las aplicaciones y los datos, mediante el explorador web.

**Computación ubicua:** Está presente en un mismo tiempo en todas partes.

![Agilidad para empresas TI](https://user-images.githubusercontent.com/2154886/141396749-95c68a4f-d7a7-432d-94c9-07a1acf8cfac.png)

### Contrato de nivel de servicio - Service Level Agreement SLA
Es un contrato escrito entre un proveedor de servicio y su cliente con objeto de fijar el nivel acordado para la calidad de dicho servicio.


## TIPOS DE SERVICIOS

1. Ofrecen la Infraestructura de sus centros de Datos.
2. Ofrecen la Infraestructura de sus centros de Datos y herramientas para que puedan realizar las aplicaciones (APIs, SDKs)
3. Ofrecen aplicaciones listas para ser utilizadas y almacenamiento para los datos.

## CATEGORÍAS
Ontología del Cómputo en la nube

![Cloud Computing Ontology](https://user-images.githubusercontent.com/2154886/141397150-4587b6e6-96e0-4546-9809-9b6ab21681a0.png)

1. Infraestructura como Servicio **IaaS**
Servicio normal de hospedaje de un centro de datos, los proveedores rentan tiempo de cómputo y espacio de almacenamiento.

![IaaS](https://user-images.githubusercontent.com/2154886/141397436-bf998b08-db16-4c4e-b746-b063d10c8b3f.png)

2. Plataforma como Servicio **PaaS**
Incluye los servicios de Infraestructura y otros adicionales. Proporciona la plataforma sobre la cual se pueden desarrollar aplicaciones para la nube. El desarrollador solo se enfoca en la creación del código para resolver las necesidades de la empresa
**CloudWare**: Sistema operativo para cómputo en la nube.

![PaaS](https://user-images.githubusercontent.com/2154886/141397585-b3593764-251c-4cad-bfd0-013d72c3d87f.png)

3. Software como Servicio **SaaS**
Permite que una aplicación este disponible en internet mediante una suscripción de pago por el servicio. Los usuarios no desarrollan aplicaciones, utilizan las aplicaciones en la nube. El proveedor se encarga de la infraestructura, el trabajo de instalación, configuración y mantenimiento de las aplicaciones.

![SaaS](https://user-images.githubusercontent.com/2154886/141397676-2c386560-94b1-4053-acfc-24cdb2dd8b2c.png)


## WINDOWS AZURE

Es la plataforma de cómputo en la nube de Microsoft, es una nube pública del tipo plataforma como Servicio Paas. Proporciona el Software y Hardware para hospedar datos y aplicaciones. Proporciona Máquinas virtuales. Las aplicaciones y los datos son replicados 3 veces y se paga por lo que se consume.
Los centros de datos de Microsoft (Más de una docena, cada uno posee miles de servidores), aportan la infraestructura para las aplicaciones y los datos.

![Centro de Datos Microsoft](https://user-images.githubusercontent.com/2154886/141397797-c9505a3a-0a00-43ce-a795-afe80ad4251c.png)

Las máquinas virtuales de **Hyper-V** permiten ejecutar varios Sistemas Operativos de manera simultánea en el mismo servidor físico. Corren Windows Server 2008 Release 2.

![Categorías de servicios en Windows Azure](https://user-images.githubusercontent.com/2154886/141397904-756d0909-1b78-47c0-ae33-bf472090d6fc.png)

## MODELOS DE EJECUCIÓN

1. **SITIOS WEB (WEB SITES) -> IaaS**

Se enfoca en la ejecución de la aplicación y sus datos. Proporcionan hospedaje web como una infraestructura como servicio. Todas corren en el IIS o en Windows Azure Web Sites(Ejecuta IIS y Windows Server en una máquina virtual).
- Sitios Web Estáticos
- Aplicaciones Web Populares: Drupal, Wordpress, etc
Soporta una gran cantidad de aplicaciones populares, y para los que emplean MySQL existe ClientDB para Windows Azure.
- Aplicaciones Web personalizadas: ASP.NET, PHP, Node.js
Pueden existir copias de las aplicaciones para proporcionar un balance de las peticiones.

![Frameworks Web Soportados](https://user-images.githubusercontent.com/2154886/141398458-f0d85f68-79df-4910-942c-973e190958c3.png)

![Métodos de publicación Soportados](https://user-images.githubusercontent.com/2154886/141398602-e7dcff05-dd5c-4df9-a128-f614c6da53c4.png)

2. **SERVICIOS EN LA NUBE (CLOUD SERVICES) -> PaaS**

Podemos ejecutar aplicaciones y sus datos, podemos establecer reglas de firewall o redes virtuales. Proporciona servicios de cómputo en una plataforma como servicio, soportando aplicaciones escalables, confiables y económicas en su operación. Los desarrolladores no se tienen que preocupar de administrar la plataforma de sus aplicaciones.

> Cloud Service = Código + Configuración

### Componentes de un Cloud Service
- **Archivo de definición del servicio (.csdef)**
Define el modelo del servicio, incluyendo el número de roles.
- **Archivo de configuración del servicio (.cscfg)**
Proporciona valores de configuración para Cloud Service y para roles individuales, incluyendo el número de instancias de los roles.
- **Paquete del Servicio (.cspkg)**
Contiene el código de la aplicación y el archivo de definición del servicio.

### Cloud Service Role
Compuesto por los archivos de la aplicación y los archivos de configuración.

- **Web Role para aplicaciones Front-End**
Una aplicación que va a interactuar con el Usuario. Proporciona un servidor web IIS dedicado para hospedar aplicaciones web.
- **Worker Role para aplicaciones Back-End**
Las aplicaciones pueden ejecutar tareas largas de forma asíncrona e independiente de la interacción con el usuario. Similares a los servicios Windows tradicionales.  

### Cloud Services

Se basa en máquinas virtuales, la tecnología ofrece 2 opciones. Un rol puede tener muchas instancias definidas en el archivo de configuración del servicio.

- **Instancias Web Role**
Máquina virtual sobre la cual el código de la aplicación junto con su configuración se esta ejecutando. Cada instancia ejecuta una variante de Windows Server con IIS.

- **Instancias Worker Role**
Se ejecutan en la misma variante de Windows Server sin IIS.

Al crear un **Cloud Service** se pueden definir varios roles para distribuir el procesamiento de una aplicación de **N-Niveles** o **N-Capas** permitiendo un escalamiento flexible de la misma. Cada una de las **Máquinas Virtuales** tiene su propia dirección IP dentro del Centro de Datos de Microsoft, esta se conoce como una **dirección IP directa**. Las peticiones se balancean a cada una de las máquinas virtuales, pero los usuarios acceden desde una **dirección pública virtual VIP** proporcionando tolerancia a fallos.

![Cloud Services](https://user-images.githubusercontent.com/2154886/141399419-96ada37e-e31a-4063-adb8-7d31fc6db142.png)

### CARACTERÍSTICAS DE CLOUD SERVICES

- Permiten crear aplicaciones y APIs de alta disponibilidad (99,95%) y escalabilidad infinita
- Permiten centrarse en la aplicación y olvidarse de la infraestructura
- Proporcionan dos ambientes: Ensayo y Producción
- Permiten desarrollar APIs en internet para una amplia gama de dispositivos
- Ayudan a crear arquitecturas de nubes modernas

3. **MÁQUINAS VIRTUALES -> IaaS (Se paga por hora de Ejecución)**

Tenemos la opción de seleccionar el Sistema Operativo, permite crear y utilizar máquinas virtuales en la nube. Es un servidor en la nube que puede ser controlado y administrado. Se pueden crear mediante el portal de administración de Windows Azure o mediante la API basada en Rest Windows Azure Service Management (Herramientas de Script en Windows, Linux y MAC).
Para crear una máquina virtual se requiere seleccionar un disco duro virtual como imagen de la máquina virtual, estos son almacenados en el Blob de Windows Azure, una imagen es un disco duro virtual que se utiliza como plantilla para crear un nueva máquina virtual, es una plantilla porque no tiene una configuración especial (nombre de la computadora o la configuración de usuarios). Al crear una máquina virtual utilizando una imagen, un disco de SO es creado automáticamente para la nueva máquina virtual. 
Para crear una máquina virtual también se puede utilizar un disco duro virtual que pueda servir de arranque y montarse como una versión de SO. Un disco es una versión de una imagen que puede ser ejecutado, después de que una imagen es provisionada esta se convierte en un **Disco**. 

Para poder seleccionar un disco duro virtual tenemos 2 opciones:
- Crear y subir hacia Windows Azure un archivo VHD que contiene la imagen
- Utilizar algún disco duro virtual proporcionado por Microsoft por medio de la galería de máquinas virtuales

Los discos duros de la galería incluyen Windows Server 2008 Release 2, Windows Server 2008 Release 2 con SQL Server y Windows Server 2012. La galería también contiene imágenes Linux(Suse, Ubuntu). Estos discos se viven actualizando, mas sin embargo al montar una máquina virtual nosotros somos los responsables de las actualizaciones de la misma

![Windows Azure Virtual Machines](https://user-images.githubusercontent.com/2154886/141400022-ef92e598-9e08-4515-8d82-1eed05996357.png)

![Tamaños de máquinas virtuales](https://user-images.githubusercontent.com/2154886/141400299-abd33629-def1-42c5-a938-23a89c183b68.png)

### Tolerancia a fallas
La plataforma inicia inmediatamente la misma máquina virtual en otro servidor si el actual falla.
Los discos duros son replicados en uno o varios centros de datos.

Para crear una máquina virtual tenemos 2 opciones:
- **Standalone VMs** Una máquina virtual que se ejecuta de forma independiente. Cada máquina virtual tiene su propia dirección IP pública.
- **VMs en un Cloud Service** Se ejecutará junto con otras máquinas virtuales. Recomendable para una aplicación de múltiples Niveles (Interfaz Web, Negocio, Base de Datos). Comparten la misma dirección IP pública. Beneficio del Balance de carga de trabajo proporcionado por Windows Azure, permitiendo que las peticiones de los Usuarios sean atendidas por todas las máquinas virtuales en el grupo.

![Agrupamiento de Máquinas Virtuales: Cloud Services](https://user-images.githubusercontent.com/2154886/141400483-d3c582c8-e0a4-40df-8793-d82812cb71bd.png)

Las Máquinas virtuales en el grupo pueden comunicarse entre ellas sobre la red local del Centro de datos de Windows Azure, de igual forma las MVs en el mismo Cloud Service pueden ser agrupadas en uno o más conjuntos de disponibilidad. Al agrupar las MVs en un  conjunto o grupo de disponibilidad Windows Azure distribuye las máquinas virtuales a través del Centro de Datos para que estas no sean ubicadas en el mismo Servidor o incluso en el mismo Rack de Servidores (en el mismo dominio de fallo), por lo cual si alguno de los Servidores o Rack de Servidores en el Centro de Datos llega a fallar no se vería afectado el funcionamiento del Cloud Service al estar disponible en las otras máquinas virtuales en los otros Servidores físicos (Otro dominio de fallo).

### Escenario de Uso
- **Máquinas Virtuales para desarrollo y pruebas**
Los desarrolladores pueden hacer uso de Máquinas Virtuales con configuraciones específicas para crear aplicaciones de manera sencilla y económica, utilizarlas y eliminarlas cuando ya no sean requeridas.
- **Ejecución de aplicaciones en la nube**
Ejecutar aplicaciones en la nube cuando exista alta demanda de ellas es un ahorro económico. Como estan en la Nube se pueden crear cuando se necesiten y eliminarlas cuando ya no son requeridas.
- **Extensión del Centro de Datos propio hacia la nube**
Con Windows Azure podemos crear redes virtuales para hacer que las máquinas virtuales en la Nube aparezcan como parte de nuestra propia red corporativa, esto permite que aplicaciones como SharePoint puedan ser utilizadas en nuestra empresa de una manera sencilla y económica sin tener que realizar grandes inversiones en nuestro Centro de Datos
- **Recuperación de Desastres**
Si nuestro Centro de Datos deja de funcionar por algún desastre podemos crear máquinas virtuales en la Nube para ejecutar aplicaciones esenciales y detenerlas cuando nuestro Centro de Datos vuelva a funcionar.

![Ejecutando una aplicación con SQL Server](https://user-images.githubusercontent.com/2154886/141400821-5d86d46c-5c02-4d52-abf6-96fa32dee32e.png)
