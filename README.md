# MyStudyPlanRust

>1 Variables

Crear un programa en Rust que permita al usuario ingresar dos números enteros y luego muestre en pantalla el resultado de la suma, resta, multiplicación y división de los mismos.

- Definir dos variables enteras utilizando el tipo de datos "i32" en Rust.
- Utilizar la función "println!" para mostrar un mensaje en pantalla solicitando al usuario que ingrese el primer número.
- Leer el primer número ingresado por el usuario utilizando la función "std::io::stdin().read_line(&mut variable).expect("Error")".
- Convertir el valor ingresado por el usuario a un número entero utilizando la función "parse()" de Rust.
- Repetir los pasos 2 a 4 para el segundo número ingresado por el usuario.
- Realizar las operaciones de suma, resta, multiplicación y división utilizando los operadores "+" "-" "*" "/" y almacenar los resultados en variables separadas.
- Utilizar la función "println!" para mostrar los resultados de las operaciones en pantalla.

>2 Data Types

Crear un programa en Rust que permita al usuario ingresar su información personal, como su nombre, edad, estatura y peso, y luego muestre en pantalla un resumen de la misma.

- Crear una estructura en Rust que represente la información personal del usuario. Esta estructura debe incluir campos para el nombre (cadena de caracteres), la edad (entero), la estatura (flotante) y el peso (flotante).
- Utilizar la función "println!" para mostrar un mensaje en pantalla solicitando al usuario que ingrese su nombre.
- Leer el nombre ingresado por el usuario utilizando la función "std::io::stdin().read_line(&mut variable).expect("Error")".
- Eliminar los caracteres de salto de línea y espacios en blanco adicionales del nombre utilizando la función "trim()" de Rust.
- Repetir los pasos 2 a 4 para la edad, estatura y peso del usuario.
- Crear una instancia de la estructura definida en el paso 1 utilizando los valores ingresados por el usuario.
- Utilizar la función "println!" para mostrar un resumen de la información ingresada por el usuario, utilizando los valores de los campos de la estructura creada en el paso 6.

>3 Operators

Crear un programa en Rust que permita al usuario ingresar un número entero y luego muestre en pantalla si dicho número es par o impar.

- Utilizar la función "println!" para mostrar un mensaje en pantalla solicitando al usuario que ingrese un número entero.
- Leer el número ingresado por el usuario utilizando la función "std::io::stdin().read_line(&mut variable).expect("Error")".
- Convertir el valor ingresado por el usuario a un número entero utilizando la función "parse()" de Rust.
- Utilizar el operador módulo "%" para determinar si el número ingresado por el usuario es par o impar. Si el resultado de la operación es cero, el número es par. De lo contrario, es impar.
- Utilizar la función "println!" para mostrar en pantalla si el número es par o impar.

>4 Conditional Expressions

Crear un programa en Rust que permita al usuario ingresar su edad y luego muestre en pantalla si es mayor de edad o no.

- Utilizar la función "println!" para mostrar un mensaje en pantalla solicitando al usuario que ingrese su edad.
- Leer la edad ingresada por el usuario utilizando la función "std::io::stdin().read_line(&mut variable).expect("Error")".
- Convertir el valor ingresado por el usuario a un número entero utilizando la función "parse()" de Rust.
- Utilizar una expresión condicional en Rust para determinar si la edad ingresada por el usuario es mayor o igual a 18 años.
- Si la edad es mayor o igual a 18 años, mostrar un mensaje en pantalla indicando que el usuario es mayor de edad. De lo contrario, mostrar un mensaje en pantalla indicando que el usuario es menor de edad.

>5 Loops

Crear un programa en Rust que permita al usuario ingresar un número entero y luego muestre en pantalla la tabla de multiplicar de dicho número del 1 al 10 utilizando un bucle while.

- Utilizar la función "println!" para mostrar un mensaje en pantalla solicitando al usuario que ingrese un número entero.
- Leer el número ingresado por el usuario utilizando la función "std::io::stdin().read_line(&mut variable).expect("Error")".
- Convertir el valor ingresado por el usuario a un número entero utilizando la función "parse()" de Rust.
- Utilizar un bucle while en Rust para calcular los primeros 10 múltiplos del número ingresado por el usuario.
- En cada iteración del bucle, calcular el resultado de multiplicar el número ingresado por el valor del contador del bucle y mostrar el resultado en pantalla utilizando la función "println!".

