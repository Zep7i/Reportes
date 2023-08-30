# // Relleno de contenido
Todo lugar que se encuentre encerrado entre corchetes de la siguiente manera: \[X] debe ser rellenado por el auditor/es correspondiente/s conforme a como se explicite en cada apartado el cómo debe ser rellenado.
**No escribir en el reporte todo apartado que contenga "//" por delante de su texto ya que es informativo, referencial o sirve para explicar que debe rellenar el auditor o auditores aunque no siempre puede estar presente ya que se especifica directamente**

# // Tarjeta de presentación (1 Hoja)
Debe adjuntarse en este apartado una tarjeta de presentación como un logotipo, imagen, etc. que lo represente a usted como auditor o a su equipo de auditoria para dar su presentación.
Esta debe contener:
- Logotipo
- Su nombre completo o el nombre de su equipo de auditoria (Puede utilizar apodos si así lo prefiere para más anonimato)
- La palabra "Reporte"
- Fecha y año de cuando se terminó de rellenar el reporte
- Versión del reporte (Si es su primer reporte para ese aplicativo en cuestión, su versión será la 1.0 por defecto)
# // Resumen ejecutivo
En este apartado se debe aclarar desde que fecha hasta que fecha se estuvo realizando la auditoria en el formato siguiente:
día-mes-año
Posteriormente se debe aclarar los "scopes" permitidos para realizar la auditoria
Se aclara que el reporte lista las vulnerabilidades encontradas en el periodo de tiempo anteriormente mencionado y que se comentan recomendaciones acerca de cada una.
Finalizamos mostrando un recuento de la cantidad de vulnerabilidades con su categoría de severidad correspondiente, ejemplo:

Crítico: 0
Alto: 0
Medio: 0
Bajo: 7
Notas: 2
# // Tabla de contenidos
## Introducción
Apartado introductorio con subdivisiones importantes para dejar en claro ciertas aclaraciones (Se rellenan las subdivisiones únicamente, este es un apartado)
### Limitaciones y descargo de responsabilidad
Se aclara que el reporte lista las vulnerabilidades encontradas en el periodo de tiempo mencionado en el resumen ejecutivo y no debe ser considerado como una lista completa de todas las vulnerabilidades que puede tener aún o no se hayan descubierto, incluyendo el descuidado de ciertas configuraciones las cuales no se conozcan o no se hayan tenido en cuenta.
### Período del proyecto y dotación de personal
Se específica cuándo comenzó la auditoria y cuándo finalizó.
Se específica la última vez que fue revisado/modificado el reporte.
Se específica los miembros conformes que auditaron el aplicativo durante el periodo de auditoria completo.
### Calificación del riesgo
Se específica en base a qué metodología se está evaluando el nivel de riesgo de cada vulnerabilidad explayada en el reporte, por ejemplo, puede utilizar la metodología de "OWASP Risk Rating".
Es importante que explaye de manera entendible y legible cómo funciona la metodología que usted cree conveniente para evaluar la severidad de las vulnerabilidades mencionadas en el reporte para que el cliente entienda a la perfección.

Adjuntar la definición sobre los riesgos generales, ejemplo:
El riesgo global refleja la estimación del riesgo que un hallazgo supone para el sistema o sistemas objetivo. Tiene en cuenta el impacto del hallazgo, la dificultad de explotación y cualquier otro factor relevante.
**Crítico:** Implica una amenaza inmediata y fácilmente accesible de compromiso total.
**Alto:** Implica una amenaza inmediata de compromiso del sistema, o una amenaza fácilmente accesible de violación a gran escala.
**Media:** Amenaza de violación a gran escala difícil de explotar, o amenaza fácil de una pequeña parte de la aplicación.
**Baja:** Implica una amenaza relativamente menor para la aplicación.
**Informativa:** Ninguna amenaza inmediata para la aplicación. Puede proporcionar sugerencias para la mejora de la aplicación, o condiciones que podrían conducir más tarde a un hallazgo explotable.

