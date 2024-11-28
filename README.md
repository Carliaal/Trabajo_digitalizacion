# Trabajo digitalizacion

Carla García Pacheco(Carliaal)

- [Trabajo digitalizacion](#trabajo-digitalizacion)
  - [1. Supuesto elegido](#1-supuesto-elegido)
    - [Problema B](#problema-b)
  - [2. Identificación del Modelo de Servicio Adecuado](#2-identificación-del-modelo-de-servicio-adecuado)
    - [2.1 Breve resumen de los diferentes Modelos de Servicio](#21-breve-resumen-de-los-diferentes-modelos-de-servicio)
      - [2.1.1. Iaas(Infraestructura como servicio)](#211-iaasinfraestructura-como-servicio)
      - [Ejemplos](#ejemplos)
      - [2.1.2. Paas(Plataforma como Servicio)](#212-paasplataforma-como-servicio)
      - [Ejemplos](#ejemplos-1)
      - [2.1.3. FaaS (Función como Servicio)](#213-faas-función-como-servicio)
      - [Ejemplos](#ejemplos-2)
      - [2.1.4.CaaS (Contenedor como Servicio)](#214caas-contenedor-como-servicio)
      - [Ejemplos](#ejemplos-3)
  - [2.2. Elección del Modelo de Servicio adecuado](#22-elección-del-modelo-de-servicio-adecuado)
  - [3. Investigación de Plataformas](#3-investigación-de-plataformas)
  - [4. Análisis Económico](#4-análisis-económico)
  - [5. Conclusión](#5-conclusión)

## 1. Supuesto elegido

### Problema B

Una empresa de desarrollo de software debe construir y desplegar una nueva aplicación web en el menor tiempo posible, con la necesidad de disponer un sistema que permita alojar backend, frontend y conectarse con una base de datos PostgreSQL. No desea preocuparse por la gestión de servidores ni por la infraestructura subyacente.

## 2. Identificación del Modelo de Servicio Adecuado

### 2.1 Breve resumen de los diferentes Modelos de Servicio

#### 2.1.1. Iaas(Infraestructura como servicio)

Se resume en el alquiler del acceso a servicios en la nube. El cliente tiene acceso a servicios básicos como pueden ser servidores, redes, almacenamiento y de más servicioes que puedan ser esenciales para él. Este solo tiene el control del sistema operativo y el software pero no puede interferir en cuanto al hardware.

#### Ejemplos

- Microsoft Azure
- Oracle Claud
- Digital Ocean

#### 2.1.2. Paas(Plataforma como Servicio)

Proporciona una plataforma completa en la cual permite al cliente desarrollar, gestionar y desplegar aplicaciones sin tener que preocuparse acerca del software y del hardware ya que este es aportado por la empresa la cual ofrece el servicio. Los usuarios se centrar en escribir y ejecutar código con las herramientas aportadas.

#### Ejemplos

- Google App Engine
- Red Hat OpenShift
- Heroku

#### 2.1.3. FaaS (Función como Servicio)

Es un modelo de computación en la nube que facilita a los usuarios la ejecución individual de fragmentos de código o funciones, evitando la administración de servidores o infraestructura. Esta perspectiva se ubica dentro del término "sin servidor", en el que la nube se ocupa de gestionar la infraestructura, la escalabilidad y el mantenimiento.

#### Ejemplos

- Azure Functions
- IBM Cloud Functions
- AWS Lambda

#### 2.1.4.CaaS (Contenedor como Servicio)

Es un modelo de servicio en la nube que simplifica a los usuarios la implementación, administración y expansión de aplicaciones a través de la utilización de contenedores, evitando la necesidad de preocuparse por la infraestructura relacionada. Los contenedores facilitan la agrupación de las aplicaciones y sus dependencias, asegurando que operen de manera uniforme en diferentes ambientes, ya sea en servidores locales o en la nube.

#### Ejemplos

- Azure Kubernetes Service
- Google Kubernetes Engine
- Amazon Elastic Kubernetes Service

## 2.2. Elección del Modelo de Servicio adecuado

En este caso, consideramos que el modelo de servicio que mejor se adapta a las necesidades del usuario es el modelo PaaS (Plataforma como Servicio), ya que, como se explicó anteriormente, las plataformas PaaS ofrecen un servicio en la nube que permite al usuario desplegar su aplicación sin tener que preocuparse por el hardware, el software del servidor ni por el mantenimiento de la infraestructura subyacente.

Estas plataformas proporcionan un entorno de desarrollo ideal para gestionar tanto el backend como el frontend, además de ofrecer herramientas como bases de datos, que es uno de los requerimientos del cliente en este caso. También permiten al usuario centrarse únicamente en escribir y desarrollar el código, tal como lo ha solicitado el cliente.

En resumen, PaaS es la mejor opción si el usuario necesita un entorno de trabajo ya preparado y listo para empezar a desarrollar sin tener que preocuparse por el mantenimiento de la infraestructura.

## 3. Investigación de Plataformas

### 3.1. Plataformas que ofrecen soluciones para PaaS

Estas son algunas de las mejores plataformas para abordar soluciones para PaaS (Plataforma como Servicio). La plataforma como Heroku es ideal para principiantes o proyectos pequeños. Para empresas con necesidades más avanzadas, Google App Engine o AWS Elastic Beanstalk son excelentes opciones y por último, si se requiere flexibilidad empresarial y un enfoque en Kubernetes, Red Hat OpenShift es la mejor alternativa.

#### 3.1.1. Google App Engine

#### Características:

- Compatible con lenguajes como Python, Java, Node.js, PHP, Go y más.
- Escalado automático según la demanda.
- Integración nativa con servicios de Google Cloud como Cloud (PostgreSQL).
- Ideal para aplicaciones basadas en microservicios.

#### Costes:

- Nivel gratuito: Incluye 28 horas/vCPU por día y 1 GB de almacenamiento.
- Precios escalables en función del uso, empezando por $0.046/vCPU-hora.

#### Facilidad de implementación:

- Documentación clara y una interfaz de usuario intuitiva.
- Opciones avanzadas para configuraciones personalizadas, pero puede requerir conocimientos básicos de Google Cloud Platform.

#### 3.1.2. Heroku

#### Características:

- Compatible con múltiples lenguajes de programación y frameworks (Ruby Python, Java, Node.js, Scala, etc.).
- Ofrece "addons" para integrar herramientas como bases de datos, cachés y monitoreo.
- Escalado fácil mediante el sistema de "dynos".

#### Costes:

- Nivel gratuito: Incluye 550-1,000 horas al mes con 512 MB de RAM.
- Planes de pago desde $7/mes por un dyno estándar.

#### Facilidad de implementación:

- Muy sencilla para desarrolladores, con un enfoque minimalista.
- Despliegue directo mediante Git y una curva de aprendizaje muy baja.

#### 3.1.3. Red Hat OpenShift

#### Características:

- Basado en Kubernetes, enfocado en aplicaciones empresariales y microservicios.
- Compatible con PostgreSQL y otras bases de datos.
- Ofrece integración con CI/CD para despliegues continuos.

#### Costes:

- Planes a partir de $50/mes por desarrollador (plataforma online).
- OpenShift Origin (versión gratuita) disponible para instalaciones locales.

#### Facilidad de implementación:

- Más técnica que Heroku, requiere conocimientos básicos de contenedores y Kubernetes.
- Ideal para equipos con experiencia técnica avanzada.

#### 3.1.4. Microsoft Azure App Service

#### Características:

- Soporte para múltiples lenguajes y frameworks (Python, .NET, Node.js, PHP, etc.).
- Integración con servicios de Azure como bases de datos, IA y DevOps.
- Escalado automático y balanceo de carga.

#### Costes:

- Plan gratuito con 1 GB de almacenamiento.
- Precios desde $0.013/hora por instancias básicas.

#### Facilidad de implementación:

- Documentación completa y soporte robusto.
- Requiere conocimientos de Azure, pero es accesible para desarrolladores experimentados.

#### 3.1.5. AWS Elastic Beanstalk

#### Características:

- Compatible con lenguajes como Java, Python, PHP, Ruby, Node.js, y .NET.
- Gestión automatizada de infraestructura, incluida escalabilidad y monitoreo.
- Amplia integración con otros servicios de AWS como RDS (PostgreSQL).

#### Costes:

- Gratis en el nivel AWS Free Tier (750 horas al mes durante el primer año).
- Los costos dependen de los recursos subyacentes (EC2, S3, RDS, etc.).

#### Facilidad de implementación:

- Muy flexible, pero puede ser abrumador para principiantes.
- Ofrece una experiencia de "configuración y olvido" para quienes ya trabajan con AWS.

#### Comparativa de plataformas:

A continuación veremos una tabla, a modo resumen, destanco las caracteriasticas mas relevantes para las empresas.

#### Comparativa de plataformas

|      Plataforma       | Facilidad de implementación | Costes iniciales | Escalabilidad | Soporte para PostgreSQL |
| :-------------------: | :-------------------------: | :--------------: | :-----------: | :---------------------: |
|   Google App Engine   |            Alta             |       Bajo       |     Alta      |           Sí            |
|        Heroku         |          Muy Alta           |       Bajo       |     Media     |           Sí            |
|   Red Hat OpenShift   |            Media            |      Medio       |   Muy alta    |           Sí            |
|    Microsoft Azure    |            Alta             |       Bajo       |     Alta      |           Sí            |
| AWS Elastic Beanstalk |            Media            |       Bajo       |   Muy alta    |           Sí            |

### 3.2. Mejores Plataformas

En este apartado hemos destacado las mejores plataformas que ofrecen soluciones PaaS (Plataforma como Servicio), para que tu como empresa no tengas la necesidad de estar investigando. A continuación veras las mejores opciones detalladas y con sus características. También veremos algunas desventajas para que sean ustedes como empresa los que tomen la decisión de elegir la Plataforma como Servicio.

#### 3.2.1. Google App Engine

#### Características destacadas:

- Entorno completamente administrado: No necesitas preocuparte por el aprovisionamiento ni la gestión de servidores. Todo el escalado, actualizaciones y balanceo de carga se manejan automáticamente.
- Lenguajes soportados: Admite Python, Java, Node.js, PHP, Ruby, Go y .NET. También permite personalizar entornos a través de contenedores Docker.
- Integración con Google Cloud: Compatible con Cloud SQL (PostgreSQL), BigQuery, Cloud Storage y otras soluciones del ecosistema de Google.
- Alta disponibilidad: Ofrece escalabilidad automática y despliegues regionales para garantizar el rendimiento incluso con picos de demanda.

#### Ventajas destacadas:

- Tiempo de configuración reducido gracias a sus herramientas de desarrollo listas para usar.
- Escalado automático y precios flexibles basados en el uso real.
- Excelente para empresas que ya utilizan otros servicios de Google Cloud.

#### Desventaja:

- Dependencia del ecosistema de Google Cloud, lo que puede dificultar la migración a otra plataforma.
- Configuración avanzada (como entornos personalizados) puede ser compleja.

#### Costes:

- Nivel gratuito: 28 horas/vCPU diarias y 1 GB de almacenamiento, ideal para pruebas o aplicaciones pequeñas.
- Costes adicionales:
- - $0.046/vCPU-hora.
- - $0.12/GB-mes de almacenamiento.

#### Facilidad de implementación:

- Documentación robusta y fácil de seguir.
- Despliegue simplificado mediante herramientas como el SDK de Google Cloud.
- Ideal para desarrolladores con conocimientos básicos de cloud computing.

#### 3.2.2. Heroku

#### Características destacadas:

- Plataforma centrada en desarrolladores: Diseñada para facilitar el despliegue, gestión y escalado de aplicaciones de forma sencilla.
- Soporte multilenguaje: Compatible con Ruby, Python, Java, Node.js, Scala, Clojure, PHP y Go.
- Extensible con "addons": Integra herramientas como bases de datos PostgreSQL, cachés (Redis), almacenamiento y herramientas de monitoreo como New Relic.
- Despliegue simple: Los desarrolladores pueden desplegar aplicaciones directamente desde Git con comandos simples.

#### Ventajas destacadas:

- Curva de aprendizaje muy baja, ideal para desarrolladores nuevos o equipos pequeños.
- Implementación extremadamente rápida.
- Amplia gama de "addons" que permiten agregar funcionalidades avanzadas sin complejidad.

#### Desventaja:

- Costos más altos en comparación con otras plataformas a medida que el proyecto crece.
- Menor control y flexibilidad en la configuración avanzada en comparación con plataformas más técnicas.

#### Costes:

- Nivel gratuito: Entre 550 y 1,000 horas de procesamiento mensuales, con 512 MB de RAM.
- Planes de pago:
- - Dynos estándar: Desde $7/mes.
- - Bases de datos PostgreSQL: Desde $9/mes para bases básicas.

#### Facilidad de implementación:

- Muy alta: Documentación clara y herramientas integradas para desarrolladores.
- Despliegue automatizado y configuración mínima.
- Ideal para equipos pequeños o proyectos con plazos ajustados.

#### 3.2.3. Red Hat OpenShift

#### Características destacadas:

- Basado en Kubernetes: Ofrece contenedores administrados y listos para su uso. Permite crear aplicaciones escalables y portátiles.
- Multinube: Puede ejecutarse en la nube pública (AWS, Azure, Google Cloud) o en instalaciones locales.
- Integración con CI/CD: Incluye herramientas de integración y entrega continua para procesos de desarrollo ágiles.
- Amplio soporte empresarial: Ideal para organizaciones grandes que requieren alta disponibilidad y soporte técnico robusto.

#### Ventajas destacadas:

- Flexibilidad y control total sobre el entorno, con soporte nativo para PostgreSQL.
- Integración avanzada con sistemas empresariales y soluciones de contenedores.
- Escalado horizontal y vertical, ideal para aplicaciones críticas.

#### Desventaja:

- Requiere conocimientos técnicos avanzados en contenedores y Kubernetes.
- Costos más altos que otras plataformas si no se utiliza adecuadamente.

#### Costes:

- OpenShift Online (público): $50/mes por desarrollador.
- OpenShift Self-Managed (on-premise): Costos dependen del tamaño del clúster y los recursos necesarios.
- Versión gratuita: OpenShift Origin, adecuada para pruebas en entornos locales.

#### Facilidad de implementación:

- Media: La configuración inicial puede ser técnica, pero está bien documentada.
- Ideal para desarrolladores o equipos con experiencia en Kubernetes.
- Amplia comunidad de soporte y recursos para aprendizaje.

#### Comparativa de plataformas

|    Plataforma     |            Ventaja principal            | Facilidad | Coste inicial |                        Recomendado para                        |
| :---------------: | :-------------------------------------: | :-------: | :-----------: | :------------------------------------------------------------: |
| Google App Engine | Escalado automático y ecosistema Google |   Alta    |     Bajo      |       Equipos que necesitan escalabilidad y simplicidad.       |
|      Heroku       |    Sencillez y rapidez de despliegue    | Muy alta  |     Bajo      | Proyectos pequeños/medianos con poco tiempo de implementación. |
| Red Hat OpenShift |   Potencia y flexibilidad empresarial   |   Medio   |     Medio     |        Empresas grandes con experiencia en Kubernetes.         |

#### Pequeña Conclusión:

Heroku es una excelente opción para una implementación rápida. Si se necesita escalabilidad avanzada, Google App Engine es más adecuado. Red Hat OpenShift destaca si el enfoque está en aplicaciones críticas y con equipos técnicos robustos.

## 4. Análisis Económico

## 5. Conclusión
