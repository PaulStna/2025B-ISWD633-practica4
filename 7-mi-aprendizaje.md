# Mi Aprendizaje

Antes de realizar la práctica, no contaba con conocimientos sólidos sobre la gestión de contenedores y el control de recursos en Docker, aunque sí tenía nociones sobre los **healthchecks** y la construcción de imágenes con un **Dockerfile**.  

Durante la práctica, adquirí conocimientos que desconocía, como la **limitación de recursos en contenedores**, función que permite establecer restricciones de CPU y memoria para optimizar los recursos y mantener la estabilidad general del sistema. También pude reforzar mis conocimientos sobre **healthchecks**, que permiten la verificación periódica del estado de los contenedores, incluso antes de su inicialización, y facilitan el reinicio automático ante fallos.  

Asimismo, recordé la estructura y uso de **Dockerfiles** con instrucciones como `FROM` para definir imágenes base, `RUN` para ejecutar comandos, `COPY` para transferir archivos, `CMD` y `ENTRYPOINT` para comandos de inicio, y `EXPOSE` para documentar puertos.  

Además, aprendí sobre las cuatro **políticas de reinicio** que ofrece Docker, que desconocía en su totalidad: `no`, que no reinicia automáticamente; `always`, que reinicia siempre salvo detenciones manuales; `unless-stopped`, que respeta detenciones manuales; y `on-failure`, que solo reinicia ante códigos de error.  

Durante la práctica enfrenté un problema con imágenes de **CentOS**, que estaban deprecadas y no funcionaban correctamente. Personalmente lo resolví reemplazando la imagen base por **Rocky Linux**, una distribución compatible y estable que permitió construir y ejecutar los contenedores exitosamente para la realización de la práctica.
