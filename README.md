# Programación Web 2
## Objetivos del sistema.
Este sistema tiene como objetivo el hacer una pagina de transacciones, en la que sea muy facil de usar por cada usuario. Esta pagina es muy simple ya que no existe tanta complejidad.
A su vez queremos que nuestros clientes tanto vendedores como compradores obtengan graficos de sus ventas y gastos.
## Descripción de funcionalidades.
Si hablamos del código como tal, entregaremos un pdf en el que documente todos los scripts y como funcionan.
Al hacer esta pagina hicimos uso de API's como lo es supabase, el cual es un servidor que tiene bases de datos y un lugar para almacenar toda clase de información.
Lamentablemente nuestra pagina no es segura, ya que es vulnerable a ataques de inyección SQL y hasta robo de credenciales, ya que no hicimos uso de Node para el backend,
todo y absolutamente todo esta desarrollado para el entorno del buscador. No existen Hasheos de contraseñas y no hay variables de entorno para hacer nuestra pagina mas segura.
Todo se resume a código JS que hace uso del LocalStorage para guardar una sesión y que al abrir o refrescar de nuevo la pagina no vuelva a pedir los datos, hicimos uso de JSON
no tanto para comunicarnos con la API de supabase, ya que esta no acepta JSON ni fetch, ya que dentro de sí las implementa. Sino que hicimos uso de JSON para guardar y recurperar cosas
del local storage. Tambien hicimos objetos que guardaban información tanto para SUPABASE como para la libreria de Graficas.
### Si se quiere saber como hicimos todos los códigos, estan dentro de la documentación.

## Como esta construido nuestro código?
Intentamos que cada uno de nuestros archivos sean como les hemos nombrado. El orden esta en dividir el documento en carpetas y en ellas se sabe que van a ser las cosas que contiene

## Como usar la pagina
Bueno básicamente creas una sesión o crear un nuevo usuario, en automatico te redirige a otra sección para comprar y vender cosas. Aqui no existen roles, puesto que es más complejidad.
Aquí cualquier persona es libre de comprar y vender a su gusto y ver sus transacciones que realizo.
### Punto importante
Si publicas algo, tu no vas a ver tus productos en la página principal, sin embargo otros usuarios si
