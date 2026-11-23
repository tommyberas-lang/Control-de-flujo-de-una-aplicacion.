# Control de flujo de una aplicación


Repositorio correspondiente a la segunda tarea de Algoritmos Computacionales. Este proyecto consiste en desarrollar una aplicación de consola utilizando el lenguaje de programación C#, aplicando funciones, parámetros, estructuras condicionales, ciclos y validación de datos.

# Participantes

1. **Luis David Herrera Ramírez** - 26-ESON-2-001

2. **Dauri Alexis Contreras Mora** - 26-EISN-2-046

3. **Brandhiel Josue Sanchez** - 26-ESON-2-013

4. **Abdison Azarias Abreu Cruz** - 26-ESON-2-005

5. **Ruddy Thomas Beras** - 26-ESON-2-016

# Descripción

El proyecto consiste en una aplicación de consola desarrollada en C#, cuyo propósito es realizar diferentes operaciones matemáticas y verificar la mayoría de edad de una persona mediante un menú interactivo.

El programa permite al usuario seleccionar entre cinco opciones:

- **Opción 1: Área del triángulo.** Solicita la base y la altura para calcular su área.
- **Opción 2: Área del cuadrado.** Solicita la medida de uno de sus lados y calcula su área.
- **Opción 3: Área del círculo.** Solicita el radio y calcula su área utilizando el valor de PI.
- **Opción 4: Verificación de edad.** Solicita la edad de una persona e indica si es mayor o menor de edad.
- **Opción 5: Salir.** Finaliza la ejecución del programa.

Para organizar las operaciones, se utilizan funciones independientes que reciben valores mediante parámetros y retornan los resultados correspondientes.

Además, el programa incorpora validaciones mediante estructuras repetitivas `while`, evitando que se utilicen medidas iguales o menores que cero y edades negativas.

# Datos de Entrada

El programa solicita diferentes datos dependiendo de la opción seleccionada por el usuario.

- **Opción del menú:** número entero que permite seleccionar la operación que se desea realizar (del 1 al 5).

- **Base del triángulo:** número decimal que representa la longitud de la base.

- **Altura del triángulo:** número decimal que representa la altura del triángulo.

- **Lado del cuadrado:** número decimal que representa la longitud de uno de sus lados.

- **Radio del círculo:** número decimal que representa la distancia desde el centro hasta el borde del círculo.

- **Edad:** número entero que representa los años cumplidos de una persona.

Las medidas utilizadas para calcular las áreas deben ser mayores que cero. La edad debe ser igual o mayor que cero.

# Datos que Procesa

El programa realiza diferentes operaciones según la opción seleccionada:

**1. Cálculo del área del triángulo**

Utiliza la función `AreaTriangulo`, que recibe la base y la altura como parámetros y aplica la siguiente fórmula:

Área = (Base × Altura) / 2

**2. Cálculo del área del cuadrado**

Utiliza la función `AreaCuadrado`, que recibe la medida del lado y la multiplica por sí misma.

Área = Lado × Lado

**3. Cálculo del área del círculo**

Utiliza la función `AreaCirculo`, que recibe el radio y aplica la fórmula matemática correspondiente, utilizando `Math.PI` para obtener el valor de PI.

Área = PI × Radio × Radio

**4. Verificación de mayoría de edad**

Utiliza la función `VerificarEdad`, que recibe la edad como parámetro y realiza una comparación:

- Si la edad es igual o mayor a 18 años, retorna el mensaje "Mayor de edad".
- Si la edad es menor de 18 años, retorna el mensaje "Menor de edad".

**5. Validación de datos**

El programa utiliza estructuras `while` para comprobar que:

- La base y la altura del triángulo sean mayores que cero.
- El lado del cuadrado sea mayor que cero.
- El radio del círculo sea mayor que cero.
- La edad no sea negativa.

Si el usuario introduce un valor que no cumple estas condiciones, el programa solicita nuevamente los datos.

También utiliza una estructura `switch` para controlar las opciones del menú y mostrar un mensaje cuando se selecciona una opción no válida.

# Datos de Salida

Dependiendo de la operación realizada, el programa muestra los siguientes resultados:

- **Área del triángulo:** muestra el resultado del cálculo utilizando la base y la altura ingresadas.
- **Área del cuadrado:** muestra el resultado obtenido al multiplicar el lado por sí mismo.
- **Área del círculo:** muestra el resultado del cálculo utilizando el radio y el valor de PI.
- **Verificación de edad:** muestra un mensaje indicando si la persona es mayor o menor de edad.
- **Mensajes de validación:** muestra advertencias cuando se introducen medidas iguales o menores que cero o una edad negativa.
- **Opción no válida:** muestra un mensaje de advertencia cuando se selecciona una opción que no pertenece al menú.
- **Salida del programa:** muestra un mensaje indicando que el programa está finalizando.


# Capturas de Pantalla

<img width="468" height="246" alt="image" src="https://github.com/user-attachments/assets/35a087de-b907-4974-8a6a-95d6252c2ad8" /> <img width="722" height="227" alt="image" src="https://github.com/user-attachments/assets/00c93098-526b-4329-9eca-fa4982e2b837" /> <img width="594" height="229" alt="image" src="https://github.com/user-attachments/assets/1a31331c-fe2c-4770-9cd7-9d8dc30457db" /> <img width="713" height="221" alt="image" src="https://github.com/user-attachments/assets/4cca51c3-c4a8-41af-879b-cc6883ccf722" /> <img width="597" height="208" alt="image" src="https://github.com/user-attachments/assets/800b0350-bf9f-4148-8720-ff870ee4f5d8" />





