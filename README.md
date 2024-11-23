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
* Microsoft Azure
* Oracle Claud
* Digital Ocean 

#### 2.1.2. Paas(Plataforma como Servicio) 
Proporciona una plataforma completa en la cual permite al cliente desarrollar, gestionar y desplegar aplicaciones sin tener que preocuparse acerca del software y del hardware ya que este es aportado por la empresa la cual ofrece el servicio. Los usuarios se centrar en escribir y ejecutar código con las herramientas aportadas. 
#### Ejemplos
*  Google App Engine
*  Red Hat OpenShift
*  Heroku
  
#### 2.1.3. FaaS (Función como Servicio)
Es un modelo de computación en la nube que facilita a los usuarios la ejecución individual de fragmentos de código o funciones, evitando la administración de servidores o infraestructura. Esta perspectiva se ubica dentro del término "sin servidor", en el que la nube se ocupa de gestionar la infraestructura, la escalabilidad y el mantenimiento.

#### Ejemplos
* Azure Functions
* IBM Cloud Functions
* AWS Lambda
  
#### 2.1.4.CaaS (Contenedor como Servicio)
Es un modelo de servicio en la nube que simplifica a los usuarios la implementación, administración y expansión de aplicaciones a través de la utilización de contenedores, evitando la necesidad de preocuparse por la infraestructura relacionada. Los contenedores facilitan la agrupación de las aplicaciones y sus dependencias, asegurando que operen de manera uniforme en diferentes ambientes, ya sea en servidores locales o en la nube.

#### Ejemplos
* Azure Kubernetes Service
* Google Kubernetes Engine
* Amazon Elastic Kubernetes Service

## 2.2. Elección del Modelo de Servicio adecuado
En este caso, consideramos que el modelo de servicio que mejor se adapta a las necesidades del usuario es el modelo PaaS (Plataforma como Servicio), ya que, como se explicó anteriormente, las plataformas PaaS ofrecen un servicio en la nube que permite al usuario desplegar su aplicación sin tener que preocuparse por el hardware, el software del servidor ni por el mantenimiento de la infraestructura subyacente.

Estas plataformas proporcionan un entorno de desarrollo ideal para gestionar tanto el backend como el frontend, además de ofrecer herramientas como bases de datos, que es uno de los requerimientos del cliente en este caso. También permiten al usuario centrarse únicamente en escribir y desarrollar el código, tal como lo ha solicitado el cliente.

En resumen, PaaS es la mejor opción si el usuario necesita un entorno de trabajo ya preparado y listo para empezar a desarrollar sin tener que preocuparse por el mantenimiento de la infraestructura.

## 3. Investigación de Plataformas


## 4. Análisis Económico

## 5. Conclusión



