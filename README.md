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

