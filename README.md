# POC Elastic APM con Kibana y PHP

Este es un POC simple para demostrar la integración de Elastic APM con Kibana en una aplicación PHP.

## Requisitos

- Docker y Docker Compose instalados en tu máquina.

## Instrucciones

1. Clona este repositorio:

    ```bash
    git clone https://github.com/tu_usuario/tu-repositorio.git
    ```

2. Inicia los servicios de Elastic APM, Kibana y la aplicación PHP:

    ```bash
    docker-compose up -d
    ```

3. Accede a la aplicación PHP en tu navegador:

    [http://localhost:8080](http://localhost:8080)

6. Realiza algunas interacciones en la aplicación PHP para generar trazas APM.

7. Accede a Kibana en tu navegador:

    [https://localhost:5601](https://localhost:5601)

   - Usuario: `<tu_usuario>`
   - Contraseña: `<tu_contraseña>`

8. En Kibana, configura APM para ver las trazas generadas por la aplicación PHP.
MENU => Observability => APM => Add the APM integration => Settings => Install elascic apm assets.
