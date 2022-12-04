# Proyecto_Agile

# Indice

### - [Postwork Sesion 01](#postwork-sesion-01)
### - [Postwork Sesion 02](#postwork-sesion-02)
### - [Postwork Sesion 03](#postwork-sesion-03)
### - [Postwork Sesion 04](#postwork-sesion-04)
### - [Postwork Sesion 05](#postwork-sesion-05)




## Postwork Sesion 01

### -- Descripción
El proyecto en este repositorio es el desarrollo de las actividades de postworks que se encuentran en la plataforma de Bedu relacionadas con el curso de HSBC, al cual me encuentro inscrito.

Ls actividades realizadas corresponden a la primera fase del curso, el cual me permitira alcanzar el nivel de Senior Enginnering Java.

Buscare la forma de usar los 12 principios de la meotodologia Agile, asi mismo usare la filosofia de *Kanban* para llevarlo a acabo.

Se usara *Kanban* debido a las condiciones del proyecto en donde se realizará un tablero en donde definire los siguientes tipos de tareas:

* Tareas por hacer
* Tareas en Proceso
* Tareas finalizadas

Para la creación del tablero usaremos la herramienta que nos proporciona *GIT* para tener un mejor control y comunicación de las distintas tareas.

Asi mismo las tareas se definiran, realizaran y terminaran de acuerdo a los principios de *Kanban* los cuales se enuncian a continuación:

- Visualización 
- Priorizacion
- Mejora continua
- Liderazago en todos los niveles
- Calidad garantizada

## -- Tablero Kanban

