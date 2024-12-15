# Trabajo digitalizacion

## Elección Estratégica del Modelo de Servicio en la Nube

![cloud computing](data:image/jpeg;base64,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)

## Miembros del grupo

| Primer miembro                                                                       | Segundo miembro                                                                          |
| ------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------- |
| Carla García Pacheco [@Carliaal](https://github.com/Carliaal/Trabajo_digitalizacion) | Rodrigo García Delgado [@Rodrigo-44](https://github.com/Carliaal/Trabajo_digitalizacion) |

## Índice

- [Trabajo digitalizacion](#trabajo-digitalizacion)
  - [Elección Estratégica del Modelo de Servicio en la Nube](#elección-estratégica-del-modelo-de-servicio-en-la-nube)
  - [Miembros del grupo](#miembros-del-grupo)
  - [Índice](#índice)
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
    - [3.1. Google App Engine](#31-google-app-engine)
      - [Explicación:](#explicación)
      - [Características a destacar:](#características-a-destacar)
        - [Compatibilidad multilenguaje:](#compatibilidad-multilenguaje)
        - [Escalado automático:](#escalado-automático)
        - [Monitoreo y diagnóstico:](#monitoreo-y-diagnóstico)
        - [Entornos de ejecución:](#entornos-de-ejecución)
        - [Integración con Google Cloud:](#integración-con-google-cloud)
      - [Facilidad de implementación:](#facilidad-de-implementación)
    - [3.2. Heroku](#32-heroku)
      - [Explicación:](#explicación-1)
      - [Características:](#características)
        - [Soporte para múltiples lenguajes de programación:](#soporte-para-múltiples-lenguajes-de-programación)
        - [Arquitectura basada en Dynos](#arquitectura-basada-en-dynos)
        - [Despliegue sencillo y automatizado](#despliegue-sencillo-y-automatizado)
        - [Complementos y extensiones](#complementos-y-extensiones)
        - [Escalabilidad sencilla](#escalabilidad-sencilla)
        - [Integración con servicios externos](#integración-con-servicios-externos)
        - [Herramientas de monitoreo y diagnóstico](#herramientas-de-monitoreo-y-diagnóstico)
        - [Herramientas de monitoreo y diagnóstico](#herramientas-de-monitoreo-y-diagnóstico-1)
      - [Facilidad de implementación:](#facilidad-de-implementación-1)
      - [3.3. AWS Elastic Beanstalk](#33-aws-elastic-beanstalk)
      - [Explicación:](#explicación-2)
      - [Características:](#características-1)
        - [Despliegue sencillo y automatizado](#despliegue-sencillo-y-automatizado-1)
        - [Soporte para Múltiples Lenguajes](#soporte-para-múltiples-lenguajes)
        - [Gestión de Infraestructura](#gestión-de-infraestructura)
        - [Escalabilidad Automática](#escalabilidad-automática)
        - [Monitoreo y Métricas](#monitoreo-y-métricas)
        - [Integración con otros servicios de AWS](#integración-con-otros-servicios-de-aws)
      - [Facilidad de implementación:](#facilidad-de-implementación-2)
      - [Comparativa de plataformas](#comparativa-de-plataformas)
  - [4. Análisis Económico](#4-análisis-económico)
    - [4.1. Google App Engine](#41-google-app-engine)
      - [Precios de Google App Engine](#precios-de-google-app-engine)
      - [Nivel gratuito](#nivel-gratuito)
      - [Precios de recursos adicionales](#precios-de-recursos-adicionales)
      - [Ejemplo de costos típicos (Práctico)](#ejemplo-de-costos-típicos-práctico)
        - [Aplicación web pequeña (bajo tráfico):](#aplicación-web-pequeña-bajo-tráfico)
        - [Aplicación web de tamaño mediano (tráfico moderado):](#aplicación-web-de-tamaño-mediano-tráfico-moderado)
        - [Aplicación grande (alto tráfico y entorno flexible):](#aplicación-grande-alto-tráfico-y-entorno-flexible)
    - [4.2. Heroku](#42-heroku)
        - [Precios de Heroku](#precios-de-heroku)
        - [Planes para Dynos](#planes-para-dynos)
          - [Dynos Gratis](#dynos-gratis)
          - [Dynos Hobby](#dynos-hobby)
          - [Dynos Standard](#dynos-standard)
          - [Dynos Performance](#dynos-performance)
          - [Dynos Enterprise](#dynos-enterprise)
        - [Complementos](#complementos)
          - [Heroku Postgres (Base de datos relacional):](#heroku-postgres-base-de-datos-relacional)
          - [Redis (Caché en memoria):](#redis-caché-en-memoria)
          - [Papertrail (Logs):](#papertrail-logs)
    - [4.3. Google App Engine](#43-google-app-engine)
      - [Instancias EC2 (Cómputo)](#instancias-ec2-cómputo)
      - [Almacenamiento S3](#almacenamiento-s3)
      - [Balanceadores de Carga (ELB)](#balanceadores-de-carga-elb)
      - [Bases de Datos RDS](#bases-de-datos-rds)
      - [Escalabilidad Automática](#escalabilidad-automática-1)
      - [Transferencia de Datos](#transferencia-de-datos)
      - [Herramientas Opcionales](#herramientas-opcionales)
  - [5. Conclusión](#5-conclusión)
  - [6. Webgrafía y otros enlaces](#6-webgrafía-y-otros-enlaces)
    - [6.1 NOTA](#61-nota)

## 1. Supuesto elegido

### Problema B

Una empresa de desarrollo de software debe construir y desplegar una nueva aplicación web en el menor tiempo posible, con la necesidad de disponer un sistema que permita alojar backend, frontend y conectarse con una base de datos PostgreSQL. No desea preocuparse por la gestión de servidores ni por la infraestructura subyacente.

## 2. Identificación del Modelo de Servicio Adecuado

### 2.1 Breve resumen de los diferentes Modelos de Servicio

#### 2.1.1. Iaas(Infraestructura como servicio)

Se resume en el alquiler del acceso a servicios en la nube. El cliente tiene acceso a servicios básicos, como pueden ser servidores, redes, almacenamiento y demás servicios que puedan ser esenciales para él. Este solo tiene el control del sistema operativo y el software, pero no puede interferir en cuanto al hardware.

#### Ejemplos

- Microsoft Azure
- Oracle Claud
- Digital Ocean

#### 2.1.2. Paas(Plataforma como Servicio)

Proporciona una plataforma completa en la que se permite al cliente desarrollar, gestionar y desplegar aplicaciones sin tener que preocuparse por el software y el hardware, ya que estos son proporcionados por la empresa que ofrece el servicio. Los usuarios se centran en escribir y ejecutar código con las herramientas aportadas.

#### Ejemplos

- Google App Engine
- Red Hat OpenShift
- Heroku

#### 2.1.3. FaaS (Función como Servicio)

Es un modelo de computación en la nube que facilita a los usuarios la ejecución individual de fragmentos de código o funciones, evitando la administración de servidores o infraestructura. Esta perspectiva se encuadra dentro del término 'sin servidor', en el que la nube se ocupa de gestionar la infraestructura, la escalabilidad y el mantenimiento.

#### Ejemplos

- Azure Functions
- IBM Cloud Functions
- AWS Lambda

#### 2.1.4.CaaS (Contenedor como Servicio)

Es un modelo de servicio en la nube que simplifica a los usuarios la implementación, administración y expansión de aplicaciones mediante la utilización de contenedores, evitando la necesidad de preocuparse por la infraestructura relacionada. Los contenedores facilitan la agrupación de las aplicaciones y sus dependencias, asegurando que operen de manera uniforme en diferentes entornos, ya sea en servidores locales o en la nube.

#### Ejemplos

- Azure Kubernetes Service
- Google Kubernetes Engine
- Amazon Elastic Kubernetes Service

## 2.2. Elección del Modelo de Servicio adecuado

En este caso, consideramos que el modelo de servicio que mejor se adapta a las necesidades del usuario es el modelo PaaS (Plataforma como Servicio), ya que, como se explicó anteriormente, las plataformas PaaS ofrecen un servicio en la nube que permite al usuario desplegar su aplicación sin tener que preocuparse por el hardware, el software del servidor ni por el mantenimiento de la infraestructura subyacente.

Estas plataformas proporcionan un entorno de desarrollo ideal para gestionar tanto el backend como el frontend, además de ofrecer herramientas como bases de datos, que son uno de los requerimientos del cliente en este caso. También permiten al usuario centrarse únicamente en escribir y desarrollar el código, tal como lo ha solicitado el cliente.

En resumen, PaaS es la mejor opción si el usuario necesita un entorno de trabajo ya preparado y listo para empezar a desarrollar, sin tener que preocuparse por el mantenimiento de la infraestructura.

## 3. Investigación de Plataformas

### 3.1. Google App Engine

#### Explicación:

Google App Engine (GAE) es una Plataforma como Servicio (PaaS) que permite a los desarrolladores desplegar aplicaciones web y móviles sin preocuparse por la infraestructura subyacente, ya que Google gestiona automáticamente los servidores, el escalado y el balanceo de carga.
Ofrece dos entornos: estándar, optimizado para aplicaciones ligeras con recursos limitados y tiempos de ejecución predefinidos, y flexible, que admite contenedores Docker personalizables para mayor flexibilidad.
Soporta lenguajes como Python, Java, Node.js, PHP y Go, además de integrarse con herramientas de Google Cloud como Cloud SQL (PostgreSQL/MySQL), Firestore y BigQuery.
GAE escala automáticamente según el tráfico, facilita la gestión de versiones y despliegues continuos, y garantiza alta disponibilidad con certificados SSL/TLS. Con un modelo de pago por uso, es ideal para startups y empresas que buscan lanzar aplicaciones rápidamente, aunque puede resultar costoso en proyectos intensivos y depende del ecosistema de Google.
Su implementación es sencilla gracias al Google Cloud SDK y un flujo de despliegue bien documentado que permite a los desarrolladores enfocarse en el código sin preocuparse por el mantenimiento de la infraestructura.

#### Características a destacar:

##### Compatibilidad multilenguaje:

- Soporta lenguajes como Python, Java, Node.js, PHP, Ruby, Go y .NET. También permite usar entornos personalizados mediante contenedores Docker.

##### Escalado automático:

- La plataforma ajusta los recursos (CPU, memoria) según el tráfico en tiempo real. Esto garantiza alta disponibilidad y rendimiento eficiente, especialmente en aplicaciones con tráfico variable.

##### Monitoreo y diagnóstico:

- Herramientas como Google Cloud Console y Cloud Monitoring permiten supervisar el rendimiento, identificar problemas y optimizar aplicaciones.

##### Entornos de ejecución:

- Entorno estándar: Diseñado para aplicaciones ligeras con requisitos predefinidos, tiempos de ejecución cortos y alta eficiencia.
- Entorno flexible: Ofrece mayor personalización, sin restricciones de tiempo de ejecución, y utiliza contenedores Docker personalizables.

##### Integración con Google Cloud:

- Integra servicios como Cloud SQL (bases de datos PostgreSQL/MySQL), Cloud Storage (almacenamiento), BigQuery (análisis de datos), y herramientas de inteligencia artificial de Google.

#### Facilidad de implementación:

Google App Engine permite a las empresas implementar aplicaciones de manera rápida y eficiente, eliminando la necesidad de gestionar servidores o infraestructura. Ofrece escalabilidad automática, integración con bases de datos y herramientas empresariales, alta disponibilidad y seguridad. Es ideal para aplicaciones internas, sistemas empresariales o plataformas con tráfico variable, optimizando costos y tiempo de desarrollo gracias a su facilidad de configuración y soporte para múltiples lenguajes.

### 3.2. Heroku

#### Explicación:

Heroku es una plataforma como servicio (PaaS) diseñada para simplificar el desarrollo, despliegue y gestión de aplicaciones en la nube. Lanzada inicialmente en 2007, Heroku se enfoca en permitir a los desarrolladores centrarse exclusivamente en la construcción y mejora de sus aplicaciones sin preocuparse por la infraestructura subyacente, como servidores, redes o configuraciones complejas.

Heroku opera sobre una arquitectura basada en contenedores llamada Dynos, que son entornos ligeros y escalables donde se ejecutan las aplicaciones. Los desarrolladores suben su código al sistema de Heroku, y la plataforma se encarga de todo lo demás, desde la instalación de dependencias hasta el aprovisionamiento de recursos.

Además, soporta una variedad de lenguajes populares como Ruby, Python, Java, Node.js, PHP, Scala, Go, y más, lo que lo convierte en una solución flexible para diferentes tipos de proyectos.
Es especialmente conocido por su facilidad de uso y su enfoque en la experiencia del desarrollador, ofreciendo herramientas intuitivas, un flujo de integración y despliegue continuo (CI/CD) eficiente y una gran cantidad de complementos para ampliar las capacidades de las aplicaciones. Heroku es utilizado tanto por startups como por grandes empresas gracias a su capacidad de escalado dinámico y su modelo de precios accesible.

#### Características:

##### Soporte para múltiples lenguajes de programación:

- Ruby (su lenguaje original).
- Node.js, Python, Java, PHP, Go, y Scala.

##### Arquitectura basada en Dynos

- Los Dynos son contenedores ligeros que ejecutan las aplicaciones en Heroku.
- Escalables automáticamente o de forma manual según la demanda.
- Diferentes tipos de Dynos permiten ajustar los recursos a las necesidades de la aplicación, desde Dynos gratuitos hasta opciones más robustas para producción.

##### Despliegue sencillo y automatizado

- Los desarrolladores pueden desplegar aplicaciones con un solo comando (git push heroku main) gracias a la integración con Git.
- Compatible con flujos de trabajo CI/CD, integrándose con herramientas como GitHub Actions, Jenkins, y CircleCI.

##### Complementos y extensiones

- Heroku ofrece una gran variedad de complementos en su Heroku Elements Marketplace para añadir funcionalidades como bases de datos, análisis de rendimiento, monitoreo o caché. Algunos ejemplos:
- Heroku Postgres: Base de datos relacional en la nube.
- Redis: Almacenamiento en memoria para caché y sesiones.
- Papertrail: Herramienta de monitoreo de logs.

##### Escalabilidad sencilla

- Heroku permite escalar aplicaciones de forma horizontal (añadiendo más Dynos) o vertical (aumentando los recursos por Dyno) con unos pocos clics o comandos.
- Esto lo hace ideal para aplicaciones con tráfico variable o picos inesperados.

##### Integración con servicios externos

- Heroku se conecta fácilmente con servicios en la nube como Amazon Web Services (AWS), Google Cloud, y Microsoft Azure.
- Compatible con bases de datos externas y APIs de terceros.

##### Herramientas de monitoreo y diagnóstico

- Heroku Metrics proporciona estadísticas detalladas sobre el rendimiento de las aplicaciones, como tiempo de respuesta, uso de memoria y CPU.
- Logs en tiempo real para identificar problemas y depurar errores rápidamente.

##### Herramientas de monitoreo y diagnóstico

- Heroku gestiona parches de seguridad y actualizaciones de software automáticamente.
- Cumple con estándares como PCI DSS, HIPAA, y ISO/IEC 27001.

#### Facilidad de implementación:

Heroku, como plataforma PaaS, permite a las empresas implementar aplicaciones rápidamente sin preocuparse por la infraestructura.
Su escalabilidad automática, soporte para múltiples lenguajes y fácil integración con herramientas como bases de datos y monitoreo lo hacen ideal para proyectos empresariales. Facilita el trabajo con flujos CI/CD, asegura alta disponibilidad y optimiza costos mediante su modelo de pago por uso, siendo perfecto para aplicaciones dinámicas y de rápida evolución.

#### 3.3. AWS Elastic Beanstalk

#### Explicación:

AWS Elastic Beanstalk es un servicio PaaS que facilita el despliegue y gestión de aplicaciones web en la nube. Permite a los desarrolladores subir su código, y la plataforma se encarga de configurar automáticamente la infraestructura necesaria, incluyendo servidores, balanceadores de carga y escalado automático.
Compatible con lenguajes como Java, .NET, Node.js, Python y Docker, ofrece integración con otros servicios de AWS y acceso a los recursos subyacentes para mayor control. Su modelo escalable y de pago por uso lo hace ideal para aplicaciones dinámicas y de rápido crecimiento.

#### Características:

##### Despliegue sencillo y automatizado

- Elastic Beanstalk simplifica el despliegue al permitir a los desarrolladores cargar su código y dejar que la plataforma gestione automáticamente la configuración de infraestructura, red, y servidores necesarios.

##### Soporte para Múltiples Lenguajes

- Compatible con lenguajes y entornos populares como: Java, .NET, Node.js, Python, Ruby, PHP, Go, y Docker.
- Ofrece plantillas preconfiguradas para cada entorno, facilitando el inicio rápido de proyectos.

##### Gestión de Infraestructura

- Proporciona y configura automáticamente recursos como:
- - Instancias EC2 (servidores virtuales).
- - Balanceadores de carga para distribuir el tráfico.
- - Auto Scaling para ajustar los recursos según la demanda.
- - Almacenamiento S3 para archivos estáticos y datos.

##### Escalabilidad Automática

- Escala horizontalmente (añadiendo más servidores) o verticalmente (mejorando la capacidad de cada servidor) en función de la carga de trabajo.
- Garantiza que la aplicación pueda manejar picos de tráfico sin intervención manual.

##### Monitoreo y Métricas

- Integrado con Amazon CloudWatch, permite rastrear el rendimiento de la aplicación, como:
- - Uso de CPU, memoria, tráfico de red, y errores.
- - Alertas configurables para eventos críticos.

##### Integración con otros servicios de AWS

- Funciona perfectamente con:
- - Amazon RDS para bases de datos relacionales.
- - Amazon DynamoDB para bases de datos NoSQL.
- - Amazon S3 para almacenamiento de objetos.
- - AWS Lambda para funciones serverless adicionales.

#### Facilidad de implementación:

- Más técnica que Heroku, requiere conocimientos básicos de contenedores y Kubernetes.
- Ideal para equipos con experiencia técnica avanzada.

#### Comparativa de plataformas

|    Plataforma     |            Ventaja principal            | Facilidad | Coste inicial |                        Recomendado para                        |
| :---------------: | :-------------------------------------: | :-------: | :-----------: | :------------------------------------------------------------: |
| Google App Engine | Escalado automático y ecosistema Google |   Alta    |     Bajo      |       Equipos que necesitan escalabilidad y simplicidad.       |
|      Heroku       |    Sencillez y rapidez de despliegue    | Muy alta  |     Bajo      | Proyectos pequeños/medianos con poco tiempo de implementación. |
| Red Hat OpenShift |   Potencia y flexibilidad empresarial   |   Medio   |     Medio     |        Empresas grandes con experiencia en Kubernetes.         |

## 4. Análisis Económico

### 4.1. Google App Engine

#### Precios de Google App Engine

Google App Engine utiliza un modelo de pago por uso, lo que significa que solo pagas por los recursos que consume tu aplicación. Además, incluye un nivel gratuito para que puedas desarrollar, probar o ejecutar aplicaciones ligeras sin incurrir en costos.

#### Nivel gratuito

- Tiempo de CPU (vCPU): 28 horas/vCPU al día.
- Memoria: 128 MB de RAM por instancia gratuita.
- Almacenamiento: 1 GB de espacio en base de datos Cloud Datastore o Firestore.
- Transferencia de datos: Hasta 1 GB de salida al mes.
- Ideal para aplicaciones de prueba o proyectos pequeños con bajos volúmenes de tráfico.

#### Precios de recursos adicionales

- Tiempo de CPU (vCPU): $0.046 por hora de CPU utilizada.
- Memoria (RAM): $0.00624 por GB-hora.
- Almacenamiento: Bases de datos (Cloud SQL, Firestore, etc.): $0.12 por GB/mes
  Almacenamiento persistente (Cloud Storage): $0.026 por GB/mes.
- Transferencia de datos (Red):
  -- Entrada de datos (hacia App Engine): Gratuita.
  -- Salida de datos (desde App Engine):
  --- Dentro de la misma región: $0.01 por GB.
  --- A otras regiones o a Internet: $0.12 por GB.

#### Ejemplo de costos típicos (Práctico)

##### Aplicación web pequeña (bajo tráfico):

- 10 vCPU-horas al día: $0.46/día (~$13.8/mes).
- 10 GB de almacenamiento: $1.2/mes.
- Transferencia de datos: 5 GB de salida (~$0.60/mes).
- Costo total aproximado: $15.6/mes.

##### Aplicación web de tamaño mediano (tráfico moderado):

- 50 vCPU-horas al día: $2.3/día (~$69/mes).
- 50 GB de almacenamiento: $6/mes.
- Transferencia de datos: 25 GB de salida (~$3/mes).
- Costo total aproximado: $78/mes.

##### Aplicación grande (alto tráfico y entorno flexible):

- 500 vCPU-horas al día: $23/día (~$690/mes).
- 200 GB de almacenamiento: $24/mes.
- Transferencia de datos: 500 GB de salida (~$60/mes).
- Costo total aproximado: $774/mes.

### 4.2. Heroku

##### Precios de Heroku

Heroku ofrece un modelo de precios flexible, adaptado a diferentes tipos de aplicaciones y necesidades, desde proyectos pequeños hasta soluciones empresariales.
Los costos dependen del tipo de Dyno (contenedores virtuales) que utilices, el número de Dynos necesarios y los complementos adicionales que integres en tu aplicación.

##### Planes para Dynos

###### Dynos Gratis

- Costo: $0/mes.
- Características:
- Adecuado para proyectos pequeños o de prueba.
- Hasta 550-1,000 horas mensuales (según la verificación de la cuenta).
- Se "duerme" automáticamente después de 30 minutos de inactividad y requiere un reinicio.
- Incluye 1,000 solicitudes de base de datos por mes en Heroku Postgres.

###### Dynos Hobby

- Costo: $7/mes por Dyno.
- Características:
- - Perfecto para proyectos personales en producción.
- - No se duerme con inactividad.
- - Soporte para SSL y nombres de dominio personalizados.

###### Dynos Standard

- Standard-1X: $25/mes por Dyno.
- Standard-2X: $50/mes por Dyno.
- Características:
- - Ideal para aplicaciones de producción con tráfico moderado.
- - Escalabilidad horizontal con más Dynos.
- - Alto tiempo de actividad.

###### Dynos Performance

- Performance-M: $250/mes por Dyno.
- Performance-L: $500/mes por Dyno.
- Características:
- - Diseñados para aplicaciones empresariales de alta demanda.
- - Rendimiento superior y capacidades avanzadas.
- - Menor latencia y soporte para gran cantidad de solicitudes simultáneas.

###### Dynos Enterprise

- Precios personalizados según las necesidades de la empresa.
- Incluyen soporte dedicado, mayor capacidad de escalado y cumplimiento normativo avanzado.

##### Complementos

###### Heroku Postgres (Base de datos relacional):

- Plan gratuito: Incluye 10,000 filas y 20 conexiones máximas.
- Plan pagado: Desde $9/mes hasta $3,500/mes, dependiendo de la capacidad de almacenamiento y rendimiento.

###### Redis (Caché en memoria):

- Gratis: Hasta 25 MB de almacenamiento.
- Plan pagado: Desde $15/mes hasta $750/mes para aplicaciones empresariales.

###### Papertrail (Logs):

- Gratis: Retención de logs de 7 días.
- Plan pagado: Desde $7/mes con mayores capacidades de almacenamiento y análisis.

### 4.3. Google App Engine

#### Instancias EC2 (Cómputo)

EC2 permite a los usuarios alquilar computadores virtuales, llamadas instancias EC2, en la nube de AWS.

- Costo: Varía según el tipo de instancia, región y uso.
- Por ejemplo, una t2.micro (uso general) cuesta ($8.35/mes si se usa continuamente).
- Puedes optar por instancias bajo demanda, reservadas o de spot para ajustar los costos.

#### Almacenamiento S3

Se utiliza para almacenar archivos estáticos o datos relacionados con la aplicación.

- Costo: $0.023/GB al mes para los primeros 50 TB almacenados.
- Transferencias de datos a S3 son gratuitas dentro de AWS.

#### Balanceadores de Carga (ELB)

Elastic Beanstalk utiliza balanceadores de carga para distribuir el tráfico entre instancias.

- Costo: $0.025 por hora, más $0.008 por GB transferido.

#### Bases de Datos RDS

Si se requiere una base de datos relacional, Elastic Beanstalk puede aprovisionarla automáticamente.
Costo: Desde ($7.44/mes), dependiendo del tipo de instancia y almacenamiento.

#### Escalabilidad Automática

Elastic Beanstalk puede escalar instancias automáticamente según la carga.

- Costo: Proporcional al número de instancias adicionales lanzadas durante los picos de tráfico.

#### Transferencia de Datos

Los datos transferidos entre servicios de AWS dentro de la misma región son gratuitos.

- Costo de datos salientes:
- - Primer GB por mes: Gratis.
- - Resto: $0.09/GB para los primeros 10 TB al mes.

#### Herramientas Opcionales

Elastic Beanstalk puede integrarse con otros servicios que tienen costos adicionales, como:

- CloudWatch Logs: Desde $0.50 por GB almacenado.
- Route 53 (DNS): $0.50 por zona al mes.

## 5. Conclusión

El modelo PaaS (Plataforma como Servicio) es la mejor opción para las empresas de desarrollo de software porque permite crear e implementar rápidamente una aplicación web sin necesidad de administrar la infraestructura. Con PaaS, los desarrolladores pueden centrarse únicamente en el código, mientras que la plataforma se encarga del mantenimiento del hardware, la gestión del servidor y el escalado de las aplicaciones. Entre las opciones analizadas destacan Google App Engine y Heroku como las mejores alternativas.

Google App Engine proporciona escalabilidad automática y estrecha integración con el ecosistema de Google Cloud, ideal para proyectos que requieren alta disponibilidad y escalabilidad. Además, la compatibilidad con bases de datos como PostgreSQL simplifica la gestión de bases de datos de aplicaciones. Sin embargo, esto puede resultar costoso si el proyecto se expande significativamente.
Por otro lado, Heroku es fácil de usar y perfecto para proyectos pequeños y medianos. Su facilidad de implementación y su amplia selección de complementos lo hacen ideal para desarrolladores que desean centrarse rápidamente en el desarrollo sin preocuparse por la infraestructura subyacente. Es más barato y adecuado para aplicaciones de rápido crecimiento.

Ambas plataformas permiten un modelo de pago por uso, lo que permite adaptarlas fácilmente a las necesidades de cada proyecto, pero es importante realizar un análisis de costos basado en el acceso al tráfico y las necesidades de las aplicaciones. En definitiva, PaaS es la solución más eficaz para este tipo de proyectos. Tanto Google App Engine como Heroku son excelentes opciones, y la elección dependerá de la complejidad del proyecto y la experiencia técnica del equipo.

## 6. Webgrafía y otros enlaces

1. **ENLACE PRESENTACIÓN:** [Enlace canva](https://www.canva.com/design/DAGZStUlo2A/jAjl9vrAKkgoDXUBmcFkwQ/edit)
2. **TIPOS DE SERVICIO EN LA NUBE:** [arsys](https://www.arsys.es/blog/que-es-iaas-saas-paas-faas-caas-te-explicamos-en-que-consisten-los-diferentes-servicios-de-la-nube)
3. **PaaS:** [Microsoft](https://azure.microsoft.com/es-es/resources/cloud-computing-dictionary/what-is-paas)
4. **Google App Engine:** [Cloud Google](https://cloud.google.com/appengine?hl=es-419)
5. **Heroku:** [Heroku](https://www.heroku.com/?utm_source=google&utm_medium=paid_search&utm_campaign=emea_heraw&utm_content=general-branded-search-rsa&utm_term=heroku&utm_source_platform=GoogleAds&gad_source=1&gclid=CjwKCAiAmfq6BhAsEiwAX1jsZ60HrF5my2nORjwJiwccQ1PnxLtFrQ6dFwwmKrC1K_mrUPL3aINsdRoCJb0QAvD_BwE)
6. **AWS Elastic Beanstalk:** [Amazon](https://aws.amazon.com/es/elasticbeanstalk/?trk=3f9fabd5-1409-48b0-a0d7-eed573be21d0&sc_channel=ps&ef_id=CjwKCAiAmfq6BhAsEiwAX1jsZ7zfrqF28NxWJfc8HA7bu9RgG_PmxpWgL0UUV14xShhTvBlvRGAcDxoCUTwQAvD_BwE:G:s&s_kwcid=AL!4422!3!651612449174!e!!g!!elastic%20beanstalk!19835790842!148728882204&gclid=CjwKCAiAmfq6BhAsEiwAX1jsZ7zfrqF28NxWJfc8HA7bu9RgG_PmxpWgL0UUV14xShhTvBlvRGAcDxoCUTwQAvD_BwE)
7. **Red Hat OpenShift:** [Red Hat](https://www.redhat.com/en/technologies/cloud-computing/openshift)

### 6.1 NOTA

Utilizamos más páginas para contrastar información, pero desgraciadamente no guardamos correctamente los enlaces, por lo que no pudimos añadirlas a nuestro trabajo.
