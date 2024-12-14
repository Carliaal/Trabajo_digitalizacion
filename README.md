# Trabajo digitalizacion

## Miembros del grupo

| Primer miembro                                                                           | Segundo miembro | Tercer miembro |
| ---------------------------------------------------------------------------------------- | --------------- | -------------- |
| Carla García Pacheco [@Carliaal](https://github.com/Carliaal/Trabajo_digitalizacion)     |
| Rodrigo García Delgado [@Rodrigo-44](https://github.com/Carliaal/Trabajo_digitalizacion) |

## Índice

- [Trabajo digitalizacion](#trabajo-digitalizacion)
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

El modelo PaaS (Plataforma como Servicio) es la mejor opción para las empresas de desarrollo de software porque permite crear e implementar rápidamente una aplicación web sin administrar la infraestructura. Con PaaS, los desarrolladores pueden centrarse únicamente en el código mientras la plataforma se encarga del mantenimiento del hardware, la gestión del servidor y el escalado de las aplicaciones. Entre las opciones analizadas destacan Google App Engine y Heroku como las mejores alternativas. Google App Engine proporciona escalabilidad automática y estrecha integración con el ecosistema de Google Cloud, ideal para proyectos que requieren alta disponibilidad y escalabilidad. Además, la compatibilidad con bases de datos como PostgreSQL simplifica la gestión de bases de datos de aplicaciones. Sin embargo, esto puede resultar costoso si el proyecto se expande significativamente. Por otro lado, Heroku es fácil de usar y perfecto para proyectos pequeños y medianos. Su facilidad de implementación y su amplia selección de complementos lo hacen ideal para desarrolladores que desean centrarse rápidamente en el desarrollo sin preocuparse por la infraestructura subyacente. Es más barato y adecuado para aplicaciones de rápido crecimiento.

Ambas plataformas permiten un modelo de pago por uso, por lo que puede adaptarlo fácilmente a las necesidades de su proyecto, pero es importante realizar un análisis de costos basado en el acceso al tráfico y las necesidades de las aplicaciones. En definitiva, PaaS es la solución más eficaz para este tipo de proyectos. Tanto Google App Engine como Heroku son excelentes opciones y la elección dependerá de la complejidad del proyecto y la experiencia técnica del equipo.