>6 Boolean

Crear un programa en Rust que permita al usuario ingresar dos valores booleanos y luego muestre en pantalla el resultado de aplicar los operadores lógicos AND, OR y NOT entre ambos valores.

- Utilizar la función "println!" para mostrar un mensaje en pantalla solicitando al usuario que ingrese dos valores booleanos (true o false).
- Leer los valores ingresados por el usuario utilizando la función "std::io::stdin().read_line(&mut variable).expect("Error")".
- Convertir los valores ingresados por el usuario a valores booleanos utilizando la función "parse()" de Rust.
- Utilizar los operadores lógicos "&&" (AND), "||" (OR) y "!" (NOT) para calcular los resultados de las operaciones lógicas entre los valores ingresados por el usuario.
- Utilizar la función "println!" para mostrar en pantalla el resultado de cada operación lógica.

>7 Strings

Crear un programa en Rust que permita al usuario ingresar una cadena de texto y luego muestre en pantalla la misma cadena de texto pero con las palabras invertidas.

- Utilizar la función "println!" para mostrar un mensaje en pantalla solicitando al usuario que ingrese una cadena de texto.
- Leer la cadena de texto ingresada por el usuario utilizando la función "std::io::stdin().read_line(&mut variable).expect("Error")".
- Utilizar la función "split_whitespace()" para dividir la cadena de texto ingresada por el usuario en palabras individuales.
- Utilizar la función "rev()" para invertir el orden de las palabras obtenidas en el paso anterior.
- Unir las palabras invertidas en una sola cadena de texto utilizando la función "join()" y mostrar el resultado en pantalla utilizando la función "println!".

>8 Vectors, Arrays and Slices

Crear un programa en Rust que permita al usuario ingresar una lista de números separados por comas y luego muestre en pantalla la suma de los números ingresados y su promedio.

- Utilizar la función "println!" para mostrar un mensaje en pantalla solicitando al usuario que ingrese una lista de números separados por comas.
- Leer la lista de números ingresada por el usuario utilizando la función "std::io::stdin().read_line(&mut variable).expect("Error")".
- Utilizar la función "split()" para dividir la lista de números ingresada por el usuario en elementos individuales.
- Convertir cada elemento de la lista a un número entero utilizando la función "parse()" de Rust.
- Crear un vector para almacenar los números enteros obtenidos en el paso anterior.
- Utilizar la función "iter()" para iterar sobre los elementos del vector y calcular la suma de los mismos.
- Calcular el promedio de los números ingresados dividiendo la suma obtenida en el paso anterior por la cantidad de elementos del vector.
- Utilizar la función "println!" para mostrar en pantalla la suma y el promedio obtenidos.

>9 Enums

Crear un programa en Rust que simule una tienda en línea y utilice enums para representar los diferentes tipos de productos disponibles.

- Crear un enum llamado "ProductType" que represente los diferentes tipos de productos que se pueden vender en la tienda en línea (por ejemplo, "Libros", "Ropa", "Electrónica", etc.).
- Crear una estructura llamada "Product" que tenga campos para el nombre del producto, su precio y su tipo (utilizando el enum "ProductType" creado en el paso anterior).
- Crear una función que permita al usuario ingresar un nuevo producto, solicitando su nombre, precio y tipo (utilizando el enum "ProductType").
- Almacenar los productos ingresados por el usuario en un vector.
- Crear una función que muestre en pantalla todos los productos disponibles, indicando su nombre, precio y tipo.
- Permitir al usuario seleccionar un tipo de producto y mostrar en pantalla solo los productos que corresponden a ese tipo.
- Permitir al usuario seleccionar un rango de precios y mostrar en pantalla solo los productos cuyo precio esté dentro de ese rango.

>10 Mutable Variables

Crear un programa en Rust que permita al usuario ingresar una lista de números y luego calcule la suma, el promedio y el máximo de los números ingresados, utilizando variables mutables.

- Crear un vector vacío para almacenar los números ingresados por el usuario.
- Crear un loop que permita al usuario ingresar los números uno por uno, hasta que indique que ha terminado de ingresar números.
- Dentro del loop, utilizar una variable mutable para almacenar cada número ingresado por el usuario en el vector.
- Después de que el usuario haya terminado de ingresar números, utilizar una variable mutable para calcular la suma de todos los números en el vector.
- Utilizar otra variable mutable para calcular el promedio de los números en el vector, dividiendo la suma total por la cantidad de números en el vector.
- Utilizar una tercera variable mutable para encontrar el número máximo en el vector.
- Mostrar en pantalla la suma, el promedio y el máximo de los números ingresados por el usuario.

