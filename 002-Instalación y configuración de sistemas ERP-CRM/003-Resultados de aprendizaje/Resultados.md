Resultado de aprendizaje 2
Resultado de aprendizaje
Implanta sistemas ERP-CRM interpretando la documentación técnica e identificando las diferentes opciones y módulos.

Criterios de evaluación

a) Se han identificado los módulos que componen el ERP-CRM.

Sí, la API del sistema, documentada en los ejercicios sobre módulos, identifica explícitamente "ventas", "rrhh", "facturacion" y "compras" como los componentes previstos.

b) Se han realizado diferentes tipos de instalaciones.

Sí, se evidencian diferentes versiones progresivas en la sección "Tipos de instalación" y se desarrolla un instalador web (`instalador.html`) diseñado para generar tablas dinámicamente a partir de un modelo de texto.	

c) Se han configurado los módulos instalados.

Sí, en el apartado de parámetros de configuración se introduce un archivo centralizado (`config.php`). Este archivo se utiliza para aplicar dinámicamente el nombre de la aplicación y sus variables de color en la interfaz del cliente.

d) Se han realizado instalaciones adaptadas a las necesidades planteadas en diferentes supuestos.

Sí, el sistema permite adaptar las instalaciones a distintas necesidades mediante la herramienta del instalador dinámico, poblando posteriormente la base de datos con supuestos específicos, como el escenario del sector aeronáutico presente en los archivos `demo.sql`.

e) Se ha verificado el funcionamiento del ERP-CRM.

Sí, se verifica el funcionamiento validando la correcta comunicación entre la arquitectura cliente-servidor, logrando extraer la información de la base de datos SQLite y renderizar las tablas en pantalla mediante peticiones JavaScript.

f) Se han documentado las operaciones realizadas y las incidencias.

Sí, el archivo `007-debug.md` documenta la gestión de incidencias detallando cómo habilitar los errores en PHP (`display_errors = On`) y cómo analizar los registros del servidor Apache (`error.log`df). Además, los documentos de texto adjuntos explican las justificaciones de la arquitectura.
