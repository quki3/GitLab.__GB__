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
## se usan para describir algun comportamiento a tener en cuenta en el codigo
(Guidance in the use of these Imperatives

   Imperatives of the type defined in this memo must be used with care
   and sparingly.  In particular, they MUST only be used where it is
   actually required for interoperation or to limit behavior which has
   potential for causing harm (e.g., limiting retransmisssions)  For
   example, they must not be used to try to impose a particular method
   on implementors where the method is not required for
   interoperability.)
- Security Considerations

   These terms are frequently used to specify behavior with security
   implications.  The effects on security of not implementing a MUST or
   SHOULD, or doing something the specification says MUST NOT or SHOULD
   NOT be done may be very subtle. Document authors should take the time
   to elaborate the security implications of not following
   recommendations or requirements as most implementors will not have
   had the benefit of the experience and discussion that produced the
   specification.
## para etiquetar tareas a los diferentes grupos
<a href="https://www.ietf.org/rfc/rfc2119.txt">Best Current Practice</a>

## issues

## boards

## list

## service desk
El Service Desk es la capacidad que te da Gitlab de abrir issues a través de correo electrónico.

    Permite dar soporte a través de email a tus clientes directamente desde Gitlab.
    Permite que el equipo no técnico reporte bugs o abra issue sin necesidad de que tengan una cuenta de Gitlab.
    Cuando se activa el servicio, se genera un email único para el proyecto.
## merges
- Los merge request, es la puerta entre el código de desarrollo y producción.
- En merge request es necesario saber si se corrigieron los issues, si se están introduciendo vulnerabilidades de seguridad, como es la performance de la aplicación.
- Es importante que los merge request sean atómicos, y no se encuentren ligados a varios archivos, con el fin de poder realizar revisiones a profundidad.
