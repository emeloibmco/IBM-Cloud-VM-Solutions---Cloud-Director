# IBM-Cloud-VM-Solutions---Cloud-Director




### 2. IBM Cloud Backup con Veeam Self-Service Portal
IBM Cloud VMware Solutions cuenta con el servicio de Veeam Self-Service Backup, esta herramienta tiene como principal ventaja es que no es necesario instalarlo en la maquina local sino que ya viene incluida dentro del servicio suministrado por IBM. Dentro de otras ventajas, se tiene que este portal ayuda a los usuarios a realizar operaciones de respaldo y restauración tanto de máquinas virtuales como de vApps. En la siguiente imágen podrá observar como acceder a este servicio.

![CD-3](https://user-images.githubusercontent.com/60628267/93234256-ae741700-f741-11ea-8fd4-2611f1c9575e.PNG)

Una vez ingresadas sus credenciales, siendo esta la misma con la que accedió a VMware Solutions, se procede a crear un Backup Job.

#### Crear un Backup Job.
Dentro de la pestaña _Jobs_ presione _+Crear_ tal como puede observar en la imágen a continuación.

<img width="617" alt="CD-2" src="https://user-images.githubusercontent.com/60628267/93233535-cd25de00-f740-11ea-9859-0d8bee3a7e7d.PNG">

Para la configuración es necesario que especifique el nombre del trabajo de respaldo, la descripción y la configuración de la política de retención. La política de retención define cuántos puntos de restauración se mantienen en el repositorio de respaldo y se pueden usar para la restauración de datos.

<img width="604" alt="CD-1" src="https://user-images.githubusercontent.com/60628267/93233042-3b1dd580-f740-11ea-98ba-d8c25e7538a8.PNG">

Una vez el paso anterior, haga clic en _Next_ y agregue una VM y/o una vApp a la que desea procesar el Backup.


