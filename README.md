# IBM-Cloud-VM-Solutions---Cloud-Director




### 2. IBM Cloud Backup con Veeam Self-Service Portal
IBM Cloud VMware Solutions cuenta con el servicio de Veeam Self-Service Backup, esta herramienta tiene como principal ventaja que no es necesario instalarse en la máquina local puesto que ya viene incluida dentro del servicio suministrado por IBM. Dentro de otras ventajas, se tiene que este portal ayuda a los usuarios a realizar operaciones de respaldo y restauración tanto de máquinas virtuales como de vApps. En la siguiente imágen podrá observar como acceder a este servicio desde el Cloud Director.

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

Una vez creado el trabajo de respaldo, se debe iniciarlo por primera vez, seleccionandolo y haciendo clic en el botón _Start_.

![5](https://user-images.githubusercontent.com/60628267/93358813-8e0e9000-f807-11ea-977d-beb78212ed47.gif)

De igual manera en el panel encontrará los botones de _Stop_ y _Retry_ en caso de que se requieran.
Una vez terminado el proceso verá como cambia el status de _Working_ a _Success_. Adicional a lo anterior, será notificado al correo electrónico que suministró los detalles del Backup y su estado.

<img width="959" alt="Captura" src="https://user-images.githubusercontent.com/60628267/93362780-0a0ad700-f80c-11ea-8e6d-41ceb52a968a.PNG">



#### Restore VM/vApp
Si requiere restaurar el Backup de la VM o de la vAapp que creó, siga tal como se muestra a continuación:

![6](https://user-images.githubusercontent.com/60628267/93360787-b39c9900-f809-11ea-9656-cc4a2c8b323e.gif)

Aquí se habilitó la opción de que al finalizar la restauración de la VM se encienda, esto por temas de practicidad.
Para comprobar que satisfactoriamente se realizó el Backup de la VM, dirijase a _History_ en donde encontrará un recuento detallado paso a paso de este.

![7](https://user-images.githubusercontent.com/60628267/93361703-c6fc3400-f80a-11ea-9f99-37f540fd9d35.gif)

De igual manera, en el Cloud Director, volverá a ver su VM o vApp con el Backup que se hizo, en caso de que ésta halla sido suprimida. Con esta opción volverá a estar nuevamente en su dashboard.


