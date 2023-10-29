# Problema planteado

## Teniendo en cuenta la aplicación de PetClinic, resolver las siguientes preguntas:

### 1. Que recursos web de Azure utilizarían para llevar a producción esa aplicación (Enumere todos los recursos que considere necesarios, la idea es atender personas que se encuentran en Alemania, 10000 Usuarios concurrentes. La aplicación debe estar disponible 24/7 todos los días del año)

### 2. Cuanto sería el presupuesto mensual de los recursos a necesitar.

## Solución

### Recursos a usar para llevar la aplicación producción junto con su precio mensual:

> #### 1. Azure App Service: Para alojar la aplicación web, 8 instancias X mes, con un plan de ahorro de 3 años más unas instancias reservadas por 3 años = 1868 USD.

> #### 2. Azure SQL Database: Para almacenar la información de los usuarios y la aplicación, 440 USD.

> #### 3. Azure Redis Cache: Para mejorar el rendimiento de la aplicación al almacenar en caché los datos comúnmente utilizados, 729 USD.

> #### 4. Azure Logic Apps: Para crear flujos de trabajo automatizados y escalables entre aplicaciones y servicios, 359 USD.

> #### 5. Azure Active Directory (AD): Para la autenticación y autorización de usuarios, 300 USD.

> #### 6. Azure Traffic Manager: Para poder distribuir el tráfico de red de manera óptima a los servicios en regiones globales, mientras se asegura un alto rendimiento y disponibilidad, 33,74 USD.

> #### 7. Azure Monitor and Application Insights: Para poder monitorear el rendimiento y usa de la aplicación, 47,53 USD.

> #### 8. Azure Storage: Para almacenar los datos no estructurados como imágenes, videos, archivos de registros, copias de seguridad, etc. Con un precio de 196,17 USD.

> #### 9. Azure Content Delivery Network (CDN): Para entregar contenido de alta banda ancha y videos a los usuarios finales, 343,04 USD.

> #### 10. Azure DevOps: Para planificar proyectos más inteligentes, colaborar y entregar más rápido con un conjunto de servicios modernos de desarrollo, 965 USD.

> #### 11. Azure Security Center: Para fortalecer la postura de seguridad y proteger contra amenazas, aquí no nos permite elegir Alemania así que quedara en East US 2 = 200 USD.

> #### 12. Azure Cost Management and Billing: Para realizar un seguimiento y controlar los costos de los recursos de Azure, este nos sale de gratis si usamos Azure.

### Y el en total por todos estos servicios, tendremos que pagar **5214,48 USD por mes**, sería lo que nos costaría mantener la Aplicación web en el ambiente de producción.
