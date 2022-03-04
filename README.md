# GitLab.__GB__

Administración: Nos da opciones de autenticación, autorización, analytics y self hosted gitlab.
Planificación: Nos da issues, milestones, burndown charts, discusiones, boards, service desk, to-dos, etc.
Creación: Generar proyectos, grupos, repositorios de código, merge request, integración y automatización.
Verificación: Correr pruebas automatizadas, calidad del código, review apps y code coverage.
Empaquetación: Container registry, paquetes privados.
Distribución(release): Deployment strategies, ambientes, Gitlab pages, feature flags.
Configuración: Existe la posibilidad de que debas cambiar la configuración de tu sistema. Auto DevOps, integración con Kubernetes, Knative serverless, manejo de secreto, chatops.
Monitoreo: Prometheus, Jaeger, Sentry.
Seguridad: Container scanning, dependency scanning, dynamic security testing, static security testing, manejo de licencias, security dashboard.
Defensa: Gitlab está trabajando en herramientas para esta etapa como Firewalls, threat detection, data loss prevention y más.

*install*
- <a href="https://about.gitlab.com/install/">install</a>
*seguridad*
- Username y Password
- Two factor authentication(2FA)
- SSH Key


Les comparto mi resumen por si es de su interés:

GRUPOS

Permiten compartir recursos entre varios miembros del equipo y poder organizar la forma en que trabajamos; permiten:

Agrupar proyectos
Otorgar permisos de acceso
Compartir recursos
Subgrupos: permiten modelar la forma en la que nuestra compañia está diseñada (2 equipos de Dev, 1 Diseñadores, 1 Directivos)

Los grupos se utilizan en GitLab a traves de “NAMESPACES”, lo que nos dará una url única para usuario, nombre de grupo y/o subgrupos

Nombres reservados para los grupos, las palabras reservadas son: https://docs.gitlab.com/ee/user/reserved_names.html

3 tipos de visibilidad:

1- Pública: cualquier usuario puede ver los contenidos de ese grupo
2- Interna: adentro de la instancia de GitLab (usuarios logueados) pueden tener acceso a ese grupo
3- Privada: Proyectos y grupos sean accesibles a traves de los permisos que se asignan en GitLab


#  labels
<a href="https://www.ietf.org/rfc/rfc2119.txt">Best Current Practice</a>
