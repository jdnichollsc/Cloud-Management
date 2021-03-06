# Cloud Management
Diplomado Cloud Management de [TI Capacitación](https://ticapacitacion.com/) en 2013

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

![Utility Computing](https://user-images.githubusercontent.com/2154886/141670005-de778ff4-5fdf-4df3-9fff-04405f74ed01.png)


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

![Windows Azure Virtual Machines](https://user-images.githubusercontent.com/2154886/141670060-bf3f07f7-6bc0-4228-951b-8e2cdefb0db7.png)

![Tamaños de máquinas virtuales](https://user-images.githubusercontent.com/2154886/141400299-abd33629-def1-42c5-a938-23a89c183b68.png)

### Tolerancia a fallas
La plataforma inicia inmediatamente la misma máquina virtual en otro servidor si el actual falla.
Los discos duros son replicados en uno o varios centros de datos.

Para crear una máquina virtual tenemos 2 opciones:
- **Standalone VMs** Una máquina virtual que se ejecuta de forma independiente. Cada máquina virtual tiene su propia dirección IP pública.
- **VMs en un Cloud Service** Se ejecutará junto con otras máquinas virtuales. Recomendable para una aplicación de múltiples Niveles (Interfaz Web, Negocio, Base de Datos). Comparten la misma dirección IP pública. Beneficio del Balance de carga de trabajo proporcionado por Windows Azure, permitiendo que las peticiones de los Usuarios sean atendidas por todas las máquinas virtuales en el grupo.

![Agrupamiento de Máquinas Virtuales: Cloud Services](https://user-images.githubusercontent.com/2154886/141670111-95123c1c-5c0c-4624-bb33-e9a25b948cc2.png)

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

![Opciones configurables de caché](https://user-images.githubusercontent.com/2154886/141413635-3ad95ae6-3133-4b11-a926-d980493c1fa7.png)

## CDN

![CDN](https://user-images.githubusercontent.com/2154886/141413894-7be887c3-899e-44c9-a944-c8b2a87f02e8.png)

![Nodos CDN](https://user-images.githubusercontent.com/2154886/141413969-9a4e591b-116f-41dd-bb17-0ba638e5fb7c.png)

![Beneficios del uso de CDN](https://user-images.githubusercontent.com/2154886/141414029-39006a8f-3713-4398-8117-b50ad6f70b46.png)

## ARQUITECTURAS DE ALTA RESISTENCIA Y ESCALABILIDAD PARA LA NUBE

### Objetivos

El diseño de servicios a gran escala de alta resistencia y escalabilidad requiere elegir cuidadosamente su diseño y arquitectura.

## PROBLEMAS Y DESAFÍOS

### Teorema de CAP (Brewer)

Establece que es imposible para un Sistema de Cómputo distribuido garantizar simultáneamente 3 áreas:  
- La consistencia
- La disponibilidad
- La tolerancia a fallos
Según el teorema un sistema puede tener no más de 2 de estas características simultáneamente.
Lo mismo ocurre con aplicaciones en la nube, pero los pilares son:

![Escalabilidad, Conocimiento y Disponibilidad](https://user-images.githubusercontent.com/2154886/141414304-32f6aaee-6598-4e88-a91d-4abaebebbfc1.png)

![Objetivos Principales](https://user-images.githubusercontent.com/2154886/141414401-c0a21091-992b-4089-9216-397eb762b1ff.png)

![Diseño de aplicaciones](https://user-images.githubusercontent.com/2154886/141414486-d92083a5-ab25-4b9b-91bb-a6de44b2e5b7.png)

![Diseño con servicios especializados](https://user-images.githubusercontent.com/2154886/141414597-17434d53-0e6b-4b4d-8c0a-89e6d16cd15f.png)

![Time to market y agilismo](https://user-images.githubusercontent.com/2154886/141414744-fb371874-0e16-4bc6-a806-48eacb140513.png)

![Carga de trabajo](https://user-images.githubusercontent.com/2154886/141414845-37b600dc-f902-48b9-89a5-2b5dd5a1bea6.png)

## DISEÑANDO PARA FALLOS

![Descomposición de una E-Commerce](https://user-images.githubusercontent.com/2154886/141415057-0d86956d-d696-4749-ba4b-8d9561212aed.png)

![Descomposición por carga de trabajo](https://user-images.githubusercontent.com/2154886/141415217-9468f3c8-2acf-4cc9-a0bc-2759f129a01d.png)

![Alta disponibilidad](https://user-images.githubusercontent.com/2154886/141415329-042e925c-c944-4352-93f0-8fcfccbdd837.png)

![Los 9s](https://user-images.githubusercontent.com/2154886/141415410-5b23de46-b3be-40a7-9b60-4ef17f91b85e.png)

![Calculando el ANS (SLA)](https://user-images.githubusercontent.com/2154886/141415520-54267ceb-dfe9-4826-a8c2-089542a04781.png)

![SLA para servicios externos](https://user-images.githubusercontent.com/2154886/141415642-370f2241-3f55-43a4-a871-e1991bb81e1d.png)

![Define tus propios acuerdos de nivel de servicio](https://user-images.githubusercontent.com/2154886/141415714-a2dfa7e4-db10-4b21-b4eb-a068ac7d8afa.png)

![Diseño para fallos](https://user-images.githubusercontent.com/2154886/141415927-20e262c1-bbbc-4c06-9150-5142c92efb81.png)

![Alcance de los Fallos](https://user-images.githubusercontent.com/2154886/141416068-82ec43be-4d7e-4c1f-93eb-bb2dac6cad6f.png)

![Manejo de errores temporales y Fallos duraderos](https://user-images.githubusercontent.com/2154886/141416153-6ffbec2f-0922-427e-898f-f010ed09b62d.png)

![Retry Policy](https://user-images.githubusercontent.com/2154886/141416319-30879f65-8e99-45b8-b241-3bded1ea61e7.png)

![Web Request Latency](https://user-images.githubusercontent.com/2154886/141416430-98a3e5fd-946d-4631-943d-07961650b622.png)

![Muestra de normas de reintentos](https://user-images.githubusercontent.com/2154886/141416527-d5e022d4-5de7-4f7c-9f8b-3cac3bcccd68.png)

### Patrón: El Disyuntor

![Patrón Disyuntor](https://user-images.githubusercontent.com/2154886/141416754-214ad575-69a8-40d8-a2ce-1ef6bfc88996.png)

![Circuit Breaker](https://user-images.githubusercontent.com/2154886/141416851-6e161d68-a350-43c8-877e-b6d2d3b86270.png)

![Circuit Breaker Fallbacks](https://user-images.githubusercontent.com/2154886/141416922-b4bbbe06-9b3a-45c3-816f-ea042177fdeb.png)

![Redundancia en el despliegue](https://user-images.githubusercontent.com/2154886/141417616-7876659f-e98f-4c27-b2c7-60ab9593a58b.png)

![Failure Points](https://user-images.githubusercontent.com/2154886/141605368-03d2b2ed-9f97-4afb-9ca1-5609c7a02eea.png)

![Failure Modes](https://user-images.githubusercontent.com/2154886/141605433-5fda3c02-9053-4749-bf96-931b001873df.png)

![Ejemplos de Modos de Falla](https://user-images.githubusercontent.com/2154886/141605493-8820481e-644a-418b-aa4c-ba4490944c66.png)


## DISEÑANDO PARA OPERACIONES

Tener una visibilidad de los sistemas que se están ejecutando, esto mediante la telemetría.
Como los Servicios Web, es importante tener monitoreo

![Capturando la información sobre el servicio](https://user-images.githubusercontent.com/2154886/141605965-cd28a939-3437-45a9-a74c-9712ac259d1b.png)

![Capturando la información con C#](https://user-images.githubusercontent.com/2154886/141606101-ef294ac3-bf5b-41f4-9389-1c16f85f4482.png)

![Opciones de telemetría](https://user-images.githubusercontent.com/2154886/141606154-884f5271-0dc9-4c95-ae59-6d51a7e6e15b.png)

## DISEÑANDO PARA ENTENDER LA APP

![Diseñando para entender la aplicación](https://user-images.githubusercontent.com/2154886/141606201-535aa966-4e98-48b6-9df6-2d96747a8f57.png)

![Definir ALM](https://user-images.githubusercontent.com/2154886/141606285-78892ea7-1b29-4079-9ba9-7176f295592a.png)

![Actualizando la configuración](https://user-images.githubusercontent.com/2154886/141606342-4a4d88d3-528b-4d51-a817-95df5e5d4738.png)

![Actualizando los servicios](https://user-images.githubusercontent.com/2154886/141606402-66f197ff-3d4b-4359-b246-f168edd6f767.png)

![Health model](https://user-images.githubusercontent.com/2154886/141606532-0aacecf4-b5fa-45a7-8a26-0b0364988400.png)

![Flujo de trabajo para la solución de problemas](https://user-images.githubusercontent.com/2154886/141606584-2fe8af92-57c1-40ed-9d92-f713e41928a5.png)

![Arquitectura a prueba de fallos](https://user-images.githubusercontent.com/2154886/141606657-73ffaf1f-a0da-4c0d-b451-2daeef29f617.png)

## DISEÑANDO PARA ESCALAR

![Escalabilidad](https://user-images.githubusercontent.com/2154886/141606825-8678f1fe-9f82-4ac2-a712-73b829878982.png)

![Unidades de Escalabilidad](https://user-images.githubusercontent.com/2154886/141606863-b221666c-bbf3-4253-ad5e-2caf053ee77c.png)

![Workloads](https://user-images.githubusercontent.com/2154886/141607091-1fe95f75-2081-485e-b9f0-973cb01b8e58.png)

![Partición de Datos](https://user-images.githubusercontent.com/2154886/141607136-6fb6b6d8-b102-4126-ba68-83d0e7019677.png)

![Las 3Vs](https://user-images.githubusercontent.com/2154886/141607217-3c40cdd1-e93f-4598-bf8d-834512540252.png)

![Capacidad de consulta](https://user-images.githubusercontent.com/2154886/141607310-29b2d4a1-33d6-425f-8158-68dec930413d.png)

![Partición horizontal](https://user-images.githubusercontent.com/2154886/141607388-80ede364-376f-4447-887a-dec9d1294511.png)

![Partición vertical](https://user-images.githubusercontent.com/2154886/141607434-e4319cc7-ece8-4f70-b5cf-d5083e5c3d03.png)

![Partición hibrida](https://user-images.githubusercontent.com/2154886/141607461-1e426cc3-b7f5-4dcb-a585-f1ef8e571e61.png)

![Windows Azure Caching](https://user-images.githubusercontent.com/2154886/141607516-3b0a759e-8b79-414c-a2c2-76ef8c00ff64.png)

![CDN](https://user-images.githubusercontent.com/2154886/141607564-dd5b5bb9-1be8-4002-afb2-6070eb92decb.png)

![Azure Cache](https://user-images.githubusercontent.com/2154886/141607618-1320e9da-9bed-4e58-b85d-220f2e38439c.png)

## CONECTIVIDAD

Extender una red local para incluir servicios hospedados en Windows Azure y servidores locales a través de las redes virtuales de Windows Azure. Windows Azure Traffic Manager se emplea para administrar y equilibrar la cantidad de tráfico entrante.

1. **Red Virtual**:

Windows Azure Virtual Network proporciona enlaces seguros con una infraestructura local. Los administradores de infraestructura pueden extender redes locales hacia la nube con control sobre la topología de red incluyendo configuración de DNS y rangos de direcciones IP para las máquinas virtuales.

![Windows Azure Virtual Network](https://user-images.githubusercontent.com/2154886/141607897-25f3b3de-7265-4e6b-836b-5b8dfbb60f78.png)

![Principales usos](https://user-images.githubusercontent.com/2154886/141608000-d19759c7-dbb1-4c03-9a0e-ff951e681408.png)

![Características soportadas por Virtual Network](https://user-images.githubusercontent.com/2154886/141608077-caca91f4-ee7d-464c-87aa-660740deeb4f.png)

![Beneficios](https://user-images.githubusercontent.com/2154886/141608426-65d82b40-f0ea-4fc6-8541-abc70b59be27.png)


2. **Windows Azure Traffic Manager**

Traffic Manager es una solución para balance de carga de trabajo que permite la distribución de tráfico entrante de diferentes Cloud Services en una Suscripción de Windows Azure independientemente de su ubicación física.

![Windows Azure Traffic Manager](https://user-images.githubusercontent.com/2154886/141665846-02dc2f3a-2c03-4182-9775-8a2b61944b60.png)

![Métodos de balance de carga](https://user-images.githubusercontent.com/2154886/141665934-5f506f1e-6795-4f09-a433-b72466ae807b.png)

![Usos de Traffic Manager](https://user-images.githubusercontent.com/2154886/141666013-be8f09fe-ef94-4991-b392-b60f4f3e5942.png)

![Recursos de Traffic Manager](https://user-images.githubusercontent.com/2154886/141666044-cf72e8b0-a774-4571-9bc1-34767f0e68d5.png)

![SQL Server Reporting Services](https://user-images.githubusercontent.com/2154886/141668915-26df953c-f41a-48cc-b600-38b2100c06e3.png)

![SQL Azure Reporting](https://user-images.githubusercontent.com/2154886/141669035-c2a68f09-708f-46db-a22c-64da9ca64f1e.png)

![SSRS vs SQL Azure Reporting](https://user-images.githubusercontent.com/2154886/141669126-8c1291fa-4f9e-40ca-9a64-6b5c8732df8f.png)

![Escenarios para usar SQL Azure Reporting](https://user-images.githubusercontent.com/2154886/141669254-fa91a8ee-80d2-4c17-99c2-6aad32c57d13.png)

![Arquitectura](https://user-images.githubusercontent.com/2154886/141669291-c1a6107d-bc52-4759-8bb2-fc3d71a79631.png)

![Modelo de Seguridad](https://user-images.githubusercontent.com/2154886/141669421-391256ea-8ad6-49f7-8ced-3aca25021bdd.png)


## IDENTITY

La administración de acceso e identidad es una tarea importante tanto para administradores de sistema como desarrolladores de aplicaciones. Active Directory permite a los administradores utilizar el conjunto de servicios de Identidad incluyendo el proceso de inicio de sesión, autenticación y federación. Permite también realizar consultas sobre los objetos del directorio tales como usuarios y grupos, así como integrar Windows Azure Active Directory con Windows Server Active Directory ejecutándose On-Premise. Active Directory permite a los desarrolladores implementar un inicio de sesión único para las aplicaciones empresariales y del tipo Software como Servicio.

![Windows Azure Active Directory](https://user-images.githubusercontent.com/2154886/141669541-16866e11-6668-4589-99c5-4abcbca7447f.png)

**Windows Azure AD Graph** es un innovador gráfico social de empresa que proporciona una sencilla interfaz basada en Rest para obtener acceso a objetos tales como usuarios, grupos y roles con una vista de explorador que permite encontrar fácilmente la información y las relaciones, así como realizar operaciones CRUD. En el mundo On-premise accedemos mediante programación al Windows Server Active Directory utilizando Active Directory Service Interfaces o Bibliotecas ADO .NET, en la nube accedemos con programación al Windows Azure Active Directory utilizando Windows Azure Active Directory Graph.

![Principales usos](https://user-images.githubusercontent.com/2154886/141669697-663c4950-e639-4dce-98ca-c60937b19598.png)

Windows Azure Active Directory Access Control permite a los usuarios iniciar sesión con diferentes proveedores de identidad. Facebook, Google, Microsoft, etc.

![Recursos Active Directory](https://user-images.githubusercontent.com/2154886/141669947-08c09a65-9a1b-4248-a8a5-3eaf20fd4211.png)