>11 Structs and Tuples

Crear un programa en Rust que permita al usuario ingresar información de diferentes personas, almacenando esta información en una estructura (struct) y una tupla (tuple). Luego, el programa debe imprimir en pantalla la información de cada persona ingresada.

- Crear una estructura (struct) llamada "Persona" que contenga los siguientes campos: nombre (String), edad (u8) y género (String).
- Crear una tupla llamada "PersonaTupla" que contenga los mismos campos que la estructura Persona.
- Crear un vector vacío para almacenar la información de las personas ingresadas por el usuario.
- Crear un loop que permita al usuario ingresar información de diferentes personas. Dentro de este loop, pedir al usuario que ingrese el nombre, edad y género de cada persona, y luego almacenar esta información en una instancia de la estructura Persona y en una instancia de la tupla PersonaTupla.
- Después de que el usuario haya terminado de ingresar información de personas, almacenar cada instancia de Persona y PersonaTupla en el vector creado en el paso 3.
- Crear un loop que recorra el vector de personas y, para cada instancia de Persona y PersonaTupla, imprimir en pantalla la información de cada persona ingresada.
- Utilizar las macros de formato de Rust (por ejemplo, println!) para imprimir la información de cada persona en el formato deseado.

>12 Ownership Rules

Implementación de una lista enlazada en Rust siguiendo las reglas de propiedad

- Cree una estructura LinkedListNode que tenga un campo de valor de tipo genérico y otro campo que almacene la siguiente LinkedListNode.
- Cree una estructura LinkedList que tenga un campo que almacene el primer LinkedListNode y un campo que almacene la longitud de la lista.
- Implemente los métodos push y pop para la estructura LinkedList. En el método push, debe crear un nuevo LinkedListNode con el valor dado y agregarlo al final de la lista. En el método pop, debe eliminar el último nodo de la lista y devolver su valor.
- Asegúrese de seguir las reglas de propiedad de Rust en todo momento, como evitar aliasing mutable y garantizar la exclusividad de las referencias mutables.
- Cree pruebas para verificar que su lista enlazada funcione correctamente y siga las reglas de propiedad de Rust.

>13 Borrowing and References

>14 Lifetimes

>15 References

>16 Methods

>17 Modules

>18 Stack vs. Heap

>19 Ownership and Borrowing

>20 Lifetime Annotations

>21 Memory Safety

>22 Traits and Implementations

>23 Generic Functions and Types

>24 Bounds and Constraints

>25 Associated Types

>26 Iterators

>27 Early Exit

>28 Stacks and Queues

>29 Trees

>30 Graphs

>31 Recursive Algorithms

>32 Backtracking Basics

>33 Backtracking in Rust

>34 Memoization

>35 Tabulation

Crear un programa que utilice el método de tabulación para resolver un problema de programación dinámica. El problema puede ser elegido por ti, pero es recomendable comenzar con uno sencillo como el problema de la mochila o el cálculo de números de Fibonacci.

- Define el problema que vas a resolver utilizando la programación dinámica y estudia cómo se resuelve mediante el método de tabulación.
- Crea un proyecto nuevo en Rust y configura tu entorno de desarrollo.
- Define las estructuras de datos necesarias para representar el problema que quieres resolver.
- Implementa la solución mediante el método de tabulación, utilizando bucles y vectores para almacenar los resultados de subproblemas previos.
- Agrega una función de prueba que permita verificar que la solución es correcta.
- Prueba tu programa con diferentes entradas y verifica que se comporta correctamente.
- Agrega documentación y comentarios a tu código para que sea fácil de entender y utilizar para otros desarrolladores.
- Si te sientes cómodo, considera publicar tu proyecto en un repositorio en línea para que otros puedan aprender de él y contribuir con mejoras.

>36 Creating a New Project

Crear una aplicación de línea de comandos para manejar tareas.

