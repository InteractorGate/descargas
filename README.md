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

Actualización del 4 de noviembre de 2026: release `v1.2.3`, aplicación `1.2.3+8`, con
`InteractorGate-Setup.exe` de 97 686 728 bytes (93,2 MiB). SHA-256:
`6a3e46f83d02f87d24ce9a20dfc505f3cb4db17fdfb48ccd3e1efa45bcdbbee0`.
La descarga queda fijada a esa release para que versión, tamaño y hash correspondan
al mismo archivo. La numeración continúa después de la release pública 1.2.2;
reemplaza la referencia local anterior 1.0.6+7.

Incluye las correcciones locales de accesibilidad y reconstruye la app Flutter y
el servicio de mirada. Verificados: 52 pruebas del cliente, 41 del servicio,
análisis estático sin incidencias y tres pruebas de arranque del servicio empaquetado
sin cámara. Se incluyen bibliotecas Visual C++ junto al ejecutable Flutter.

`release-manifest.json` conserva tamaño, hash y huellas del código utilizado; la
compilación incluye cambios locales sobre el commit base allí indicado. No se
publica el código fuente de la app. La instalación en otro equipo y las pruebas
con cámara, lector de pantalla y participantes siguen pendientes.

Para futuras versiones, actualizar juntos versión, fecha, tamaño, SHA-256, enlace
y aviso al evaluador después de construir y comprobar el instalador correspondiente.
