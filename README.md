# IBM-Cloud-VM-Solutions---Cloud-Director




### 2. IBM Cloud Backup con Veeam Self-Service Portal
IBM Cloud VMware Solutions cuenta con el servicio de Veeam Self-Service Backup, esta herramienta tiene como principal ventaja es que no es necesario instalarlo en la maquina local sino que ya viene incluida dentro del servicio suministrado por IBM. Dentro de otras ventajas, se tiene que este portal ayuda a los usuarios a realizar operaciones de respaldo y restauración tanto de máquinas virtuales como de vApps. En la siguiente imágen podrá observar como acceder a este servicio.

![CD-3](https://user-images.githubusercontent.com/60628267/93234256-ae741700-f741-11ea-8fd4-2611f1c9575e.PNG)

Una vez ingresadas sus credenciales, siendo esta la misma con la que accedió a VMware Solutions, se procede a crear un Backup Job.

#### Crear un Backup Job.
Dentro de la pestaña _Jobs_ presione _+Crear_ tal como puede observar a continuación, es necesario que especifique el nombre del trabajo de respaldo, la descripción y la configuración de la política de retención. La política de retención define cuántos puntos de restauración se mantienen en el repositorio de respaldo y se pueden usar para la restauración de datos.

![2](https://user-images.githubusercontent.com/60628267/93346924-1f770580-f7fa-11ea-8707-34d979af9c12.gif)

Una vez el paso anterior, haga clic en _Next_ y agregue una VM y/o una vApp a la que desea procesar el Backup.

![3](https://user-images.githubusercontent.com/60628267/93348097-6adde380-f7fb-11ea-80e3-a2f980345204.gif)

En el paso _Notificaciones por correo electrónico_, es necesario habilitarlas y configure los ajustes de notificación, tales como:
- En el campo destinatarios, ingrese las direcciones de correo electrónico de los destinatarios separados por comas.
- En el campo Asunto, especifique el asunto de los correos electrónicos de notificación.(Ya viene un asusto predefinido).

![4](https://user-images.githubusercontent.com/60628267/93355123-556cb780-f803-11ea-9c2f-7856246468c7.gif)

Una vez creado el trabajo de respaldo, se deben iniciarlo por primera vez, seleccionandolo y haciendo clic en el botón _Start_.

![5](https://user-images.githubusercontent.com/60628267/93358813-8e0e9000-f807-11ea-977d-beb78212ed47.gif)




