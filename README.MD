# Descripcion
el presente documento esta realizado a forma de muestra sobre el futuro proyecto que se pretende desarrollar en el cual se describiran las acciones y objetos que estaran inmersos para el correcto funcionamiento, se pretende crear un sistema de bodega simple y se presentan como soluciones 2 opciones, una en forma instalable para algun computador con sistema operativo windows 7,8 o 10, con al menos 4 gigas en ram, 50GB de espacio de almacenamiento libre y con sus parches de seguridad al dia, el otro caso es un ambiente web alojado en un hosting que contendra una aplicacion web con un logeo de seguridad al iniciar y con sus respectivos niveles de acceso pensando en la seguridad de los datos como primer fuerte.
# Problematica
actualmente vuestra empresa cuenta con un nivel basico de registro en bodega, segun lo conversado con Francisco todos los procesos se estan ejecutando de forma manual, por esta razon se compro una pistola laser que lee codigos de barra, pero carece de software adicional y a medida que permita realizar estos procesos de forma automatica o generar informes relacionados a las faenas que en bodega se realizan.
los procesos que se contemplan para realizar el desarrollo son los siguientes:
## Carga de usuarios
Francisco indica que vuestra empresa cuenta con credenciales las cuales poseen codigo de barra, el sistema leera este codigo de barra y registrara el rut, el resto de campos se debe definir y ser llenado a mano dada la naturaleza del codigo de barra, los campos pueden ser Nombre, Telefono, Celular, Direccion, Area, Cargo, Jornada, Fecha de ingreso a la empresa, una vez el proceso de carga de usuarios esta realizado se puede continuar el flujo.
## Carga de articulos nuevos
los articulos deben poseer un codigo de barra lo cual le dara un identificador unico dentro del sistema, se tienen que definir los campos a llenar como por ejemplo, Nombre de articulo, Empresa del articulo, los campos de fecha de creacion se registraran de forma automatica al dar al boton salvar.
## Carga de articulos normal
al iniciar el proceso solicitara pistolear una credecial de un usuario para registrar quien esta realizando el procedimiento y la fecha en la cual se esta realizando(la fecha se tomara de forma autmatica al dia del computador), posterior a esto el usuario comenzara a pistolear articulos que ingresan a bodega, los cuales de estar registrados sumaran al inventario por cantidad de veces pistoleados los articulos, al cerrar este proceso el usuario debera pistolear nuevamente su credencial y con esto confirmar que la cantidad de articulos mostrados en pantalla es el correcto, una vez realizado estos pasos la informacion sera guardada de forma interna en el sistema.
## Despacho de productos
este proceso es identico al anterior pero descontara articulos de la bodega y solicitara confirmacion por pantalla antes de cerrar el proceso
## Modulo de reportes
el modulo de reportes contempla entregar un archivo CSV por faena realizada y tambien por el stock total de articulos en bodega.