- Crea un nuevo proyecto Rust usando Cargo.
- Define una estructura de tarea que tenga un título, una descripción y una fecha de vencimiento.
- Crea una función para agregar nuevas tareas a una lista.
- Crea una función para eliminar tareas de la lista.
- Crea una función para mostrar todas las tareas en la lista.
- Crea una función para mostrar solo las tareas que vencen en un determinado período de tiempo (por ejemplo, próximos 7 días).
- Implementa la entrada y salida de datos de la aplicación de línea de comandos.
- Prueba la aplicación con algunos datos de muestra para verificar su funcionamiento.

>37 Building and Running

Crear una aplicación de línea de comandos que solicite al usuario una cadena de texto y un número entero, y luego genere un nuevo texto que contenga el texto original repetido el número de veces especificado.

- Crear un nuevo proyecto de Rust utilizando Cargo.
- Definir una estructura que represente la entrada del usuario (texto y número).
- Leer la entrada del usuario desde la línea de comandos utilizando la biblioteca std::io.
- Escribir una función que tome la entrada del usuario y devuelva una cadena de texto que contenga la cadena original repetida el número de veces especificado.
- Imprimir el resultado en la consola utilizando la biblioteca std::io.
- Compilar el proyecto y ejecutar la aplicación resultante en la línea de comandos.

>38 Publishing and Sharing

Publishing a Rust crate to crates.io

- Crea un nuevo proyecto Rust usando Cargo: cargo new my_crate
- Agrega el código que deseas compartir en el archivo src/lib.rs.
- Si tu proyecto tiene dependencias externas, agrégalas al archivo Cargo.toml.
- Asegúrate de que tu código esté bien documentado para que los usuarios puedan entender cómo usar tu crate. Puedes agregar comentarios al código usando ///.
- Ejecuta cargo login e ingresa tu nombre de usuario y token de acceso personal de crates.io cuando se te solicite. Si no tienes un token de acceso personal, sigue las instrucciones en https://crates.io/me/publishers.
- Ejecuta cargo package para crear un archivo de paquete .crate en la carpeta target/package.
- Ejecuta cargo publish para publicar tu crate en crates.io.
- Para actualizar tu crate, repite los pasos 2 a 7 con el código actualizado.
- Puedes encontrar tu crate publicado en https://crates.io/crates/my_crate.

>39 Connecting to Databases in Rust

Crear una aplicación de lista de tareas que se conecte a una base de datos SQLite usando Rust.

- Configure una base de datos SQLite y cree una tabla para almacenar las tareas.
- Defina una estructura para representar una tarea con campos como id, descripción, fecha de creación, fecha de vencimiento, etc.
- Escriba funciones para insertar, actualizar y eliminar tareas en la base de datos.
Implemente una API RESTful para acceder a las tareas utilizando un framework web como Rocket.
- Escriba pruebas unitarias y de integración para asegurarse de que la aplicación funcione correctamente.
- Agregue funcionalidades adicionales, como filtrado de tareas por fecha, búsqueda de tareas por palabra clave, etc.
- Implemente la autenticación de usuario y autorización para proteger las tareas de usuarios no autorizados.
- Despliegue la aplicación en línea usando un proveedor de servicios en la nube como Heroku o AWS.

>40 Web Servers

Desarrollo de un servidor web básico en Rust.

- Crea un nuevo proyecto Rust y agrega las dependencias necesarias para implementar un servidor web. Puedes usar el paquete actix-web o rocket como framework para tu servidor web.
- Define las rutas y endpoints de tu servidor web en el archivo principal de tu proyecto.
- Implementa la lógica necesaria para manejar las solicitudes HTTP entrantes. Puedes incluir la lectura y escritura de archivos, la conexión a una base de datos, la manipulación de datos JSON, etc.
- Configura tu servidor web para escuchar en un puerto y ejecutar el código de manejo de solicitudes. Puedes elegir cualquier puerto disponible en tu sistema local.
- Agrega pruebas unitarias y de integración para validar el comportamiento de tu servidor web en diferentes situaciones, incluyendo casos exitosos y casos de error.
- Ejecuta tu servidor web y realiza algunas solicitudes HTTP utilizando una herramienta como curl o un cliente web. Verifica que tu servidor web responda correctamente a las solicitudes y maneje adecuadamente los errores.
- Documenta tu servidor web y su funcionalidad en un archivo README. Incluye instrucciones para configurar y ejecutar el servidor web, así como ejemplos de cómo realizar solicitudes HTTP válidas a través de él.

>41 Building a Backend in Rust

