# Gestion de Usuarios SQL

La administración de usuarios dentro de una base de datos es uno de los aspectos más importantes en la seguridad informática y en la correcta organización de la información.

En este proyecto se desarrolló un ejercicio práctico enfocado en la creación de usuarios con distintos niveles de acceso sobre una base de datos, donde se configuraron tres roles fundamentales utilizados comúnmente en entornos empresariales y académicos.

Cada uno de estos usuarios fue diseñado con privilegios diferentes, de acuerdo con sus responsabilidades dentro del sistema, aplicando el principio de seguridad de mínimo privilegio, que consiste en otorgar solamente los accesos necesarios para cumplir una función específica.

Los roles trabajados en este proyecto fueron los siguientes:

> Usuario con permisos de solo lectura

Este usuario fue creado para consultar información sin posibilidad de modificarla. Tiene acceso únicamente al privilegio `SELECT`, por lo cual puede visualizar datos almacenados en las tablas.

No puede realizar acciones como:

- Insertar registros.
- Modificar información.
- Eliminar datos.
- Crear tablas.
- Alterar estructuras.

---

> Usuario con permisos de modificación

Este rol fue diseñado para personas encargadas de gestionar información dentro de la base de datos, permitiéndoles trabajar directamente con los registros almacenados.

Cuenta con permisos como:

- Consultar información.
- Insertar nuevos registros.
- Actualizar datos existentes.
- Eliminar información innecesaria.

Sin embargo, no posee privilegios administrativos, por lo tanto no puede:

- Crear tablas nuevas.
- Eliminar tablas existentes.
- Modificar estructuras.
- Administrar usuarios.

---

> Usuario administrador

Este usuario posee privilegios completos sobre la base de datos mediante `ALL PRIVILEGES`, lo que le permite ejecutar tareas avanzadas de administración y mantenimiento.

Entre sus capacidades se encuentran:

- Crear tablas nuevas.
- Modificar estructuras.
- Insertar, actualizar y eliminar datos.
- Gestionar respaldos.
- Eliminar tablas.
- Administrar objetos de la base de datos.


Debido al nivel de acceso que posee, este usuario debe asignarse únicamente a personas confiables y con experiencia técnica.

---

Durante el desarrollo del proyecto se realizaron pruebas prácticas para comprobar el correcto funcionamiento de cada rol, verificando que los permisos asignados coincidieran con las restricciones establecidas.

Además, se comprendió la importancia de segmentar accesos, ya que una mala asignación de privilegios puede ocasionar errores humanos, pérdida de información o vulnerabilidades de seguridad.

La correcta administración de usuarios en MySQL permite construir entornos más seguros, organizados y eficientes, donde cada persona trabaja únicamente con las herramientas necesarias según sus responsabilidades.


> Camila Andrea Oquendo Quintero 
@caoq28
> Melinda Camila Sanchez Mantilla
@Mila8-San
