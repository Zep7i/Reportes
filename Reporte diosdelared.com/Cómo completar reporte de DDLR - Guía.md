# // Info.: Relleno de contenido
Todo lugar que se encuentre encerrado entre corchetes de la siguiente manera: [X] debe ser  
rellenado por el/los auditor/es correspondiente/s conforme a como se requiera en cada  
apartado. No escribir en el reporte todo apartado que contenga "//" por delante de su texto  
ya que es informativo y sirve para explicar que debe rellenar el auditor/auditores, aunque  
no siempre puede estar presente ya que se especifica directamente

# // Info.: Tarjeta de presentación (1 Hoja)
Debe adjuntarse en este apartado una tarjeta de presentación como un logotipo, imagen, etc.  
que lo represente a usted como auditor o a su equipo de auditoria para dar su presentación.  
Esta debe contener:

- Logotipo
 - Su nombre completo o el nombre de su equipo de auditoria (Puede utilizar apodos si  
así lo prefiere para más anonimato)
- Fecha y año de cuando se terminó de rellenar el reporte
- Versión del reporte (Si es su primer reporte para ese aplicativo en cuestión, su  
versión será la 1.0 por defecto)

# Resumen
En este apartado se comentan algunas de las vulnerabilidades que se han encontrado en el  
aplicativo, se habla como esto puede afectar a la web/activos y que se listarán todas las  
vulnerabilidades encontradas no siendo así significado de que sea un reporte absoluto de  
todas las vulnerabilidades habidas y por haber que pudo, tenga o tendrá el aplicativo en  
cuestión.

Finalizamos mostrando un recuento de la cantidad de vulnerabilidades con su categoría de  
severidad correspondiente, ejemplo:

Crítico: 0 / Alto: 0 / Medio: 0 / Bajo: 7 / Informativo: 2

# Tabla de contenidos
## Introducción
### Limitaciones y descargo de responsabilidad
Se especifica las limitaciones que tiene/tienen el/los auditor/auditores para realizar ciertos  
ataques debido ya sea al scope o a cierta información faltante o desconocida sobre el  
aplicativo. Se aclara que tipo de prueba de penetración se ha realizado (Bajo que términos y  
condiciones o conocimientos previos a la prueba) por ejemplo:

Prueba de penetración de tipo White-Box / Black-Box / Gray-Box – Se vuelve a especificar  
el scope permitido ya que este es un factor delimitador el cuál debe respetarse.
### Personal involucrado
Se específica los miembros conformes que auditaron el aplicativo.
### Calificación del riesgo
Se específica en base a qué metodología se está evaluando el nivel de riesgo de cada  
vulnerabilidad explayada en el reporte, por ejemplo, puede utilizar la metodología de  
"OWASP Risk Rating". Es importante que explaye de manera entendible y legible cómo  
funciona la metodología que usted cree conveniente para evaluar la severidad de las  
vulnerabilidades mencionadas en el reporte para que el cliente entienda a la perfección.

Adjuntar la definición sobre los riesgos generales, ejemplo:  
El riesgo global refleja la estimación del riesgo que un hallazgo supone para el sistema o  
sistemas objetivo. Tiene en cuenta el impacto del hallazgo, la dificultad de explotación y  
cualquier otro factor relevante. Crítico: Implica una amenaza inmediata y fácilmente  
accesible de compromiso total.  
Alto: Implica una amenaza inmediata de compromiso del sistema, o una amenaza  
fácilmente accesible de violación a gran escala.  
Media: Amenaza de violación a gran escala difícil de explotar, o amenaza fácil de una  
pequeña parte de la aplicación.  
Baja: Implica una amenaza relativamente menor para la aplicación.

Informativa: Ninguna amenaza inmediata para la aplicación. Puede proporcionar  
sugerencias para la mejora de la aplicación, o condiciones que podrían conducir más tarde a  
un hallazgo explotable.

Adjuntar la definición sobre impacto, ejemplo:
El impacto refleja los efectos que una explotación exitosa tiene sobre el sistema o sistemas  
objetivo. Tiene en cuenta las pérdidas potenciales de confidencialidad, integridad y  
disponibilidad, así como las pérdidas potenciales de reputación. Alto: Los atacantes pueden  
leer o modificar todos los datos de un sistema, ejecutar código arbitrario en el sistema o  
escalar sus privilegios a nivel de superusuario. Media: Los atacantes pueden leer o  
modificar algunos datos no autorizados en un sistema, denegar el acceso a dicho sistema u  
obtener información técnica interna significativa. Bajo: Los atacantes pueden obtener  
pequeñas cantidades de información no autorizada o degradar ligeramente el rendimiento  
del sistema. Pueden tener una percepción pública negativa de la seguridad.

## Observaciones - [X]
En X colocar el nombre del apartado de la vulnerabilidad explicado más adelante.
## [X1].[Z1]
X1 debe ser el número en orden en el cual se anuncia la vulnerabilidad, al ser la primera  
vulnerabilidad para expresar en la tabla de contenidos, colocar "1", si Z1 es mayor a "9"  
entonces, se completa como "2" teniendo como máximo 9 (nueve) Z1 por cada X1.

