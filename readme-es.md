# Monitoreo de Hashtags (clipping) para Twitter.

## Ejecución Local
1. Descargar el proyecto utilizando GIT.
2. Abra el proyecto Maven utilizando el IDE de su preferencia
4. Completar el arthico twitter4j.properties con su información de autenticación.
5. Ejecutar el proyecto desde el IDE
> La Clase principal es com.monteiro.monitor.MonitorApplication.java

## Uso del sistema
1. Abra el navegador en http://localhost:8080/monitorv

### Incluir el Hashtag a Monitorear
1. Escribir el hashtag que desea que el monitor siga en el campo "Nuevo hastag" y haga click en "Insertar".
2. Agregar todos los hashtags que considere necesarios

### Visualizar los hastags
1. Seleccione el hastag deseado en el combo "hashtags monitoreados". La tabla se carga de manera automática 

### Eliminar un hashtag de la lista 
1. Seleccione el hastag deseado en el combo "hashtags monitoreados". 
2. Presional el boton "Remover"

> Obs.: El sistema llama a twitter cada 50 segundos.
> Al elimitar un hashtag, se borran todos los mensajes almacenados.
