# Revoluciones industriales

## Primera revolucion industrial -> Inglaterra Año 1750

Se crea la maquina de vapor, maquina de hilar y la locomotora a vapor

## Segunda revolucion industrial -> USA Año 1850

Se vuelve la generacion de energia electrica con el bombillo electrico, radio electrico
Tambien cambio la industria petro-quimica
La produccion en serie -> Ford

## Tercera revolucion industrial -> USA-Japon Año 1950

Se creo el primer robot, primer PLC, Celular, PC y se empezo con el uso de la red. En est

## Cuarta revolucion industrial -> China-Europa-USA Año 2010

Es el auge de la creacion de software, conexion a internet. El uso de inteligencia artificial y con todo eso la evolucion de la creatividad.

>Para la transformacion digital es necesario tener caracteristicas de la cuarta revolucion industrial, ademas de cultura empresarial y estrategia.

Queremos tener transformacion digital usando los recursos dados por la 4RI para poder mejorar los procesos.

En esta tenemos varias tecnologias como lo es la Inteligencia artificial, Computacion en la nube o el internet de las cosas.

# Automatización (Norma ISA)

Se establecio en 1945 y es una de las organizaciones mas antiguas. Ha desarrollado una amplia gama de estandares para la industria, incluyendo comunicacion, la seguridad, energia, automatizacion y calidad.

- ISA 95: Piramide de Automatizacion -> El objetivo principal es dar un marco para integrar los sistemas de automatizacion y de informacion empresarial en la industria.

![](../Images/ISA95.jpeg)

Sensores y actuadores -> Control -> SCADA (Supervisory Control and Data Acquisition) -> Gestion de produccion (Manufacturing execution systems "MES") -> Gesion corporativa (Enterprise Resource Planning "ERP")

## Problema asociado -> Convergencia entre OT e IT

La convergencia de la IA con tecnologias de control y comunicacion ha posibilitado el desarrollo de entornos de produccion adaptativos.

Con la Estandar ISA 95 tenemos que la comunicacion es bidireccional entre dos niveles consecutivos.

- Comunicaciones industriales: Control <-> Sensores y actuadores
- Comunicacion OPC: SCADA <-> Control
- Comunicacion Ethernet: MES <-> SCADA
- Comunicacion Ethernet: ERP <-> MES

Si un nivel falla, la comunicacion de los niveles superiores quedan desconectados. Se puede mejorar es con el uso de la nube donde la comunicacion de cada nivel es directa a ella.

Sistema empresarial <-> Estrategia <-> Tecnologia

### Sistema MES vs ERP

Crear la base adecuada requiere invertir en sistemas basicos que lleven a su empresa por la direccion correcta. Desde elementos de software ***ERP (Sistemas de planificacion de recursos empresariales)*** y sistema ***MES (sistema de ejecucion de fabricacion)***.

La solucion correcta debe abordar aspectos cruciales y acercarlo a los objetivos.

- **Que es un sistema MES?** Sistemas de ejecucion manufacturera son potentes sistemas de software que sirven para mejorar la capacidad, calidad, entrega y visibilidad. Las capacidades actuales pueden impulsar su madurez digital, maximizar el potencial operacional, facilitar lamejora continua y acelerar la inovacion.
- **Que es la ERP?** El sistema de Planificacion de Recursos Empresariales Plex adecuado puede ayudar a su empresa a funcionar de manera mas eficiente y eficaz. Muchos fabricantes informan que las caracteristicas y la funcionalidad del sistema ERP tradicional no estan diseñadas para la planta.

**Cual es la principal diferencia entre los dos sistemas?**

Un sistema MES automatiza la organizacion de la produccion mediante el control de procesos basado en IA y optimiza protocolos de mantenimiento con monitoreo inteligente de activos. Mientras que el sistema ERP informa sobre la cantidad de materiales que necesita para completar un pedido y sobre cuanto debe este salir de su planta.

### Sistemas DCS (Distribuited Control System)

Destaca principalmente por su fiabilidad, precision y escalabilidad siendo uno de los pilares tecnologicos de la industria moderna.

> Es un sistema de automatizacion diseñado para controlar procesos industriales complejos distribuidos geograficamente, como los que se encuentran en plantas quimicas, refinerias, centrales electricas, fabricas de papel, alimentos y mas.

Este sistema distribuye la inteligencia de control en diferentes zonas o areas del proceso ***Lo que lo hace mas resitente a fallos, flexible y mas eficiente por su control en multiples variables***

- Se tiene un *supercontrolador* tomando todas las decisiones, que reparte la inteligencia entre diferentes controladores distribuidos
    - Cada uno se encarga de una parte del proceso:
        - Linea de produccion
        - Caldera
        - Tanque de mezcla
        - etc...

Un DCS tiene un ciclo continuo:

1. Captura de datos
2. Procesamiento
3. Accion
4. Visualizacion
5. Registro

Todos los controladores, sensores, HMI y servidores estan conectados mediante una red de comunicacion industrial (garantiza fluidez continua, rapida y segura), ademas, los sitemas modernos permiten conexion con sistemas ERP o MES.

La **Red de Comunicacion Industrial** conecta todos los sistemas entre si utilizando protocolos como:

- Ethernet/IP
- Modbus TCP
- Profibus
- Profinet

Debe ser rapida, estable y segura.

![](../Images/Sistema-de-control-distribuido.png)