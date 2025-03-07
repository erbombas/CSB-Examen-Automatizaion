# CSB-Examen-Automatizacion
Examen para candidatos vacante “Ingeniero de Calidad” Consubanco

Puntos a Evaluar

E2E:

1. Estrategia de pruebas según la HU descrita
1. Todos los Test corren correctamente
2. Genera scenarios outline con consumo csv o json
3. Genera los Task, user interface, model etc correctamente
4. Genera Readme con las instrucciones del test
5. La entrega del código debe realizarse a través de un repositorio de Git personal.



Con el objetivo de comprobar el conocimiento de automatización
Como Consubanco
Requiero realizar las validaciones E2E del aplicativo facilitado

CA01
Dado que abrimos la apk 
Cuando se nos muestra la pantalla inicial
Entonces se mostrarán los textos ”The App” y “Choose An Awesome View”

CA02
Dado que abrimos la apk 
Cuando hacemos clic “Login Screen”
Entonces nos abrirá la pantalla del Login    

CA03
Cuando llenamos los campos requeridos
Entonces nos abrirá la pantalla del Login con el botón “Logout” y el text “Secret Area”

CA04
Cuando hacemos click en el botón “Logout”
Entonces redirecciona a la pantalla de Login

CA05
Cuando hacemos click en la flecha de atrás de la esquina superior izquierda
Entonces redirecciona al home de la apk.

CA06
Cuando hacemos clic en el link “List Demo/Fog” y luego en “Learn More About Fog”
Entonces se mostrará una pantalla con el texto “Fog”

CA07
Dado que hace clic  en el link “ClipBoard Demo”
Cuando Ingrese el texto “Consubanco” en el campo, haga clic en el botón “Refresh ClipBoard Text”
Entonces se replicará el texto ingresado en la pantalla

 
E2E WEB: 

1. Estrategia de pruebas según la HU descrita 
2. Todos los Test corren correctamente 
3. Genera los Task, user interface, model etc correctamente 
4. Genera Readme con las instrucciones del test 
5.La entrega del código debe realizarse a través de un repositorio de Git personal.

URL: https://www.demoblaze.com/index.html 

Con el objetivo de comprobar el conocimiento de automatización 
Como Consubanco 
Requiero realizar las validaciones E2E de la página facilitada 

CA01 
Dado que ingresamos a la url demoblaze 
Cuando se nos muestra la pantalla inicial 
Entonces hacemos clic en “Sing UP” para crear una cuenta 

CA02 
Dado que contamos con una cuenta 
Cuando se nos muestra la pantalla inicial 
Entonces hacemos clic en “Log in” para ingresar con nuestra cuenta 

CA03 
Dado que hicimos login 
Cuando se nos muestra la pantalla inicial 
Entonces nos debe aparecer nuestro nombre de usuario en la esquina superior derecha. 

CA04 
Dado que nos encontramos en la pantalla inicial 
Cuando hacemos clic en la categoría de “Phone” 
Entonces nos debe mostrar el listado de “Phone”

 CA05 
Dado que nos encontramos en el listado de Phones 
Cuando hacemos clic en “Samsung galaxy s6 ” 
Entonces nos debe mostrar el label “Product description” 
CA06 
Dado que nos encontramos en la página del detalle “Samsung galaxy s6 ” 
Cuando hacemos clic en “Add to Cart ” 
Entonces nos debe mostrar un modal con el mensaje “Product added” 

CA07
 Dado que nos encontramos en la página del detalle “Samsung galaxy s6 ”
 Cuando hacemos clic en la opción “Cart” del menú 
Entonces nos debe mostrar el producto agregado en nuestro carrito de compra 

CA08 
Dado que nos encontramos en nuestro carrito de compras 
Cuando hacemos clic en la opción “Delete” 
Entonces nos borrar el producto del listado 

CA09 
Dado que nos encontramos en nuestro carrito de compras 
Cuando hacemos clic en la opción “Log Out” 
Entonces nos debe sacar de nuestra sessión y redireccionar a la página principal de demoblaze . 


APis

Puntos a Evaluar

1. Test corren correctamente (todos los métodos)
2. Genera los informes
3. Genera los features optimizados y utilización de variables
4. Genera escenarios outline con consumo csv o json
5.La entrega del código debe realizarse a través de un repositorio de Git personal.

Consulta en la siguiente URL del swagger el contrato de la api para gestionar
Mascotas:

URL Swagger: https://petstore.swagger.io/#/pet/updatePet
API: https://petstore.swagger.io/v2/

1-Adiciona una mascota nueva donde el nombre tenga el siguiente formato:
Pug_Luna
2-Verifica que la mascota está agregada correctamente
3-Modifica el nombre de mascota por PugCarlino_Luna
4-Verifica que el nombre de la mascota fue modificado correctamente
5-Elimina la mascota agregada


