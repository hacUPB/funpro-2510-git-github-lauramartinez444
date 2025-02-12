[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WV8VkdWq)
# Bitácora
**Nombre del estudiante:** Laura Martínez Correa

**ID.:** 000533807

El proyecto básicamente, consta de un codigo base c, diseñado para agregarle información sobre el uso de las herramientas claves en la programación como lo son git bash, y los repositorios para tener los archivos en caso de tener que cambiar algo de una rama secundaria.

**En caso de ser necesario, clonar y/o ejecutar el proyecto se deben seguir los siguientes pasos:**

# Para clonar un repositorio existente de GitHub, sigue estos pasos:

Obtener la URL del Repositorio: Ve al repositorio en GitHub y copia la URL (por ejemplo, 
*https://github.com/usuario/nombre-repo.git).*

## Abrir la Terminal: Utiliza Git Bash o el terminal que prefieras.
Ejecutar el Comando de Clonación:

bash
```
git remote add origin
```

 https://github.com/usuario/nombre-repo.git

**Este comando crea una copia local del repositorio en tu máquina.**
Acceder al Directorio Clonado:

bash
```
cd nombre-repo
```

Cambia al directorio del repositorio clonado para comenzar a trabajar en él.

### Verificación
Puedes verificar que el repositorio se ha clonado correctamente listando los archivos:

bash 
```
ls
```

## TABLA DE CONTENIDO
| NOMBRE                 | DESCRIPCIÓN                                 | ENLACE                                   |
| ---------------------- | ------------------------------------------- | ---------------------------------------- |
| src/                   | Código c inicial                            | [SRC](./src/READ.me)
| docs/                  | Directorios con la información de cada uno. | [DOCS](./docs/)     |
| uso\_consola.md        | Descripción del uso de la consola           | [USO CONSOLA](./docs/uso_consola.md)|
| repositorio\_remoto.md | Como tener tu propio repositorio remoto     | [REPOSITORIO REMOTO](./docs/repositorio_remoto.md)     |
| repositorio\_local.md  | Como iniciar un repositorio local           | [REPOSITORIO LOCAL](./docs/repositorio_local.md)  |
| Images/                | Donde tengo localizadas todas las imágenes  | [IMAGES](./images/)     |

 # ¿Qué es un computador?   🖥️💻
*Un computador, también conocido como computadora u ordenador, es una máquina programable y compleja que procesa y ejecuta órdenes para realizar diversas tareas Es un dispositivo electrónico que recibe datos (como números, texto o imágenes), los procesa mediante un conjunto de instrucciones (un programa) y los transforma en información útil.*

🖥️🖥️🖥️🖥️🖥️

imagen 

## **Partes de un computador**
Un computador se compone de dos partes esenciales: 
*hardware y software*
Hardware El hardware se refiere a los componentes físicos y tangibles de un computador, como el teclado, el ratón, la pantalla, los cables y las placas. Los componentes de hardware se pueden clasificar en internos y externos 
**Componentes internos:**
*Procesador (CPU):* Ejecuta instrucciones de programas y procesa datos También se le conoce como el "cerebro" del computador. La CPU consta de la Unidad Aritmético Lógica (ALU), la Unidad de Control (UC) y registros
*Memoria (RAM y ROM):* La memoria RAM (Random Access Memory) almacena datos a corto plazo y las instrucciones que se están ejecutando. La memoria ROM (Read-Only Memory) es un medio de almacenamiento que solo permite la lectura de información
*Placa madre:* Es una tarjeta de circuito impreso a la que se conectan los componentes del computador 
*ALU (Unidad Aritmético-Lógica):*
Realiza operaciones lógicas, matemáticas o formales que sostienen el sistema 
*Unidad de Control (UC):*
Coordina y controla el flujo de datos dentro del sistema 
*Registros:*
Espacios de almacenamiento de alta velocidad dentro de la CPU que se utilizan para guardar datos e instrucciones que se están utilizando activamente 
*Buses:*
Sistemas de comunicación que transfieren datos entre los componentes del computador 

#### 🖱️🖱️ ⌨️⌨️ **Componentes externos:** 🖱️🖱️ ⌨️⌨️

imagen

*Periféricos de entrada:* 
Permiten el ingreso de datos al computador (ej. teclado, ratón) 
*Periféricos de salida:* 
Muestran la información procesada al usuario (ej. monitor, impresora) 
*Dispositivos de almacenamiento:* 
Discos que almacenan información, incluyendo el sistema operativo, programas y archivos del usuario 

### **Componentes internos** 

imagen

*Software:* El software es el conjunto de programas, sistemas operativos y funciones instaladas en el computador que coordinan el hardware para funcionar  Incluye el sistema operativo (SO) y las aplicaciones.
*Sistema operativo:* Actúa como una interfaz entre el hardware y las aplicaciones, coordinando el acceso a los recursos del computador 
*Aplicaciones:* Programas que realizan tareas específicas, como edición de textos, reproducción de música o navegación web 
*Software de desarrollo:* Herramientas utilizadas para crear, probar y depurar otros programas (ej. compiladores, entornos de desarrollo integrados (IDEs)) 

### **Funcionamiento general de un computador**
Un computador funciona recibiendo datos de entrada a través de periféricos, procesándolos en la CPU mediante la ejecución de programas (software) almacenados en la memoria, y enviando la información resultante a través de los periféricos de salida La CPU, que incluye la ALU y la Unidad de Control, es responsable de realizar operaciones lógicas y aritméticas y de coordinar el flujo de datos dentro del sistema. 
El sistema operativo gestiona los recursos del hardware y permite que las aplicaciones interactúen con el computador.

🏗️🏗️ **Arquitecturas de un computador:**

imagen

La arquitectura de un computador se refiere a su diseño conceptual y la estructura operacional fundamental de un sistema de computación 
Describe cómo están interconectados sus componentes de hardware y cómo interactúan para ejecutar programas.

**Arquitectura CISC (Complex Instruction Set Computing):** 
CISC se caracteriza por un conjunto de instrucciones amplio y complejo, diseñado para realizar tareas complejas con pocas instrucciones. Los computadores con arquitectura CISC, como los procesadores Intel x86, se encuentran comúnmente en equipos de escritorio y portátiles modernos
Arquitectura RISC (Reduced Instruction Set Computing): RISC utiliza un conjunto de instrucciones más pequeño y simple, lo que permite una ejecución más rápida de cada instrucción. Esta arquitectura se encuentra en dispositivos móviles, servidores y sistemas integrados, como los procesadores ARM.

**Registros:**

imagen

*Caché:* Memoria de alta velocidad utilizada para almacenar datos a los que se accede con frecuencia, lo que acelera el acceso a la información.

*Principal (RAM):* Almacena datos e instrucciones que la CPU está utilizando actualmente. Es de acceso aleatorio y volátil, lo que significa que los datos se pierden cuando se apaga el computador.

*Secundaria (Disco duro y unidades externas de almacenamiento):* 
Almacena datos a largo plazo, incluyendo el sistema operativo, programas y archivos del usuario. Es no volátil, lo que significa que los datos se conservan cuando se apaga el computador.

**Dispositivos de entrada/salida:**
*Entrada:* Permiten el ingreso de datos al computador (ej. teclado, ratón) 

*Salida:* 
Muestran la información procesada al usuario (ej. monitor, impresora) s

**¿Qué sucede desde que ingreso un dato a través del teclado, hasta que veo el resultado de la operación en la pantalla?** 
Cuando se ingresa un dato a través del teclado, la señal se envía a la CPU, donde se procesa según las instrucciones del programa en ejecución. Luego, el resultado se envía a la tarjeta de video, que lo muestra en la pantalla 
¿Cómo se codifican los datos internamente en el computador? Los datos se codifican internamente en el computador utilizando el sistema binario, que representa la información mediante combinaciones de 0 y 1.

**¿Cuáles son las unidades de medida de datos en un computador?**
*Bit:* La unidad más pequeña de información, que representa un 0 o un 1.

-*Byte:* Un grupo de 8 bits.

-*Kilobyte (KB):* 1024 bytes.

-*Megabyte (MB):* 1024 kilobytes.

-*Gigabyte (GB):* 1024 megabytes.

-*Terabyte (TB):* 1024 gigabytes.

*REFERENCIAS:*
1. https://concepto.de/computador/
2. https://courses.minnalearn.com/es/courses/digital-revolution/the-computing-revolution/computer-basics/ 
3. https://es.wikipedia.org/wiki/Computadora
4. https://concepto.de/computadora/


# LENGUAJES CON SUS TIPOS DE DATOS
## Comparación de Tipos de Datos

| Tipo de Dato | Lenguaje | Definición en Español                                                                 | Tamaño (bytes) | Notas                                                                                                     |
|--------------|----------|---------------------------------------------------------------------------------------|-----------------|-----------------------------------------------------------------------------------------------------------|
| `int`        | C/C++    | Representa números enteros.                                                           | 4               |                                                                                                           |
| `char`       | C/C++    | Representa un solo carácter.                                                           | 1               |                                                                                                           |
| `float`      | C/C++    | Representa números de punto flotante de precisión simple.                             | 4               |                                                                                                           |
| `double`     | C/C++    | Representa números de punto flotante de doble precisión.                             | 8               |                                                                                                           |
| `void`       | C        | Indica la ausencia de valor o tipo.                                                  | -               |                                                                                                           |
| `bool`       | C++      | Representa valores booleanos (`true` o `false`).                                    | 1               |                                                                                                           |
| `string`     | C++      | Representa una secuencia de caracteres (cadena de texto).                           | Variable         |                                                                                                           |
| `int`        | Java     | Representa números enteros.                                                           | 4               |                                                                                                           |
| `char`       | Java     | Representa un solo carácter Unicode.                                                  | 2               |                                                                                                           |
| `float`      | Java     | Representa números de punto flotante de precisión simple.                             | 4               |                                                                                                           |
| `double`     | Java     | Representa números de punto flotante de doble precisión.                             | 8               |                                                                                                           |
| `boolean`    | Java     | Representa valores booleanos (`true` o `false`).                                    | 1               |                                                                                                           |
| `byte`       | Java     | Representa un número entero pequeño.                                                  | 1               |                                                                                                           |
| `short`      | Java     | Representa un número entero corto.                                                   | 2               |                                                                                                           |
| `long`       | Java     | Representa un número entero largo.                                                   | 8               |                                                                                                           |
| `int`        | Python   | Representa números enteros.                                                           | Variable         | El tamaño depende de la magnitud del número.                                                             |
| `float`      | Python   | Representa números de punto flotante.                                                | 8               | Generalmente se implementa como un `double` de C.                                                        |
| `str`        | Python   | Representa una secuencia de caracteres (cadena de texto).                           | Variable         | Depende de la longitud de la cadena y la codificación (UTF-8, etc.).                                       |
| `bool`       | Python   | Representa valores booleanos (`True` o `False`).                                    | Variable         | Generalmente ocupa poco espacio, pero puede depender de la implementación.                               |
| `list`       | Python   | Representa una colección ordenada y mutable de elementos.                            | Variable         | Depende del número de elementos y el tamaño de cada elemento.                                              |
| `tuple`      | Python   | Representa una colección ordenada e inmutable de elementos.                          | Variable         | Depende del número de elementos y el tamaño de cada elemento.                                              |
| `dict`       | Python   | Representa una colección de pares clave-valor.                                     | Variable         | Depende del número de pares y el tamaño de las claves y los valores.                                     |

**Notas Adicionales sobre Python:**

*   En Python, el tamaño en bytes de algunos tipos (especialmente `int`, `str`, `list`, `tuple`, `dict`) puede variar significativamente dependiendo de la cantidad de datos almacenados y de la versión de Python que se esté utilizando.
*   Python gestiona automáticamente la memoria, por lo que no hay una asignación de tamaño fija como en C o Java.

# Símbolos usados en programación:

*   **Línea de flujo:**
```
 `-->`  o `→`
 ```
*   **Terminal:** 
```
`( )` 
```
(con "Inicio" o "Fin" dentro)
*   **Proceso:** 
```
`[ ]`
```
*   **Decisión:** 
```
`<>`
```
*   **Entrada/Salida:** 
```
`/ /`
```
*   **Anotación/Comentario:** 
```
`/* */`
```
*   **Proceso predefinido:** 
```
`[[ ]]`
```
*   **Conector en la página:** 
```
`(A)` , `(B)`, `(C)`... 
```
(la letra cambia)
*   **Conector fuera de página:** 
```
`[[A]]`, `[[B]]`, `[[C]]`... 
```
(para diferenciar del conector en la página)
*   **Retraso:** 
```
` D ` 
```
(Una D mayúscula con espacio a cada lado, como una aproximación)
*   **Datos:** Similar a la Entrada/Salida, podríamos usar 
```
`/ /` 
```
(aunque no es ideal)
*   **Documento:** 
```
`|_|`
```
*   **Multi-documento:** 
```
`||_||`
```
*   **Preparación:**  Es similar al proceso, podrías usar 
```
`[Prep]` 
```
para indicar que es preparación.
*   **Display/Pantalla:** 
```
`|o|`  
```
(simulando una pantalla)
*   **Entrada manual:** 
```
`(teclado)`
```
 (para indicar que es entrada manual)
*   **Operación manual:** 
```
`(mano)`
```
 (para representar una operación manual)

![alt text](</images/simbolos.PNG>)