Z1 debe ser el número en orden en el cual le sigue a X1, en caso de que X1 sea igual a "1" y  
sea la primera vulnerabilidad para expresar en la tabla de contenidos entonces Z1 será igual  
a "1", si fuese la segunda vulnerabilidad entonces X1 seguiría siendo "1" pero Z1 cambiaría  
a "2".

Nota: Se aplica por cada apartado individual.
## Vulnerabilidades Informativas
## Conclusiones y recomendaciones finales
## Referencias
# Observaciones
## [X]
Este apartado debe ser rellenado como subtitulo, haciendo referencia al apartado de la  
aplicación a la cual se le informará de la vulnerabilidad encontrada en la plantilla posterior,  
ejemplo:  
LOGIN  
REGISTRO 
ADMIN 
PANEL 
HOME 
Por favor añadir la cantidad de plantillas sobre la  
explicación de cada vulnerabilidad correspondiente para cada apartado como corresponda.
## [X1].[Z1]
X1 debe ser el número en orden en el cual se anuncia la vulnerabilidad, al ser la primera  
vulnerabilidad para explicar sobre la plantilla se completa como "1", si Z1 es mayor a "9"  
entonces, se completa como "2" teniendo como máximo 9 (nueve) Z1 por cada X1.

Z1 debe ser el número en orden en el cual le sigue a X1, en caso de que X1 sea igual a "1" y  
sea la primera vulnerabilidad que se esté explicando entonces Z1 será igual a "1", si fuese  
la segunda vulnerabilidad entonces X1 seguiría siendo "1" pero Z1 cambiaría a "2".

Nota: Se aplica por cada apartado individual.
## // Plantilla (Sólo escribir la plantilla y rellenar)
// (Puede que haya ciertos campos que no puedan ser rellenados por el auditor, ejemplo:  
Falta de información o reciente descubrimiento de un "0day", etc.)

Nombre: // Nombre que usted le colocará para identificar esta vulnerabilidad
Descripción: // Descripción breve sobre la vulnerabilidad
Riesgo: // Definir el impacto y el riesgo general de la vulnerabilidad de forma
cualitativa y cuantitativa.
Tipo de vulnerabilidad: // Explicitar el tipo de vulnerabilidad, ejemplo: XSS, CSRF,
etc.
Categoría: // Explicitar a que categoría pertenece la vulnerabilidad.
Ubicación de explotabilidad: // Explicitar en dónde sucede esta vulnerabilidad en
cuestión, adaptándose a los scopes permitidos.
Impacto real: // Explicar cuál es el impacto que se pudo ver del lado del auditor o el
grupo de auditores al explotar la vulnerabilidad. (No en todos los casos es posible
debido a las limitaciones que se hayan impuesto, aclaradas anteriormente en el
apartado de Limitaciones y Descargo de responsabilidad)
Pasos a seguir: // Explicar todos y cada uno de los pasos que se realizaron desde el
reconocimiento que llevó a identificar un posible vector de vulnerabilidad hasta la
explotación satisfactoria de la misma y las herramientas y/o metodologías utilizadas de
por medio.
Recomendaciones: // Realizar recomendaciones sobre la contramedida/defensa
aplicada a la vulnerabilidad en cuestión.

# Vulnerabilidades Informativas

// (X se completa con un número inicialmente desde el "1" hasta infinito dependiendo sea el  
caso y en orden)  
Nota N°[X]: // Se brinda algún tipo de aclaración adicional sobre el aplicativo (No  
necesariamente relacionado con la seguridad) o vulnerabilidad informativa la cuál no  
dispone de un impacto real pero podría ser escalable a que lo fuese.

# Conclusiones y recomendaciones finales
En este apartado se tratan las conclusiones sobre el aplicativo en el cual se realizó la  
auditoria, aclarando cualquier cosa que haya quedado pendiente o desee añadir para  
finalizar, asimismo con las recomendaciones siendo o no relacionadas con la seguridad en  
sí del aplicativo.

# Referencias
Siempre que se hable sobre otro sitio, institución, aplicación o se cite/nombre o usted  
considere el caso, debe escribirse en el formato siguiente:

nombre [X]

Finalmente, en este apartado debe adjuntarse el vínculo/url/enlace de la referencia en  
cuestión, en el siguiente formato:

[X] nombre vínculo/url/enlace (Clickeable)

# // Info.: Ejemplo de categorías para utilizar
Controles de acceso: Relacionados con la autorización de usuarios y la evaluación de  
derechos.  
Auditoría y registro: Relacionado con la auditoría de acciones o el registro de problemas.  
Autenticación: Relacionado con la identificación de usuarios. Configuración: Relacionado  
con las configuraciones de seguridad de servidores, dispositivos o software. Criptografía:  
Relacionado con la protección matemática de los datos. Exposición de datos: Exposición  
involuntaria de información sensible. Validación de datos: Relacionado con la confianza  
indebida en la estructura o los valores de los datos. Denegación de servicio: Relacionado  
con provocar fallos en el sistema. Notificación de errores: Relacionado con la notificación  
de condiciones de error de forma segura. Parcheado: Relacionado con mantener el software  
actualizado. Gestión de sesiones: Relacionado con la identificación de usuarios  
autenticados. Tiempo: Relacionado con las condiciones de tiempo, el bloqueo o el orden de  
las operaciones.