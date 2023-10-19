📚primer parcial de la materia de sistema de procesamiento de datos de la carrera de tecnicatura en programacion en la utn 2023

📎 Integrantes.

👼 matias Mazzino

👼Valentin Giraldi

👼ignacio Villalba

💣PROJECTO:

Parte 1: Contador de 0 a 99 con Display 7 Segmentos y Multiplexación

![](https://github.com/valenngiraldi/repositorios/blob/main/1%20parte%20arduino.jpeg)

🔔Descripcion

Con este proyecto planteamos un codigo de arduino para crear un contador con displays de 7 segmentos y multiplexacion.

💻 Funcion principal

Este código se utiliza para crear un contador que muestra valores en dos displays de 7 segmentos y se controla mediante tres botones en un Arduino Uno R3 en Tinkercad. Su funcionalidad es la siguiente: Configura las conexiones de los displays de 7 segmentos y los botones en el Arduino. Utiliza tres botones para controlar el contador: El botón "Incrementar" aumenta el valor del contador. El botón "Decrementar" disminuye el valor del contador. El botón "Reiniciar" restablece el contador a 0. Utiliza la técnica de multiplexación para mostrar los dígitos del contador en los displays de 7 segmentos, evitando el parpadeo al cambiar los dígitos. Muestra los dígitos del contador de 0 a 99 en los displays de 7 segmentos. En resumen, el código crea un contador con dos displays de 7 segmentos que puede aumentar, disminuir y reiniciar su valor utilizando tres botones, y muestra el valor actual en los displays.

📡Enlace del proyecto

https://www.tinkercad.com/things/84cOtP9RYw3-cool-kasi-fyyran/editel?tenant=circuits

Parte 2: Modificación con Interruptor Deslizante y Números Primos

![](https://github.com/valenngiraldi/repositorios/blob/main/2%20parte%20arduino.jpeg)

🔔Descripcion presentamos un codigo de arduino para mostrar uma modificacion de la primera parte agregando un interruptor deslizante

💻 Funcion principal El código principal es un programa de Arduino que controla un contador de dos dígitos y la visualización de números primos en un display de 7 segmentos. Aquí está una descripción de las partes clave: El código configura dos displays de 7 segmentos, un botón para incrementar, un botón para decrementar y un interruptor deslizante que permite alternar entre el contador y los números primos. En la función loop(), se lee el estado del interruptor deslizante para determinar si se debe mostrar el contador o los números primos en el display. Si el interruptor está en una posición, muestra los números primos llamando a la función displayPrimes(). Esta función aún necesita ser implementada para mostrar números primos. Si el interruptor está en la otra posición, el código verifica el estado de los botones para incrementar o decrementar el contador. Cuando se presiona uno de los botones, el contador se incrementa o decrementa en 1 y se muestra en el display.El código utiliza la técnica de multiplexación para mostrar los valores en el display de 7 segmentos, lo que evita el parpadeo al cambiar los dígitos. En resumen, el código principal controla un contador y alterna entre mostrar el contador y los números primos en función de la posición del interruptor deslizante. Puedes personalizar la lógica para mostrar números primos en la función displayPrimes() según tus necesidades.

💾 EJERCICIO 2

📚 Motor de Corriente Continua (Motor DC) Descripción del Componente: Un motor de corriente continua (motor DC) es un dispositivo que convierte energía eléctrica en energía mecánica. Puede girar en ambas direcciones (en sentido horario y antihorario) y se utiliza comúnmente en proyectos de robótica, automatización y control de dispositivos.

Función en el Proyecto: Puedes integrar un motor DC para agregar una función adicional, como una alarma visual o sonora cuando se alcance un valor específico en el contador. Por ejemplo, cuando el contador llega a 99, el motor DC podría activarse para hacer girar un objeto o activar una alarma.

Integración en el Proyecto:

Conecta el motor DC a un transistor o un relé para controlarlo desde el Arduino. El Arduino puede controlar la activación del motor en función de la condición del contador.

Programa el Arduino para que, cuando se alcance el valor deseado en el contador, active el motor DC. Puedes ajustar la lógica de activación según tus necesidades.

📚 Motor de Ventilador (Motor de Aficionado) Descripción del Componente: Un motor de ventilador (motor de aficionado) es un tipo de motor de corriente continua utilizado en ventiladores, enfriadores y otros dispositivos de flujo de aire. Puede generar una corriente de aire que puede ser útil en proyectos de control de temperatura.

Función en el Proyecto: Integrar un motor de ventilador podría permitirte controlar la temperatura en tu proyecto. Por ejemplo, cuando el valor del contador alcance cierto umbral, el motor de ventilador podría activarse para enfriar el sistema.

Integración en el Proyecto:

Conecta el motor del ventilador a un transistor o un módulo de relé para controlarlo desde el Arduino.

Programa el Arduino para que, cuando el valor del contador alcance el umbral de temperatura deseado, active el motor del ventilador para enfriar el sistema.

La integración de cualquiera de estos motores requerirá conocimientos adicionales de electrónica y programación, pero puede agregar funcionalidades interesantes y prácticas a tu proyecto de contador. Asegúrate de tomar las precauciones necesarias al trabajar con componentes eléctricos y de entender cómo controlarlos de manera segura desde tu Arduino.

📡Enlace del proyecto:

https://www.tinkercad.com/things/cVglYRGo3dx-glorious-trug/editel

Parte 3: Modificación según el Último Número de Documento 

![](https://github.com/valenngiraldi/repositorios/blob/main/3ParteArduino.png)

🔔Descripcion En este ejercicio agregue al codigo y al sistema de arduino un fotodiodo y un motor

💻 Funcion principal

En este codigo se utiliza el fotodiodo para determinar si hay suficiente luz. Si la luz supera un cierto umbral (definido por "umbralTemperatura"), se activará una acción específica en el sistema, como encender un dispositivo conectado al pin 12 del Arduino (El motor).

📡Enlace del proyecto

https://www.tinkercad.com/things/5HhGCEtZENv

📫Fuentes

https://www.youtube.com/playlist?list=PL7LaR6_A2-E11BQXtypHMgWrSR-XOCeyD