Acceso al Tablero [Kanban](https://github.com/users/Angel123Lara/projects/1/views/1) definido con la herramienta en GITHUB.


## Postwork Sesion 02
### -- Fundamentos de Scrum

En el entregable de esta sesion se realizara analizando los fundamentos de Scrum y como se aplicaran sobre nuestro proyecto en curso.

En Scrum tenemos herramientas llamadas ceremonias las cuales se describen a continuación

- Sprin Planning -. Se trata de revisar lo que se tiene que realizar y como se tiene que realizar el trabajo durante el Sprint

- Sprint Review -. Se revisa el avance y se muestra evidencia, asi como se mencionan detalles que hayan impedido realizar algun trabajo durante el sprint.
  

- Retrospective -. En esta parte de trata de analizar todos los problemas que se presentaron durante el sprint y se negocia con las partes interesadas para evitar que en los proximos sprint no existan tantos contratiempos.

### -- Roles Centrales

- Product Owner -. Es aquella persona que sabe sobre el area del proyecto y es quien realiza los requirimientos y validaciones sobre el proyecto.

- Scrum Developer -. Es quien sabe sobre toda la metodología Scrum y esta al 100% concentrando en el proceso del sprint y busca soluciones ante posibles problemas, ademas es quien informa sobre el proceso al Product Owner.

Referente a nuestro proyecto solo contaremos con la figura principal de Scrum developer debido a que es un proyecto personal.

### -- Valores SCRUM

Los valores en SCRUM son 5 pero de los cuales en nuestro proyecto aplicaremos los siguientes debido a la naturaleza del mismo.

- Coraje: Los miembros de Scrum tienen el coraje de hacer lo correcto y trabajar en problemas difíciles.

Compromiso: Las personas se comprometen personalmente a alcanzar los objetivos del equipo de desarrollo.

### -- Principios SCRUM

Los principios SCRUM que mas identifico en mi proyecto son los siguientes:

- Control empirico de proceso
¿Por que? - 
existira transperencia a lo largo del desarrollo del proyecto mostrando en cada postwork un feedback del proceso y del resultado de cada actividad

- Auto organización
¿Por que? -
porque se buscara de manera ordenada la meta final para la entrega del proyecto y se concentraran todos los esfuerzos hasta conseguirlos.

- Priorizacion basada en valor
¿Por que?
porque a lo largo del desarrollo de cada entregable se prioriza los cuales se necesite mas enfoque para lograr el objetivo, asi como buscar la priorización de las tareas.

### -- Aspectos

En el desarrollo del proyecto se buscara tener los siguientes aspectos principalmente.

- Organización. Entender los roles y responsabilidades definidos en un proyecto Scrum es muy importante con el fin de asegurar la implementación exitosa del método de Scrum.

- Calidad. Es la capacidad del producto o los entregables de cumplir con los criterios de aceptación

- Riesgo. El riesgo se define como un evento o conjunto de eventos inciertos que pueden afectar los objetivos de un proyecto y pueden contribuir a su éxito o fracaso.


## Postwork Sesion 03

En el siguiente link se encuentra el repositorio del postwork de la sesión 03

[Repositorio Java con Test NG](https://github.com/Angel123Lara/HSBC_Sesion03/tree/master)

##  Postwork Sesion 04

El postwork de la sesion 04 se realizó con la herramienta de Docker a traves de la terminal siguiendo las insutrucciones se logro completar el postwork generando los siguientes entregables:

#### -- Ultima versión del Docker instalada

![Imagen version Docker](/src/imgs/Sesion04/VersionDocker.jpg)
version docker

#### -- Comando básicos Docker

```
Docker pull <nombre_imagen>
```
Con este comando descargamos de un repositorio la imagen que deseamos, tambien podemos especificar que versión de la imagen deseamos en dado caso que existan varias versiones.

```
Docker images
```
Nos muestra en terminal la información detallada de las imagenes que tenemos en nuestro sistema.

```
Docker run -d --name <imagen> -p <puerto>:<puerto> <nombre que definimos>
```
Ejecuta una instancia de la imagen Docker, es importante declara el puerto con el que trabajara esta imagen para poder comunicarnos con dicha imagen.
En este comando especificamos la imagen que vamos a instanciar y el nombre con el que queremos identificarlo

```
Docker ps
```
Muestra en pantalla los contenedores en ejecución.

```
Docker exec -it <CONTAINER> bash
```
Accede a la terminal del contenedor esto nos ayuda a ejecurar comandos desde el interior del contenedor.

```
Docker start <CONTAINER>
```
inicia un contendedor para comprobar que el contenedor arranco correctamente puedes usar el comando *Docker ps*

#### -- Servidor de aplicaciones

![Servidor de aplicaciones](/src/imgs/Sesion04/ImagenDocker_httpd.jpg)

#### -- Modicación de página principal

![Pagina de inicio modificada](/src/imgs/Sesion04/PaginaModificada.jpg)

##### -- Feedback de postwork 04

Al realizar este postwork me ayudo a familiarse mas con Docker y sus comandos, asi como entender mas su funcionamiento y aplicación

##  Postwork Sesion 05

Para la realización del postwork se creo un repositorio nuevo al cual podemos acceder con el siguiente link

[Repositorio DevOpsBeduReto02](https://github.com/Angel123Lara/DevOpsBeduReto02)

se deja evidencia de lo realizado en el repositorio

#### -- Creacion repositorio

![Repositorio nuevo](/src/imgs/Sesion05/Creando_repo.jpg)

#### -- Repositorio creado

![Repositorio creado](/src/imgs/Sesion05/repo_creado.jpg)
 
 #### -- Branch en repositorio local
 ![Branch](/src/imgs/Sesion05/inciso_a.jpg)
 
 #### -- Pull request
 ![Pull request](/src/imgs/Sesion05/evidenciaPullrequest.jpg)
 
 #### -- Buena práctica eliminar branch de pull request
 ![BuenaPractica](/src/imgs/Sesion05/branchMainonly.jpg)
 
 ## - [Postwork Sesion 06](#postwork-sesion-06)
 
 En el siguiente link se encuentra el repositorio que se creo con las actividades del postwork 06
 
 [Repositorio Sesion 06](https://github.com/Angel123Lara/Sesion06_BEDU_HSBC)
 
 #### Terraform instalado
 
 ![Terraform version]((src/imgs/Sesion06/terraform version.jpg)
 
 #### Comandos basicos de terraform
 
 ##### terraform –version
      se utiliza para checar que la version de terraform y darnos cuenta que tenemos instalado terraform en nuestra computadora
      
##### Terraform init
    Se utiliza para iniciar un proyecto de terraform
    
##### terraform plan
    Crea un plan de ejecucion pero no lo ejecuta determina las acciones necesarias para crear la configuracion especificada.

#### terraform apply
  se utiliza para aplicar los cambios necesarios para alcanzar el estado deseado de la configuración, o el conjunto predefinido de acciones generado por un plan ejecución.

#### terraform destroy
  Es capaz de eliminar toda la infraestructura con base en la configuración.
  
### Primer despliegue desde terraform

![Despligue browser](/src/imgs/Sesion06/despliguebrowser.jpg)

![Comandodespliegue](/src/imgs/Sesion06/comandosdespligue.jpg)

![Terraform init](/src/imgs/Sesion06/terraform_init.jpg)

![Terraform apply](/src/imgs/Sesion06/terraformapply.jpg)

![microservicios](/src/imgs/Sesion06/contenedormicroservicios.jpg)

 
 







