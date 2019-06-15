
# Introducción
 
### Descripción básica
Redmine es un planificador y gestor de proyectos.

### Características
<div class=text-justify>

Se pueden crear dos tipos de proyectos, públicos y privados. Los proyectos públicos son visibles para todo el mundo mientras que los proyectos privados son gestionados por los administradores que dan accesos a los usuarios. En los dos casos se puede dividir el proyecto en subproyectos. Existen roles definidos por proyecto, de modo que un mismo usuario puede tener distintos roles en los proyectos que participe.

Entrando en cada proyecto vemos que es muy personalizable. Según el objetivo del proyecto podemos activar o desactivar diferentes módulos en cualquier combinación como wiki, foro, noticias, peticiones, control del tiempo, documentos y ficheros (repositorio). Hay módulos que son comunes para todos los proyectos como el de actividad y vistazo. 

El sistema de peticiones es muy útil. Se dividen en errores, tareas y soporte. Pueden ser asignadas a un miembro, se les puede establecer fecha de inicio, fecha de fin, prioridades y categorías. Con un sistema de control de tiempo y porcentaje realizado. Esta tarea creada de forma personalizada se puede asociar a subida de uno o varios ficheros. El usuario podrá visualizar las peticiones que tiene asignadas mediante filtros y ordenación. Un proyecto puede establecer versiones y asignar tareas a determinadas versiones. De modo que el porcentaje irá avanzando automáticamente a medida que se marquen tareas realizadas.
	
Se puede integrar con un repositorio de código que esté montado en la misma máquina indicando el directorio local. De esta manera la aplicación sirve de interfaz web pudiendo descargar los ficheros, ver los cambio, el historial e incluso descargar un archivo a modo de parche de para aplicar a código desactualizado. Es un sistema de seguimiento de versiones de modo que no se pueden actualizar los ficheros directamente.

Para visualizar todas las peticiones se puede utilizar calendario o diagrama de Gantt. A esto le podemos aplicar filtros para visualizar exactamente lo que necesitemos.
Si se configura el servidor de correo SMTP, se pueden recibir notificaciones de los proyectos. Cada usuario puede personalizar las notificaciones que le llegan por correo. Mediante correo se pueden actualizar y crear tareas. Toda la actividad se puede exportar en Atom para ser seguida desde un lector RSS. Se active o esta configuración, todos los proyectos tienen un módulo de actividad que refleja todo el flujo por día en el proyecto y lo muestra en una lista.

Si se necesita exportar la información, se pueden aplicar filtros y exportar los resultados en formato PSD o CSV para poder trabajar con los datos de una forma ordenada. Las páginas de wiki, en cambio pueden exportarse en formato HTML o TXT.

Cada usuario tiene una página personal personalizable donde puede visualizar los distintos proyectos donde participa, calendarios globales e incluso una barra de buscador. Puede añadir módulos personalizados y ampliar la funcionalidad con las numerosas extensiones que tiene. Se admite como base de datos de MySQL, SQLite y PostgreSQL.

Algunas carencias se pueden apreciar en la complejidad de la instalación de la aplicación. Siendo muy delicada y con poca documentación al respecto.
</div>

### Multiplataforma y requisitos
Redmine es una aplicación servidor multiplataforma basada en Ruby on Rails. Los únicos requisitos para instalar Redmine en una máquina son: una base de datos (que puede ser MySQL, PostgreSQL o SQLite), Ruby y Ruby on Rails en sus versiones apropiadas. Si una máquina sostiene esto, puede instalarse Redmine independientemente de la plataforma. Rails funcionará sobre cualquier sistema operativo.
A nivel de cliente, Redmine puede ser accedido desde cualquier plataforma o sistema operativo, tan solo hace falta conexión a la red apropiada y un navegador de internet.

### Plugins
Redmine dispone de muchos y muy variados Plugins. Se pueden consultar en: http://www.redmine.org/wiki/redmine/Plugin_List

En la lista vienen los autores de cada uno, una pequeña descripción, versión compatible y de dónde obtenerlo. Pinchando en cada uno se visualiza una ficha específica para cada plugin, con información adicional como la instalación, la actualización o capturas.

### LICENCIA / DISTRIBUCIONLicencia
La licencia de la aplicación es GPL v2 y se puede consultar en:
http://www.gnu.org/licenses/gpl-2.0.html

	En donde se define como software libre con todo lo que ello implica. Se descarga de forma gratuita desde: 
http://www.redmine.org/wiki/redmine/Download
Desde la propia página no se ofrecen servicios o soporte sobre Redmine porque está mantenido por una comunidad de voluntarios, pero existe una gran cantidad de empresas que trabajan con ella y ofrecen instalaciones, soporte, formación o desarrollos.
