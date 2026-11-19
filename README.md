# InteractorGate · Descargas

Página de descarga del instalador de **InteractorGate**, una aplicación de comunicación
aumentativa y alternativa que se controla con la mirada mediante una cámara web común.

**Página:** https://interactorgate.github.io/descargas/

InteractorGate es un prototipo de investigación de un proyecto de tesis de Ingeniería de
Software (Universidad Peruana de Ciencias Aplicadas). La instalación la realiza el equipo
de investigación junto con cada participante, después del consentimiento informado.

Los instaladores están en [Releases](https://github.com/InteractorGate/descargas/releases).
Este repositorio contiene solo la página; el código fuente de la aplicación no se publica aquí.

Contacto: U20201F282@upc.edu.pe

## Evaluación técnica

La sección pública [Indicaciones para evaluadores](https://interactorgate.github.io/descargas/#evaluacion)
explica cómo recibir las credenciales por privado, registrar el entorno y completar
el Excel de casos. No publicar usuarios, contraseñas ni evidencias con datos sensibles.

Actualización del 19 de noviembre de 2026: release pública `v1.2.9`, aplicación
`1.2.9+14`. `InteractorGate-Setup.exe` tiene 98 566 348 bytes
(94,0 MiB). SHA-256:
`8af1c2f35342fa675d523ed3e2bd31d91561dad80211167a8bd1f233c008127e`.
La descarga queda fijada a esa release para que versión, tamaño y hash correspondan
al mismo archivo. Las distribuciones anteriores se conservan sin sobrescribir
sus archivos. Para registrar una evaluación, usar «1.2.9».

Novedad de la 1.2.9: actualización automática. En la pantalla de inicio de
sesión la app consulta `release-manifest.json`; si hay una versión más nueva,
ofrece instalarla, descarga el instalador solo desde las releases de este
repositorio, comprueba tamaño y SHA-256 y lo ejecuta en modo silencioso
(Windows pide permiso de administrador). La 1.2.9 se instala a mano una vez;
las siguientes llegan como aviso dentro de la app.

Novedades de la 1.2.8, a partir del feedback de los participantes: antes de
calibrar, una vista en espejo con óvalo guía comprueba rostro, distancia
aproximada (50 a 70 cm), centrado, cabeza derecha e iluminación; el botón
HABLAR pasa a la izquierda de la caja de texto y cerrar sesión pide
confirmación. Para actualizar basta con instalar encima de la versión anterior.

Novedad de la 1.2.7: el estudio E2 se reduce a la mitad. La práctica tiene 5
mensajes (bloques 3-2) y S2 y S3 tienen 10 frases cada una, en bloques
alternados 3-2-2-3. El avance guardado con la versión anterior del banco no se
conserva: el participante empieza desde la práctica. El sidecar de mirada usa
exactamente las mismas dependencias que la 1.2.5.

Novedad: modo discurso. El botón HABLAR, junto a la caja de texto, pronuncia el
mensaje con una voz neural de Azure AI Speech (es-PE) y DETENER la corta. Necesita
conexión a internet; el texto se envía a Azure solo para generar el audio y no se
guarda en el servidor del proyecto. Durante el estudio E2 el botón se oculta.

Incluye el login sin cámara, la calibración después de identificar al usuario,
el seguimiento solo al mostrar el tablero y la detención de la cámara al cerrar
sesión. Antes de calibrar se solicita autorización explícita: rechazar o cerrar
el permiso no inicia la cámara; se puede continuar con mouse o teclado físico.
El tablero permite desactivar la cámara y volver a la preparación. El permiso
se solicita de nuevo al calibrar y no sustituye el consentimiento del estudio
ni los permisos de Windows. ESC permite cancelar la calibración.
Las peticiones de identidad esperan hasta 75 segundos; telemetría conserva 15.
Se mantienen las correcciones de accesibilidad y las bibliotecas Visual C++ junto
al ejecutable Flutter. Verificación automatizada: 87 pruebas del cliente, 57 del
servicio, análisis sin incidencias y compilación del instalador satisfactoria.

`release-manifest.json`, incluido también en la release, conserva versión, revisión,
tamaño y hash del instalador. No incluye credenciales, datos de participantes ni
referencias al código privado. La instalación desde cero, la precisión ocular,
la evaluación con lector de pantalla y la validación con participantes siguen
pendientes. La publicación no acredita conformidad WCAG AA completa.

Para futuras versiones, actualizar juntos versión, fecha, tamaño, SHA-256, enlace
y aviso al evaluador después de construir y comprobar el instalador correspondiente.
