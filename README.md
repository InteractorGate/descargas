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

Actualización del 6 de noviembre de 2026: release pública `v1.2.3-r2`, aplicación
`1.2.3+8`, revisión de descarga 2. `InteractorGate-Setup.exe` tiene 97 730 116 bytes
(93,2 MiB). SHA-256:
`4be9e0497dc4f0a37ea1606b7522267b044f1f5c691d4062281a6355d84136be`.
La descarga queda fijada a esa release para que versión, tamaño y hash correspondan
al mismo archivo. La revisión 2 distingue la compilación actualizada de la
distribución anterior `v1.2.3`, que se conserva sin sobrescribir sus archivos.
Para registrar una evaluación, usar «1.2.3, revisión 2».

Incluye el login sin cámara, la calibración después de identificar al usuario,
el seguimiento solo al mostrar el tablero y la detención de la cámara al cerrar
sesión. ESC permite cancelar la calibración y existe una opción solo con mouse.
Las peticiones de identidad esperan hasta 75 segundos; telemetría conserva 15.
Se mantienen las correcciones de accesibilidad y las bibliotecas Visual C++ junto
al ejecutable Flutter. Verificación automatizada: 63 pruebas del cliente, 48 del
servicio, análisis sin incidencias y compilación del instalador satisfactoria.

`release-manifest.json`, incluido también en la release, conserva versión, revisión,
tamaño y hash del instalador. No incluye credenciales, datos de participantes ni
referencias al código privado. La instalación desde cero, la precisión ocular,
la evaluación con lector de pantalla y la validación con participantes siguen
pendientes. La publicación no acredita conformidad WCAG AA completa.

Para futuras versiones, actualizar juntos versión, fecha, tamaño, SHA-256, enlace
y aviso al evaluador después de construir y comprobar el instalador correspondiente.
