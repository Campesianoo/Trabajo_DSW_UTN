# Propuesta TP DSW

## Grupo
### Integrantes
* 50390 - Cabardos, Matias
  52331 - Degiovanni, Bianca
  52199 - Kasperczak, Ian
  
### Repositorios


## Tema
### Descripción
El gimnasio Power Trainer nos convocó para realizar un sistema que permita administrar el flujo de personas en el mismo. 
Diariamente los clientes ingresan a la aplicación para reservar un turno y realizar actividades dentro del gimnasio. A lo largo del día los profesores del gimnasio dictan dos tipos de clases: musculación y crossfit. Cada clase tiene una cantidad de cupos limitados para un determinado día y horario, es por ello que los clientes deberán anotarse con anticipación.   

### Modelo
https://drive.google.com/file/d/1_nS8bmaKZF69zily-P3Q4HlUUluL-mYP/view?usp=sharing


## Alcance Funcional 

|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Cliente <br>2. CRUD Profesor <br>3. CRUD Salon <br>4. CRUD Especialidad|
|CRUD dependiente|1. CRUD Actividad {depende de} CRUD Profesor y CRUD Salon <br>2. CRUD Membresia {depende de} CRUD Cliente|
|Listado<br>+<br>detalle| 1. Listado de Clientes con membresia vencida=> detalle CRUD Cliente <br> 2. Listado de clases del dia => detalle muestra los clientes anotados en la clase|
|CUU/Epic|CUU_1  Reservar turno para realizar una actividad en un determinado día y horario.<br> CUU2_ Registrar asistencia del alumno a la clase|

La data registrada por el CUU_1 sirve como Input para el CUU_2.


