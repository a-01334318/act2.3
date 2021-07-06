![Tec de Monterrey](images/logotecmty.png)
# Act 2.3 - Actividad Integral estructura de datos lineales (Evidencia Competencia)

## <span style="color: rgb(26, 99, 169);">¿Qué tengo que hacer?</span>
ccede a la siguiente liga: HTTP y acepta la tarea. Esto creará tu repositorio de trabajo. En él, encontrarás archivos de entrada, así como las salidas esperadas que podrás usar para probar tu implementación. También encontrarás un archivo "main.cpp". Ahí deberás implementar tu solución. En el archivo deberás colocar en la parte superior, en comentarios, tus datos. Por ejemplo:
```
// =========================================================
// File: main.cpp
// Author: Edward Elric - A00123456
// Date: 01/01/2021
// =========================================================
```
<span style="text-decoration: underline;">De manera individual</span>, desarrolla la solución del siguiente problema:

El canal de Suez es un canal navegable que conecta el mar Mediterráneo con el mar Rojo a través de alrededor de 190 km, uniendo por un el lado del mar Mediterráneo desde el puerto Said hasta el golfo de Suez en el mar Rojo. Este canal es navegado entre 49 y 97 barcos diariamente. Se tiene un registro de los barcos que navegan por el canal con el siguiente formato.
```
<fecha> <hora> <punto-entrada> <UBI-Identificador único del buque>
```
Ejemplo:
```
3-jan-20 13:45 M 8PAK7
```
Donde el punto de entrada puede ser **M – Mar Mediterráneo** y **R – Mar Rojo**.

En equipos de dos personas, hacer una aplicación que:
1. Solicite el nombre del archivo de entrada (Ej. canal.txt) y lo abra, almacenando los datos en dos listas encadenadas, una para los que entran por el Mar Mediterráneo y otra para los buques que entran por el mar Rojo.
2. Ordene ambas listas encadenadas por UBI + Fecha (primero por UBI, al haber empate ordenar por fecha).
3. Solicite al usuario la serie a buscar (los primeros tres caracteres de el UBI).
4. Despliegue mes por mes (empezando por el primer mes que venga un buque de esa serie y terminando en el mes de la última entrada) la cantidad de entrada de buques de esa serie por cada una de las entradas con el siguiente formato:
```
<mes><año> <cant-M> <cant-R>
```
Ejemplo:
```
jan 20 5 3
feb 20 2 4
mar 20 0 0
```
Para probar tu implementación, compila tu programa con el comando:
```
g++ main.cpp -o app
```
Posteriormente, prueba con cada uno de los archivos de entrada de prueba que encontrarás en este repositorio (input1.txt, input2.txt, input3.txt, input4.txt). Los resultados que debes obtener se encuentran en los archivos llamados output1.txt, output1.txt, output1.txt y output1.txt. Para realizar las pruebas, puedes usar las siguientes líneas de código. Por ejemplo, si queremos probar con el archivo de prueba "input1.txt".
```
./app > mysolution1.txt
diff mysolution1.txt output1.txt
```
Si el segundo comando no tenga ninguna salida, sabrás que los resultados que obtuviste son los esperados. Recuerda actualizar tu repositorio (*git push*) cuando hayas terminado tu implementación.

Por último, Realiza en forma individual una investigación y reflexión de la importancia y eficiencia del uso de grafos en una situación problema de esta naturaleza,  generando un documento llamado **"ReflexAct2.3.pdf "**.

## <span style="color: rgb(26, 99, 169);">**¿Bajo qué criterios se evalúa mi evidencia?**</span>

- **80%** - Para cada una de las funcionalidades se evaluará:

    - **Excelente (80%)** - pasa correctamente todos los casos de prueba.
    - **Muy Bien (60%)** - pasa correctamente el 75% de los casos de prueba.
    - **Bien (40%)** - pasa correctamente el 50% de los casos de prueba.
    - **Insuficiente (20%)** - pasa correctamente menos del 50% de los casos de prueba.


- **10%** - El código deberá seguir los lineamientos estipulados en el estándar de codificación: <span class="instructure_file_holder link_holder">[liga_estándar_codificación](estandar.pdf)</span>
- **10%** - Se respetenan los nombres de las funciones en la aplicación.

## <span style="color: rgb(26, 99, 169);">**¿Dónde la entrego?**</span>
Esta actividad forma parte tanto de tu calificación final del curso, así como del portafolio de evidencias de las competencias a desarrollar del curso, por lo que se te pide que en forma individual:
* Realices una entrega del código fuente de la solución del problema, en la sección correspondiente dentro de esta plataforma, así como el documento de reflexión individual (**ReflexAct2.3.pdf**).
En la carpeta personal llamada **TC1031(Portafolio_Final)** que generaste desde la entrega de la actividad 1.3 y que te servirá como preparación para la entrega del portafolio de competencias que se realizará al final del curso, coloca en la subcarpeta **Act2.3** tus archivos que solucionaron la <span style="text-decoration: underline;">actividad 2.3</span> así como el documento de reflexión individual (**ReflexAct2.3.pdf**).
