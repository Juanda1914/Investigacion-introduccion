# Investigacion-introduccion
#  PRUEBAS UNITARIAS:
Las pruebas unitarias consisten en aislar una parte del código y comprobar que funciona a la perfección. Son pequeños tests que validan el comportamiento de un objeto y la lógica.
El unit testing suele realizarse durante la fase de desarrollo de aplicaciones de software o móviles. Normalmente las llevan a cabo los desarrolladores, aunque en la práctica, también pueden realizarlas los responsables de QA.
Hay una especie de mito respecto a las pruebas unitarias. Algunos desarrolladores están convencidos de que son una pérdida de tiempo y las evitan buscando ahorrar tiempo.
Nada más alejado de la realidad.
Con ellas se detectan antes errores que, sin las pruebas unitarias, no se podrían detectar hasta fases más avanzadas como las pruebas de sistema, de integración e incluso en la beta.
Realizar pruebas unitarias con regularidad supone, al final, un ahorro de tiempo y dinero.

Cómo llevarlas a cabo:
El proceso de los tests unitarios puede realizarse de manera manual, aunque lo más común es automatizar el procedimiento a través de herramientas.
Hay muchas opciones disponibles, que varían en función del lenguaje de programación que se esté utilizando. Estos son algunos ejemplos de este tipo de herramientas que te ayudarán con las pruebas.

xUnit: se trata de una herramienta de pruebas unitarias para el framework .NET.
Junit: es un conjunto de bibliotecas para realizar pruebas unitarias de aplicaciones Java.
NUnit: inicialmente portado desde JUnit, NUnit 3 se ha reescrito por completo para dotarlo de nuevas características y soporte para una amplia gama de plataformas .NET.
PHPUnit: entorno de pruebas unitarias en el lenguaje de programación PHP.
Al utilizar estas herramientas, se codifican los criterios en la prueba que verificarán si el código es o no correcto. Durante la fase de ejecución, la herramienta puede detectar las pruebas con errores.
Si alguno de estos errores es grave, puede detener pruebas posteriores que iban a realizarse a continuación.

#  PRUEBAS DE INTEGRACION:
Las pruebas de integración o pruebas integradas se definen como un mecanismo de testeo de software, donde se realiza un análisis de los procesos relacionados con el ensamblaje o unión de los componentes, sus comportamientos con múltiples partes del sistema (ya sea de archivos operativos) o de hardware, entre otras.
De modo que las pruebas de integración están a cargo del examen de las interfaces entre los subsistemas o los grupos de componentes del programa o aplicación que se analiza, lo que contribuye a garantizar su funcionamiento correcto.

Características de las pruebas de integración:

Dentro de las principales características de las pruebas de integración se puede incluir su propiedad de comprobar la interacción adecuada de los componentes del sistema, para lo que usa sus interfaces internas o externas.

Estas pruebas también verifican que el sistema y sus componentes corran bien, cumplen con cada una de las labores asignadas y se adaptan a los requisitos establecidos.

Otra de las características de este tipo de pruebas es que permiten el uso de sistemas reales, preparados y dedicados específicamente para este test, lo que hará más sencillo el proceso de aplicación de la prueba.

Las pruebas de integración también se caracterizan por aplicarse después de las pruebas unitarias, cuando estas no son suficientes y se necesita probar el software de una manera más global.

#     PRUEBAS FUNCIONALES:

Las pruebas funcionales en las pruebas de software son una forma de determinar si el software o una aplicación funcionan como se espera. Las pruebas funcionales no se ocupan de cómo se produce el procesamiento, sino de si éste ofrece los resultados correctos o tiene algún fallo.
Al realizar una prueba funcional, se busca cualquier laguna, error o cualquier cosa que falte en los requisitos del software o la aplicación.
La diferencia entre las pruebas del sistema y las pruebas funcionales es que las primeras prueban todo el sistema, mientras que las segundas sólo prueban una característica.

Tipos de pruebas funcionales:

Pruebas unitarias
Pruebas de componentes
Pruebas de humo
Pruebas de integración
Pruebas de regresión
Pruebas de cordura
Pruebas de aceptación

#   PRUEBAS DE ACEPTACION:

En Ingeniería y sus diversas disciplinas, el Testing de aceptación se realiza para determinar si los requerimientos de una especificación o contrato han sido cumplidos.
En la Ingeniería de sistemas, las pruebas de aceptación de software implican pruebas de caja negra antes de su entrega definitiva.
Por su parte, el Internationa Software Testing Qualification Board (ISTQB) define la “Aceptación” como: Pruebas formales con respecto a las necesidades del usuario, requerimientos y procesos de negocio, realizadas para determinar si un sistema satisface los criterios de aceptación que permitan que el usuario, cliente u otra entidad autorizada pueda determinar si acepta o no el sistema.
Las pruebas de aceptación a menudo también se les denominan pruebas de aceptación de usuario (UAT), pruebas de usuario final, pruebas de aceptación operacional o pruebas de campo.
Estas pruebas son fundamentales para asegurar el éxito de la implementación final de un proyecto de ingeniería de software, por lo cual deben incluirse obligatoriamente en el plan de pruebas de software.

¿Cuál es la base para definir las pruebas de aceptación de software?
Según los estándares establecidos por el ISTQB, las pruebas de aceptación de software son diseñadas a partir de:

Requerimientos del usuario.
Requerimientos de sistema.
Casos de uso.
Procesos de negocio.
Reportes de análisis de riesgo.

¿Cuáles son los tipos de pruebas?

Pruebas unitarias. Las pruebas unitarias son de muy bajo nivel y se realizan cerca de la fuente de la aplicación. ...
Pruebas de integración
Pruebas funcionales
Pruebas de extremo a extremo
Pruebas de aceptación
Pruebas de rendimiento
Pruebas de humo

#   PRUEBAS DE RENDIMIENTO:

El objetivo de las pruebas de rendimiento es determinar el rendimiento del sistema bajo una carga de trabajo definida utilizando diferentes tipos de pruebas de rendimiento tales como pruebas de carga, de estrés y de estabilidad.
Tenga en cuenta las consideraciones siguientes:
Las prácticas recomendadas para realizar pruebas de rendimiento son las mismas que para las pruebas funcionales: probar en las fases iniciales y con frecuencia.
Aproveche los activos de prueba existentes creados en las pruebas funcionales.
Utilice analizadores para recopilar estadísticas de servidor, tales como utilización de CPU y de memoria.
La instalación de agentes en varios sistemas para controlar la carga puede crear un perfil de generación de carga más realista y distribuido.
Utilice la acción "Registrar medida" para almacenar información adicional de servidores.
Utilice varios conjuntos de datos para combinar dos o más gráficos de rendimiento, tales como gráficos de tiempo de respuesta y gráficos de utilización de CPU.

¿Qué tipos de prueba de rendimiento existen?

Pruebas de Carga. 
Pruebas de Capacidad. 
Pruebas de Estabilidad. 
Pruebas de Estrés o sobrecarga. 
Pruebas de Picos. 
Pruebas de Aislamiento. 
Pruebas de Regresión.

#    PRUEBAS DE ESTRES :

La prueba de estrés es un tipo de prueba que se utiliza para determinar los límites del sistema, app o web, sometiéndolas a un alto nivel de concurrencia de usuarios en simultáneo, con el objetivo de encontrar su punto de inflexión, ya sea a nivel de aplicación como de su infraestructura.
El objetivo de las pruebas de estrés es medir la solidez y las capacidades de manejo de errores del software, apps o webs en condiciones de carga extremadamente pesada y garantizar que el software no se bloquee en situaciones críticas. 
De hecho, en Atentus hemos visto que diversos ecommerce colapsaron en los Cybers o Black Friday porque no soportaron los altos niveles de tráfico, tampoco realizaron una prueba de estrés, perdiendo oportunidades de ventas y miles de dólares.
Es por ello que en Atentus ofrecemos este servicio que consiste en realizar pruebas de carga y estrés a sus plataformas web, determinando su capacidad de atención frente a una alta concurrencia de usuarios. Esto es posible gracias a los Atentubots que generan una navegación automática y masiva, estresando y degradando la aplicación o plataforma web de la empresa, con el fin de conocer su real comportamiento y capacidad ante la demanda de múltiples sesiones simultáneas.

Tipos de pruebas de estres:

Tipos de pruebas de estrés:
Los siguientes son los tipos de pruebas de estrés y se explican a continuación:

Prueba de estrés de la aplicación:
Estas pruebas se concentran en encontrar defectos relacionados con el bloqueo de datos, problemas de red y cuellos de botella en el rendimiento de una aplicación.

Pruebas de estrés transaccional:
Realiza pruebas de estrés en una o más transacciones entre dos o más aplicaciones. Se utiliza para ajustar y optimizar el sistema.