Adjuntar la definición sobre impacto, ejemplo:
El impacto refleja los efectos que una explotación exitosa tiene sobre el sistema o sistemas objetivo. Tiene en cuenta las pérdidas potenciales de confidencialidad, integridad y disponibilidad, así como las pérdidas potenciales de reputación.
**Alto:** Los atacantes pueden leer o modificar todos los datos de un sistema, ejecutar código arbitrario en el sistema o escalar sus privilegios a nivel de superusuario.
**Media:** Los atacantes pueden leer o modificar algunos datos no autorizados en un sistema, denegar el acceso a dicho sistema u obtener información técnica interna significativa.
**Bajo:** Los atacantes pueden obtener pequeñas cantidades de información no autorizada o degradar ligeramente el rendimiento del sistema. Pueden tener una percepción pública negativa de la seguridad.

Adjuntar la definición sobre explotabilidad, ejemplo:
La explotabilidad refleja la facilidad con la que los atacantes pueden explotar un hallazgo. Tiene en cuenta el nivel de acceso requerido, la disponibilidad de información de explotación, los requisitos relativos a la ingeniería social y otros impedimentos para la explotación.
**Alto:** Los atacantes pueden explotar unilateralmente el hallazgo sin permisos especiales ni obstáculos significativos.
**Media:** Los atacantes tendrían que recurrir a un tercero, obtener información no pública, explotar una condición de carrera, tener acceso privilegiado, o superar obstáculos moderados para explotar el hallazgo.
**Baja:** La explotación requiere ingeniería social inverosímil, una condición de carrera difícil, adivinar datos difíciles de adivinar o es improbable por cualquier otro motivo.
## Metodologías y Scope
## Scope
Aclarar los scopes permitidos para la auditoria y cuales no, asimismo aclarar de que tipo es la auditoria (Caja blanca, Caja negra o Caja gris)
## Metodología
Explicar de que manera se identificó los objetos a explotar, que herramientas se utilizaron durante el proceso de auditoria, que información se recabó y los métodos aplicados. En caso de que hayan existido ciertas limitaciones para poder realizar cierto ataque del lado del aplicativo de modo que no defiende el ataque pero tampoco lo permite ya sea por falta de un componente, actualización, configuración, etc., aclararlo.
## \[X]
En X colocar el nombre del apartado de la vulnerabilidad explicado más adelante.
## \[X1].\[Z1]
X1 debe ser el número en orden en el cuál se anuncia la vulnerabilidad, al ser la primer vulnerabilidad a expresar en la tabla de contenidos, colocar "1", si  Z1 es mayor a "9" entonces, se completa como "2" teniendo como máximo 9 (nueve) Z1 por cada X1.

Z1 debe ser el número en orden en el cuál le sigue a X1, en caso de que X1 sea igual a "1" y sea la primer vulnerabilidad a expresar en la tabla de contenidos entonces Z1 será igual a "1", si fuese la segunda vulnerabilidad entonces X1 seguiría siendo "1" pero Z1 cambiaría a "2".

**Nota:** Se aplica por cada apartado individual.
## Conclusiones y recomendaciones finales
// No lleva relleno interior, es parte de la tabla de contenidos
# Observaciones
## \[X]
Este apartado debe ser rellenado como subtitulo, haciendo referencia al apartado de la aplicación a la cuál se le informará de la vulnerabilidad encontrada en la plantilla posterior, ejemplo:
LOGIN
REGISTRO
ADMIN PANEL
HOME
Por favor añadir la cantidad de plantillas sobre la explicación de cada vulnerabilidad correspondiente para cada apartado como corresponda.
## \[X1].\[Z1]
X1 debe ser el número en orden en el cuál se anuncia la vulnerabilidad, al ser la primer vulnerabilidad a explicar sobre la plantilla se completa como "1", si  Z1 es mayor a "9" entonces, se completa como "2" teniendo como máximo 9 (nueve) Z1 por cada X1.

Z1 debe ser el número en orden en el cuál le sigue a X1, en caso de que X1 sea igual a "1" y sea la primer vulnerabilidad que se esté explicando entonces Z1 será igual a "1", si fuese la segunda vulnerabilidad entonces X1 seguiría siendo "1" pero Z1 cambiaría a "2".

