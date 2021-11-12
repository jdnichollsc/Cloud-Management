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

### Ejecutando una Granja de Sharepoint

![Ejecutando una Granja de Sharepoint](https://user-images.githubusercontent.com/2154886/141400971-ece12f21-9e6a-4063-a49a-f628a3384667.png)

**SharePoint** requiere **Active Directory**, la Organización crea controladores de dominio en la Nube utilizando Imágenes de Windows Server de la Galería o también se puede realizar On-Premise, pero debido a que SharePoint interactúa frecuentemente con el Active Directory es recomendable tener controladores de dominio en la Nube para un buen rendimiento.

![Opciones de Almacenamiento](https://user-images.githubusercontent.com/2154886/141401089-4d3478eb-1107-4e51-aeab-458f4b3c58ea.png)

1. **SQL DATABASE**

Es una tecnología que nos permite administrar datos relacionales en una Plataforma como Servicio (Paas), proporciona un Sistema de Administración de Base de Datos Relacional DBMS para Windows Azure y esta basado sobre la tecnología SQL Server.
Con una instancia SQL Database fácilmente se puede provisionar y desplegar soluciones de Bases de Datos Relacionales en la Nube y tomar ventaja de un Centro de Datos distribuido de Alta Disponibilidad, Escalabilidad, Seguridad y Confiabilidad.
No proporciona a cada cliente su propia instancia física de SQL Server, proporciona un servicio de múltiples inquilinos con un Servidor Lógico de Base de Datos SQL para cada cliente, por lo tanto todos los clientes comparten las capacidades de cómputo y almacenamiento que el servicio proporciona. Todos los datos son almacenados en 3 distintos Servidores del Centro de Datos, proporcionando una alta disponibilidad.

![SQL DATABASE](https://user-images.githubusercontent.com/2154886/141401220-a85b5ccf-49ab-49eb-ace6-00e997fb6902.png)

**SQL Data Sync** permite replicar datos entre distintos centros de datos de Windows Azure o entre centros de datos Microsoft Azure y servidores SQL Server on-premises.

![SQL Data Sync](https://user-images.githubusercontent.com/2154886/141405400-e1b2d062-88b4-41d0-aaeb-4118c7ff2c29.png)

**Reportes en las Aplicaciones Windows Azure**

![SQL Reporting](https://user-images.githubusercontent.com/2154886/141405537-376aecff-8a2b-482b-9a6b-c7b73f7b303b.png)

**Agregando cuentas de inicio de sesión y de usuario**

![Add loginuser](https://user-images.githubusercontent.com/2154886/141405922-16be3302-f2ad-4e4c-82ad-4a8e14cec1c2.png)

**Copias de Base de Datos SQL Database**

```
create database newname 
as copy of actualname 
```

> Los cambios que se hagan en nuestra base de datos durante el proceso de copiado se realizan también a la nueva base de datos.

**Para Bajar de Windows Azure SQL Database a SQL Server - Copia de Seguridad**
1. Click en Exportar. 
2. Dejar que se cree cuenta de almacenamiento de Blob. 
3. No habilitar replicación geográfica. 
4. En SQL Server, Databases, Click derecho, Import Data-Tier Application. 
5. Obtenemos los Datos de conexión en Administrar Claves del almacenamiento. 
6. Eliminar Blob para no incurrir en costos de consumo.

2. **LOCAL STORAGE**
Proporciona un área temporal de almacenamiento para una instancia de una aplicación, ejecutándose como un Cloud Service. El área de almacenamiento temporal es un directorio de sistema de archivos de la instancia de la aplicación y sólo es accesible por esa instancia, cuando la instancia reinicia los datos de Local Storage pueden perderse.

3. **WINDOWS AZURE STORAGE**
Cada una puede contener hasta 100 Terabytes de datos y por defecto se tiene hasta un límite de 5 cuentas de almacenamiento por suscripción (Se pueden pedir más). Es el más alto nivel de espacios de nombres. Proporciona almacenamiento perdurable a través de 3 principios principales:

- **BLOB STORAGE**

Proporciona un almacenamiento económico para almacenar grandes cantidades de información binaria, tales como archivos de vídeo, audio e imágenes.

![Blob Storage](https://user-images.githubusercontent.com/2154886/141408039-654ae5b9-3fe5-4681-9037-920cda738464.png)

![Componentes del Blob Storage](https://user-images.githubusercontent.com/2154886/141408214-4edecb24-0777-46b7-a345-4883c8625a0d.png)

![Block Blob](https://user-images.githubusercontent.com/2154886/141408429-a5956458-e8f4-49a6-9ba4-70523c523db4.png)

![Page Blob](https://user-images.githubusercontent.com/2154886/141408642-684358c2-610c-4479-aaa4-173b1b95a84a.png)

- **TABLE STORAGE**

Ofrece funcionalidad NoSQL a un bajo costo para aplicaciones sin requisitos de acceso a datos de una gran complejidad.

![Table Storage](https://user-images.githubusercontent.com/2154886/141410649-4b0e1469-ded8-4a97-a27b-565cba533492.png)

![Table Storage Partitions](https://user-images.githubusercontent.com/2154886/141410827-7d5ff340-bf89-46da-acaa-cf7bebaadef4.png)

![Bases de datos no relacionales](https://user-images.githubusercontent.com/2154886/141410923-10269372-f8bf-4526-a7cc-f133443d66b9.png)

![Tablas](https://user-images.githubusercontent.com/2154886/141411045-99e44106-01a3-4c62-a1b8-a80641e63dfb.png)

![Entidades](https://user-images.githubusercontent.com/2154886/141411161-ee2f9d0d-1795-412c-ac8f-ec948a85707c.png)

![Propiedades](https://user-images.githubusercontent.com/2154886/141411275-796c8779-e30c-44c7-b687-d91aa547a06f.png)

![Particiones](https://user-images.githubusercontent.com/2154886/141411363-9cdf9937-d54e-4faa-a476-46281a30e9f1.png)

Una partición es capaz de atender 500 transacciones por segundo. Una Tabla con un buen particionamiento puede procesar miles de peticiones por segundo.

![Propiedades de una partición](https://user-images.githubusercontent.com/2154886/141411553-de430990-971c-4895-8a5e-2a80fc8b831f.png)

- **QUEUE STORAGE**

![Queue Storage](https://user-images.githubusercontent.com/2154886/141411652-c53ec449-fd63-44af-88c7-28c5c02d9188.png)

> Para los 3 servicios es necesario crear una cuenta de Almacenamiento Storage Account. Los Datos pueden ser accedidos mediante APIs de código administrado o REST.

**Grupo de afinidad**: es un agrupamiento geográfico para despliegue de Cloud Services y Cuentas de Almacenamiento en Windows Azure. Al estar nuestros Servicios dentro del mismo Centro de Datos se evitan costos de **ancho de banda** porque no generan tráfico entre distintos Centros de Datos. Puede mejorar el rendimiento del servicio al ubicar las cargas de trabajo de los Servidores en el mismo Centro de Datos o cerca de los clientes que lo requieran.

**Windows Azure** proporciona redundancia local de almacenamiento, **Locally Redundant Storage o LRS** la cual permite alta durabilidad y disponibilidad de almacenamiento dentro de una simple ubicación. En la redundancia local los datos son replicados 3 veces dentro del mismo centro de Datos, en Windows Azure todo el almacenamiento es localmente redundante.
Para adicionar durabilidad podemos activar la replicación geográfica **Geo Redundant Storage o GRS** la cual proporciona protección de los datos al replicarlos en una ubicación secundaria de la misma región, esto permite una tolerancia a fallos en caso de que la aplicación primaria tenga algún problema. GRS es implementada mediante una característica llamada **Geo-Replication**.

![Windows Azure Service Bus](https://user-images.githubusercontent.com/2154886/141412023-31360e5f-c3b4-4250-9173-b4f0a9ce3d9a.png)

![Uso de Service Bus](https://user-images.githubusercontent.com/2154886/141412150-2bda68b6-3847-4d4f-8dd0-9277c6a2b0af.png)

![Estilos de Comunicación](https://user-images.githubusercontent.com/2154886/141413293-ee3fac0e-13b5-4975-9373-685c937af47f.png)

![Windows Azure Service Bus](https://user-images.githubusercontent.com/2154886/141412470-a52e4fdd-62bf-421b-a505-03bdf90e22ce.png)

![Service Bus Development](https://user-images.githubusercontent.com/2154886/141412529-53776237-1842-4c8e-a9a2-a3e8d1049b81.png)


## CACHING

Permite que podamos acercar a los usuarios la información que necesiten proporcionándoles una gran experiencia de respuesta en cualquier parte del mundo. Los servicios de almacenamiento en caché de Windows Azure permiten construir aplicaciones altamente responsivas y escalables mediante el acercamiento de los datos a los usuarios que lo necesitan. Windows Azure también proporciona caché en memoria que permite almacenar los datos de la aplicación en memoria para mejorar el rendimiento, el tiempo de respuesta y la escalabilidad.

![Windows Azure Caching](https://user-images.githubusercontent.com/2154886/141412776-7ac5e1b3-fa1a-43bf-9000-60162e460f1f.png)

![Topologías de Despliegue](https://user-images.githubusercontent.com/2154886/141412857-bcd69e1e-9d0d-47ca-87c2-84f0baded4f9.png)

![Características de Windows Azure Caching](https://user-images.githubusercontent.com/2154886/141412939-a97a7cad-551b-4078-91e4-edee1a270983.png)

![Ventajas de Windows Azure Caching](https://user-images.githubusercontent.com/2154886/141413129-4e8c0162-c61b-4abc-b836-4a37949c9637.png)

![Ventajas de Windows Azure Caching](https://user-images.githubusercontent.com/2154886/141413526-ca8cf39e-9977-4e3f-b501-71615e0ff6e2.png)