Pruebas de estrés sistémico:
Esta es una prueba de estrés integrada que se puede probar en múltiples sistemas que se ejecutan en el mismo servidor. Se utiliza para encontrar defectos en los que los datos de una aplicación bloquean otra aplicación.                                                                     

Pruebas de estrés exploratorias:
Este es uno de los tipos de pruebas de estrés que se utilizan para probar el sistema con parámetros o condiciones inusuales que es poco probable que ocurran en un escenario real. Se utiliza para encontrar defectos en escenarios inesperados como:

Un gran número de usuarios registrados al mismo tiempo.
Si un escáner de virus se inició en todas las máquinas simultáneamente.
Si la base de datos se ha desconectado cuando se accede a ella desde un sitio web.
Cuando se inserta un gran volumen de datos en la base de datos simultáneamente.

#   PRUEBAS DE EGRESION:

Las pruebas de regresión son un tipo de prueba de aplicaciones para determinar si el software aún funciona después de que se haya cambiado o modificado el código existente. 

Es un paso crucial para permitir que los desarrolladores mejoren continuamente el software sin afectar negativamente su funcionalidad existente. El objetivo de las pruebas de regresión en el desarrollo de software es descubrir problemas derivados de cualquier cambio que pueda afectar el funcionamiento del software.

Ventajas, desventajas y desafíos de las pruebas de regresión

Ventajas

Las pruebas de regresión son un paso importante para mejorar la calidad del software y la experiencia del usuario. 
Garantiza que cualquier cambio realizado en el código fuente no haya afectado la funcionalidad general del software.
 Ahorra tiempo y dinero al ayudar a entregar un producto de alta calidad más rápido. A través de casos de prueba automatizados, el costo y el tiempo del proyecto general se reducen drásticamente.
 
Desventajas

Aunque los casos de prueba de regresión se pueden automatizar, algunos casos deben hacerse manualmente. Las pruebas manuales requieren mucho tiempo y recursos humanos.
La prueba de regresión es un proceso altamente repetitivo, e incluso un pequeño cambio necesita prueba, ya que puede afectar las funcionalidades básicas del software.
Las funcionalidades complejas en su mayoría necesitan scripts de prueba complejos, lo que puede retrasar la fecha límite de ejecución de la prueba.

Desafios

A pesar de todos los grandes beneficios que brindan las pruebas de regresión, también existen algunos desafíos: 

Selección de la herramienta adecuada – Para el éxito de las pruebas de regresión, es esencial elegir la herramienta adecuada. De lo contrario, resultará en un gasto de tiempo, dinero y recursos.

Hora - Las pruebas de regresión son repetitivas y, por lo tanto, consumen mucho tiempo. Es por eso que se convierte en un gran desafío ejecutar y entregar el producto antes de la fecha límite.

Complejidad – Debido a su naturaleza altamente repetitiva, los casos de prueba se vuelven cada vez más complejos a medida que el producto pasa de la primera etapa de construcción a la siguiente. Requerirá probar los casos de prueba antiguos junto con los nuevos todo el tiempo.

#   PRUEBAS DE HUMO:

Con prueba de humo, la mayoría de los problemas de compilación se pueden identificar en las primeras etapas del desarrollo del programa y pueden ser útiles para la corrección de los mismos, por lo que se puede decir que las pruebas de humo son una prueba de regresión frecuente de las funcionalidades principales y se manifiesta si la compilación es listo para llevar a cabo más pruebas.

Los desarrolladores pueden adoptar este método y la compilación pasa la prueba, entonces solo se puede implementar para más pruebas; de lo contrario, se debe rechazar.

¿Cuando hacer una prueba de humo?

Prueba de humo debe realizarse en la fase inicial del ciclo de vida de prueba, ya que verifica muy pronto la productividad de la construcción y asegura si los requisitos elementales se pueden cumplir o no. Siempre que se implemente una compilación nueva o se realice algún cambio en la compilación, se deben realizar pruebas de humo.
El desarrollo de software siempre se divide en diferentes sprints para que se cubran todos los rincones por lo que es importante que cada sprint tenga un código estable por lo que la prueba de humo toma muy poco tiempo para cumplir con esta necesidad antes de la prueba de regresión y, de esta manera, también ahorramos nuestro precioso tiempo también.
El objetivo de las pruebas de humo es probar las funcionalidades importantes de un sistema y no ejecutar los escenarios de prueba exhaustivos.
