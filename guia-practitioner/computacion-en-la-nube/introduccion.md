# Table of Contents
1. [Introduccion](#introduccion)
2. [Que es la ccomputacion en sa nube?](#Que-es-la-camputacion-en-la-nube)
3. [A Brief History of Cloud Computing](#a-brief-history-of-cloud-computing)
4. [Advantages of Cloud Computing](#advantages-of-cloud-computing)

## Introduccion

AWS es una plataforma integral que ofrece servicios de computación en la nube y soluciones de infraestructura para empresas y desarrolladores.

En 2006, Amazon Web Services (AWS) comenzó a ofrecer servicios de infraestructura de TI a las empresas como servicios web, lo que hoy conocemos como computación en la nube.

## Que es la computacion en la nube?

La computación en la nube es la entrega de poder de cómputo, almacenamiento, bases de datos y otros recursos de TI bajo demanda, a través de internet, mediante una plataforma unificada que permite a las empresas e individuos escalar y gestionar sus operaciones de manera eficiente.

## Historia de la computacion en lo nube

- **1950s**: Se introdujeron las computadoras mainframe, sentando las bases para la computación en la nube.
- **1960s**: Surge el concepto de "time-sharing", que permite a varios usuarios acceder a recursos de cómputo en una sola máquina.
- **1990s**: El auge de internet pavimenta el camino para la computación distribuida y el desarrollo de los primeros servicios similares a la nube.
- **1999**: Salesforce lanza su software CRM basado en la nube, marcando una de las primeras aplicaciones exitosas en la nube.
- **2002**: Se lanza Amazon Web Services (AWS), ofreciendo servicios de infraestructura en la nube a las empresas.
- **2006**: AWS introduce Elastic Compute Cloud (EC2), permitiendo poder de cómputo y almacenamiento bajo demanda.
- **2008**: Google lanza Google App Engine, ampliando las ofertas de la nube más allá de infraestructura, hacia plataformas y software.
- **2010**: Microsoft lanza Windows Azure (ahora Microsoft Azure), consolidándose como un actor importante en el mercado de la nube.
- **2014**: La adopción de la computación en la nube se acelera, con un cambio significativo de la infraestructura de TI local a la nube.
- **2020s**: La computación en la nube sigue creciendo con avances en inteligencia artificial, aprendizaje automático y soluciones de nube híbrida.

## Beneficios de la computacion en la nube

## Seguridad
AWS proporciona una infraestructura segura diseñada específicamente para la nube. 

Los datos se cifran automáticamente en la capa física antes de salir de las instalaciones protegidas, lo que garantiza la confidencialidad, integridad y disponibilidad. 

Los clientes mantienen la propiedad de sus datos, incluyendo su capacidad para cifrarlos, transferirlos y gestionar su retención.

## Disponibilidad 
AWS ofrece una alta disponibilidad de red. Cada región está completamente aislada y compuesta por varias **Zonas de Disponibilidad (AZ)**, que son centros de datos independientes. 

Esto permite distribuir las aplicaciones a través de múltiples AZ para mejorar la resiliencia. Los planos de control de AWS y la consola de administración están diseñados para funcionar de manera segura incluso en aislamiento, garantizando un funcionamiento seguro durante al menos 24 horas sin intervención externa.

## Rendimiento
La infraestructura global de AWS está optimizada para el rendimiento. 

Ofrece baja latencia, mínima pérdida de paquetes y alta calidad de red, gracias a una red troncal de 400 GbE. **AWS Local Zones** y **AWS Wavelength** proporcionan infraestructura cerca de los usuarios finales y dispositivos conectados 5G, garantizando latencias muy bajas. 

Además, permite iniciar recursos rápidamente, implementando miles de servidores en minutos.

## Escalabilidad
AWS permite una escalabilidad prácticamente infinita, lo que permite a las empresas ajustar los recursos según sus necesidades. 

Ya no es necesario sobreaprovisionar infraestructura, ya que se pueden aumentar o disminuir los recursos instantáneamente. Esto reduce costos y mejora la capacidad de respuesta a las demandas del negocio.

## Flexibilidad
La infraestructura de AWS ofrece flexibilidad total para ejecutar cargas de trabajo donde se necesiten. Se puede elegir entre **Regiones** y **Zonas de Disponibilidad (AZ)** globalmente, o utilizar opciones como **AWS Outposts** para ejecutar aplicaciones localmente. 

## Presencia Global
AWS tiene la mayor presencia global de infraestructura en la nube. Esto permite ejecutar aplicaciones cerca de los usuarios finales para asegurar el mejor rendimiento y baja latencia. 

Además, **AWS Ground Station** proporciona antenas satelitales cercanas a las regiones de infraestructura de AWS, ofreciendo soluciones de comunicación satelital.



## Componentes Principales de la Infraestructura de AWS

### 1. **Regiones y Zonas de Disponibilidad**
   AWS opera en múltiples **regiones** alrededor del mundo, cada una de ellas compuesta por varias **zonas de disponibilidad (AZ)**. 
   
   Cada región es una ubicación geográfica independiente, y las zonas de disponibilidad son centros de datos físicos que proporcionan redundancia y resiliencia.

   - **Región**: Es una área geográfica que contiene varias zonas de disponibilidad, a diciembre 2024 hay **34 regiones** lanzadas .

   - **Zona de Disponibilidad (AZ)**: Es un centro de datos aislado separado por 100km en promedio entre cada uno,  dentro de una región que está conectado a otras zonas mediante redes de baja latencia. a Diciembre 2024 hay **108 zonas** .

   > AWS recomienda replicar los datos y recursos entre las zonas de disponibilidad para obtener mayor resiliencia.

### ¿Cómo elegir una región de AWS? 

- Cumplimiento de los requisitos legales y de gobernanza de datos: los datos nunca salen de una región sin un permiso explícito.
- Proximidad a los clientes: latencia reducida.
- Servicios disponibles en una región: los nuevos servicios y las nuevas funciones no están disponibles en todas las regiones.
- Precios: los precios varían de una región a otra y son transparentes en la página de precios del servicio.

### 2. Zonas Locales

Las zonas locales están disponibles en 34 áreas metropolitanas de todo el mundo: 17 fuera de los Estados Unidos (Auckland, Bangkok, Buenos Aires, Copenhague, Delhi, Hamburgo, Helsinki, Calcuta, Lagos, Lima, Manila, Mascate, Perth, Querétaro, Santiago, Taipéi y Varsovia) y 17 en los Estados Unidos.