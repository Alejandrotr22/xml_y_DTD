# xml_y_DTD
Este repositorio está dedicado a una tarea de dtd y XML

## ¿Qué se pide?
La Seguridad Social necesita un formato de intercambio unificado para distribuir la información personal de los afiliados.
Todo archivo XML contiene un listado de uno o mas afiliados Todo afiliado tiene los siguientes elementos:
   
   - DNI o NIE 
   - Nombre 
   - Apellidos 
   - Situación laboral: que tiene que ser una y solo una de entre estas posibilidades: «en_paro», en_activo, jubilado, edad_no_laboral 
   - Fecha de nacimiento: que se desglosa en los elementos obligatorios día, mes y anio. 
   - Listado de bajas: que indica las situaciones de baja laboral del empleado. Dicho listado consta de una repetición de 0 o más bajas: 
       - Una baja consta de tres elementos: causa (obligatoria), fecha de inicio (obligatorio) y fecha de final (optativa), 
   - Listado de prestaciones cobradas: consta de 0 o más elementos prestación, donde se indicará la cantidad percibida (obligatorio), la fecha de inicio (obligatorio) y la fecha de final (obligatorio). 

### Ejercicio

Lo primero que se tiene que hacer el dtd correspondiente

<div align="center">
<img width="100%" src="http://drive.google.com/uc?export=view&id=1d7WFSKyJAbrNfX_elt1i8e2ezslAEgZn">
</div>

Podemos ver que en este dtd he utilizado diferentes etiquetas, de las cuales la mayoría vaciás pero con atributos en ellas

<br>

Después de hacer el dtd así quedó el xml que completé a continuación 

<div align="center">
<img width="100%" src="http://drive.google.com/uc?export=view&id=1oY0jUYQ0bJR_hXI60EPPKj6hoZ3HUWRk ">
</div>


Y para ver si el código estaba correcto, utilicé una herramienta de comprobación dada por el profesor.

<div align="center">
<img width="100%" src="http://drive.google.com/uc?export=view&id=1D6RfZYvzcRGAwIAQJjCf0eGmilw-OFDI">
</div>

Dando 0 errores en el código.


























