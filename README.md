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