Crea un backend en Rust que permita a los usuarios realizar operaciones CRUD (Crear, Leer, Actualizar y Eliminar) en una base de datos SQLite. La aplicación web debe tener una interfaz de usuario simple para que los usuarios puedan interactuar con la base de datos.

- Crea un nuevo proyecto Rust utilizando un marco web como Rocket o Actix-Web.
- Configura la base de datos SQLite en tu proyecto y utiliza una biblioteca como Diesel para interactuar con la base de datos.
- Crea modelos para las tablas que deseas utilizar en la base de datos y utiliza Diesel para crear las tablas.
- Implementa los endpoints de la API REST para que los usuarios puedan realizar operaciones CRUD en la base de datos.
- Crea una interfaz de usuario utilizando HTML, CSS y JavaScript para permitir a los usuarios interactuar con la API REST.
- Implementa la funcionalidad del frontend utilizando fetch para hacer llamadas a la API REST en tu aplicación web backend.
- Prueba exhaustivamente tu aplicación web backend para asegurarte de que todo funciona como se espera.
- Implementa una capa de autenticación y seguridad para proteger tu aplicación web de ataques.
- Despliega tu aplicación web en un servidor de producción utilizando herramientas como Docker y Kubernetes.

>42 Web Frameworks

Crear una aplicación web usando el framework web Rocket para Rust que permita a los usuarios buscar y visualizar información de películas. La aplicación debe consumir una API externa que proporciona información sobre películas y mostrar los resultados de la búsqueda al usuario. Además, debe permitir al usuario hacer clic en una película para ver más detalles.

- Investigar y elegir una API externa que proporcione información sobre películas. Algunas opciones populares incluyen la API de películas de IMDb, la API de películas de TMDb o la API de películas de OMDb.
- Crear un proyecto Rocket en Rust utilizando Cargo.
- Configurar el proyecto para consumir la API externa elegida. Puede hacer esto utilizando una biblioteca de Rust como reqwest.
- Crear una ruta en la aplicación web para que el usuario pueda buscar películas utilizando un formulario HTML.
- Crear una vista que muestre los resultados de la búsqueda al usuario. Cada resultado debe ser un enlace a una página de detalles de la película.
- Crear una ruta en la aplicación web para que el usuario pueda ver los detalles de una película en particular.
- Crear una vista que muestre los detalles de la película seleccionada. Esta vista debe incluir información como el título de la película, el año de lanzamiento, el reparto, la trama, el cartel y cualquier otra información relevante.
- Estilizar la aplicación web utilizando CSS para que tenga un aspecto profesional y atractivo.
- Asegurarse de que la aplicación maneje correctamente cualquier error que pueda ocurrir al interactuar con la API externa.
- Ejecutar y probar la aplicación para asegurarse de que funciona correctamente y se ve bien.

>43 Integrating with a Rust Backend

Crear una aplicación web usando Rust y un framework web de su elección que permita a los usuarios realizar operaciones CRUD (crear, leer, actualizar, eliminar) en una base de datos SQLite. La aplicación debe tener una interfaz de usuario simple que permita al usuario interactuar con la base de datos y mostrar los resultados de las operaciones realizadas.

- Crear una base de datos SQLite y una tabla que contenga la información que se desea almacenar. Puede usar el comando SQLite3 para crear la base de datos y la tabla, o puede usar una herramienta de administración de bases de datos como DB Browser para SQLite.
- Crear un proyecto Rust usando el framework web de su elección (por ejemplo, Rocket, Actix, etc.).
- Configurar el proyecto para que se conecte a la base de datos SQLite. Puede hacer esto usando un paquete de Rust como rusqlite o diesel.
- Crear las rutas necesarias en la aplicación web para realizar operaciones CRUD en la base de datos (por ejemplo, una ruta para crear un registro en la base de datos, una ruta para actualizar un registro existente, etc.).
- Crear las vistas HTML y CSS necesarias para mostrar la información en la aplicación web. Puede usar un paquete de Rust como horrorshow para generar las vistas dinámicamente en el servidor.
- Integrar las vistas con las rutas creadas en el paso 4 para permitir que el usuario realice operaciones CRUD en la base de datos a través de la aplicación web.
- Ejecutar la aplicación y probarla para asegurarse de que funcione correctamente. Asegúrate de manejar correctamente los posibles errores que puedan ocurrir al interactuar con la base de datos.