**Nota:** Se aplica por cada apartado individual.
## // Plantilla (Sólo escribir la plantilla y rellenar)
// (Puede que hayan ciertos campos que no puedan ser rellenados por el auditor, ejemplo: Falta de información o reciente descubrimiento de un "0day", etc.)

- Nombre: // Nombre que usted le colocará para identificar esta vulnerabilidad
- Descripción: // Descripción breve sobre la vulnerabilidad
- Riesgo: // Definir el impacto y la explotabilidad de la vulnerabilidad de forma cualitativa y cuantitativa.
- CVE: // (De ser posible) Adjuntar códigos CVE que se relacionen con la vulnerabilidad, únicamente nombres junto a su referencia, ejemplo: "RCE Android 1.9.7" \[7]. Siendo "7" el número de orden de referencia totales que se han dispuesto a lo largo del reporte para después adjuntar un vínculo/link/url sobre el mismo.
- CVSS: // Adjuntar la cadena de vector calculada por el sistema de CVSS v4.0
- Tipo de vulnerabilidad: // Explicitar el tipo de vulnerabilidad, ejemplo: XSS, CSRF, DDOS, etc.
- Categoría: // Explicitar a que categoría pertenece la vulnerabilidad.
- Ubicación de explotabilidad: // Explicitar en dónde sucede esta vulnerabilidad en cuestión, adaptándose a los scopes permitidos.
- Impacto real: // Explicar cuál es el impacto que se pudo ver del lado del auditor o el grupo de auditores al explotar la vulnerabilidad.
- Impacto mínimo: // Explicar cuál sería el impacto mínimo que podría surgir al explotar la vulnerabilidad.
- Impacto máximo: // Explicar cuál sería el impacto máximo que podría surgir al explotar la vulnerabilidad.
- Pasos a seguir: // Explicar todos y cada uno de los pasos que se realizaron desde el reconocimiento que llevó a identificar un posible vector de vulnerabilidad hasta la explotación satisfactoria de la misma y las herramientas y/o metodologías utilizadas de por medio.
- Recomendaciones: // Realizar recomendaciones sobre la contramedida/defensa aplicada a la vulnerabilidad en cuestión.

## Información adicional (aclaraciones finales)
// (X se completa con un número inicialmente desde el "1" hasta infinito dependiendo sea el caso y en orden)
- Nota N°\[X]: // Nota dando alguna aclaración adicional sobre el aplicativo o vulnerabilidad.

# Conclusiones y recomendaciones finales
En este apartado se tratan las conclusiones finales sobre el aplicativo en el cuál se realizó la auditoria, aclarando cualquier cosa que haya quedado pendiente o desee añadir para finalizar, asimismo con las recomendaciones siendo o no relacionadas con la seguridad en sí del aplicativo.
# Referencias
Siempre que se hable sobre otro sitio, institución, aplicación o se cite/nombre debe incluirse el formato siguiente:

nombre \[X]

Finalmente en este apartado debe adjuntarse el vínculo/url/link de la referencia en cuestión, con el formato siguiente:

\[X] nombre
vínculo/url/link (Clickeable)

# // Ejemplo de categorías para utilizar
**Controles de acceso:** Relacionados con la autorización de usuarios y la evaluación de derechos.
**Auditoría y registro:** Relacionado con la auditoría de acciones o el registro de problemas.
**Autenticación:** Relacionado con la identificación de usuarios.
**Configuración:** Relacionado con las configuraciones de seguridad de servidores, dispositivos o software.
**Criptografía:** Relacionado con la protección matemática de los datos.
**Exposición de datos:** Exposición involuntaria de información sensible.
**Validación de datos:** Relacionado con la confianza indebida en la estructura o los valores de los datos.
**Denegación de servicio:** Relacionado con provocar fallos en el sistema.
**Notificación de errores:** Relacionado con la notificación de condiciones de error de forma segura.
**Parcheado:** Relacionado con mantener el software actualizado.
**Gestión de sesiones:** Relacionado con la identificación de usuarios autenticados.
**Tiempo:** Relacionado con las condiciones de tiempo, el bloqueo o el orden de las operaciones.