El servicio Identity and Access Management (IAM) de Google Cloud te permite crear y administrar permisos para los recursos de Google Cloud. Cloud IAM unifica el control de acceso para los servicios de Google Cloud en un solo sistema y presenta un conjunto coherente de operaciones.
Si quieres practicar habilidades más avanzadas de Cloud IAM, consulta el siguiente lab de Google Cloud Skills Boost, [Roles personalizados de IAM](https://www.cloudskillsboost.google/catalog_lab/955).

- Editor
- Propietario
- Visualizador

Estos son _roles primitivos_ en Google Cloud. Estos roles establecen permisos a nivel de proyecto y, a menos que se especifique lo contrario, controlan el acceso a todos los servicios de Google Cloud y la correspondiente administración.

En la siguiente tabla se proporcionan definiciones del artículo de Google Cloud IAM, [Roles básicos](https://cloud.google.com/iam/docs/understanding-roles#primitive_roles), que ofrece una descripción general breve de los permisos de los roles de navegador, visualizador, editor y propietario:

|   |   |
|---|---|
|**Nombre del rol**|**Permisos**|
|roles/viewer|Permisos para acciones de solo lectura que no afectan el estado, como leer (pero no modificar) los recursos o datos existentes.|
|roles/editor|Todos los permisos de lectura y permisos adicionales para acciones que modifican el estado, como cambiar recursos existentes.|
|roles/owner|Todos los permisos de edición, además de permisos para realizar las siguientes acciones:<br><br>- Administrar roles y permisos de un proyecto y todos los recursos dentro de este<br>- Configurar la facturación de un proyecto|![[mermaid-diagram-2025-04-24-160854.svg]]
