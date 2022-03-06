# CI
El Continuous Integration es una práctica en la que los desarrolladores envían sus cambios a un repositorio central, lo cual detona builds y pruebas automatizadas.

    Ayuda a encontrar bugs de manera oportuna
    Aumenta la velocidad de los releases
    Automatiza el pipeline que lleva código desde la computadora del desarrollador hasta el dispositivo del cliente.



    Trigger Variables: Son variables automatizadas cuando se detona un nuevo build.
    Project Variables (y Protected Variables): Son variables que se pueden definir para que
    sean expuestas únicamente en un proyecto específico o algunas ramas específicas.

    Group Variables: Son variables que se pueden definir para que estén expuestas en un grupo específico.

    YAML Job Level Variables and YAML Global Variables: Son variables que se pueden incluir en el archivo de configuración yaml.

    Deployment Variables: Son variables enfocadas a almacenar información o credenciales para la integración con servicios externos, por ejemplo kubernetes, para hacer el deploy del proyecto.

    Pre Defined Variables: Son variables predefinidas que se exponen por parte de GitLab en cada uno de los 
    trabajos de automatización.

# ci => CD (continuous delivery) deply a ambientes por ejemplo staging

