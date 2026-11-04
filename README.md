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

Verificación del 4 de noviembre de 2026: GitHub Pages responde HTTP 200 y la última
release pública es `v1.2.2`, publicada el 8 de octubre de 2026, con el archivo
`InteractorGate-Setup.exe` de 80 412 660 bytes. El digest publicado por GitHub coincide
con el SHA-256 mostrado en la página. La descarga queda fijada a esa release para
que versión, tamaño y hash correspondan al mismo archivo.

Esta release es anterior a las correcciones locales de accesibilidad de noviembre.
Antes de evaluar esas correcciones, construir y validar un instalador que las incluya,
publicar una nueva release y actualizar juntos versión, fecha, tamaño, SHA-256,
enlace y aviso al evaluador. La numeración pública `1.2.2` difiere de la versión
local declarada `1.0.6+7`; resolver esa diferencia antes de publicar el nuevo instalador.
