# Investigación: ¿esto ya existe? ¿quién lo dice?

**Autor:** Koral Flores Ramírez
**Fecha:** 17 de Septiembre del 2026
**Ideas analizadas:** ver [[ideas-proyecto]] o [ideas-proyecto.md](ideas-proyecto.md)

---

## Parte 1. Un ejemplo que ya existe, por cada idea

### Idea 1: Checky

- **Qué encontré:** Tapete de entrada inteligente con sensores de presión y alarma
- **Enlace:** https://es.scribd.com/document/689384060/DECA-Project-1
- **Qué hace:** Detecta el peso o las pisadas de las personas al pararse en la entrada y activa una alarma o alerta en el celular para avisar que alguien llegó a la puerta.
- **Por qué no resuelve mi caso:** Porque es un sistema de seguridad o de bienvenida, no para verificar los objetos personales antes de que tú salgas de la casa.

### Idea 2: OnWay

- **Qué encontré:** Botón de pánico basado en LoRaWAN®
- **Enlace:** https://www.mokosmart.com/es/lorawan-button-lw004-pb/
- **Qué hace:** Es un dispositivo físico tipo llavero o credencial con un botón que, al ser presionado, manda una señal de alerta inmediata a contactos o centrales mediante redes de radio frecuencia
- **Por qué no resuelve mi caso:** Porque depende de que existan antenas especiales instaladas en la calle para funcionar sin internet, y aparte solo sirve si tú misma le picas en una emergencia

### Idea 3: Spot-y

- **Qué encontré:** Filtros de precio en aplicaciones como TripAdvisor
- **Enlace:** https://www.tripadvisor.com.mx
- **Qué hace:** Te muestra lugares para comer o visitar y te deja hacer reseñas de qué tan caro o barato es el lugar
- **Por qué no resuelve mi caso:** Porque esos filtros de precio son súper generales y no te dejan poner la cantidad exacta de dinero que traes en la bolsa para ver qué te alcanza de verdad siendo estudiante.

---

## Parte 2. Fuentes de la idea que elegí

### Fuente 1

| Campo                | Contenido                                                                                                                                                                                                                                                     |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Autor u organización | Estudiantes de Ingeniería / DECA                                                                                                                                                                                                                              |
| Título               | Smart Doormat with Piezoelectric Sensor                                                                                                                                                                                                                       |
| Año                  | 2023                                                                                                                                                                                                                                                          |
| Enlace               | https://es.scribd.com/document/689384060/DECA-Project-1                                                                                                                                                                                                       |
| Tipo                 | Documentación técnica                                                                                                                                                                                                                                         |
| Por qué le creo      | Le creo porque es un proyecto real que armaron otros estudiantes de ingeniería para una entrega. En el documento vienen los diagramas de cómo conectaron las cosas, los materiales que compraron y las fotos de cómo sí funciona cuando le pones peso encima. |
| Qué dato me dio      | Me dio la idea de cómo estructurar la base o repisa física para montar los sensores de manera limpia y cómo programar la condición básica de presencia/ausencia antes de mandar la señal a la alerta.                                                         |


### Fuente 2

| Campo                | Contenido                                                                                                                                                                                                                 |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Autor u organización | SparkFun Electronics                                                                                                                                                                                                      |
| Título               | RFID Reader MFRC522 Hookup Guide                                                                                                                                                                                          |
| Año                  | 2021                                                                                                                                                                                                                      |
| Enlace               | [https://learn.sparkfun.com/tutorials/load-cell-amplifier-hx711-breakout-hookup-guide/all](https://learn.sparkfun.com/tutorials/rfid-basics/all)                                                                          |
| Tipo                 | Documentación técnica                                                                                                                                                                                                     |
| Por qué le creo      | Le creo porque SparkFun es una página gigante de electrónica que casi todos los que hacen prototipos usan. Ellos mismos fabrican las piezas, así que los ingenieros que explicaron el módulo son los expertos en el área. |
| Qué dato me dio      | Información técnica sobre cómo funcionan los lectores RFID de corto alcance para entender cómo leen las etiquetas/llaveros y cómo programarlo con mi repisa.                                                              |

---

## Parte 3. Qué haría distinto

Lo que cambia mi proyecto no es una alarma comercial carísima ni un sistema robótico exagerado. Mientras que los organizadores o repisas normales solo sirven para dejar las cosas botadas, y los sensores de seguridad que venden por ahí son para detectar si alguien se mete a robar a tu casa, mi idea es una repisa inteligente justo en la salida. No te pide conectarte al wifi de la casa ni descargar una app kilométrica, es algo rápido, físico y local que te avisa al instante antes de que cierres la puerta y tengas que regresarte corriendo.

## Parte 4. Qué me falta averiguar

- [ ] ¿Cómo funcionan bien las etiquetas y lectores tipo RFID (como los que usan en las cajas de Zara o Bershka para detectar las prendas) y cuál sensor chiquito me conviene comprar para que lea mis llaves o la credencial sin estorbar?
- [ ] A qué distancia máxima el lector puede detectar el tag o la etiqueta pegada a mi cartera o llavero cuando los pase o los deje cerca de la repisa.
- [ ] Pegarle un tag de prueba a mis llaves y checar en mi  puerta si la señal sí atraviesa la tela de mi mochila o bolsillo, o si a fuerza tengo que tocarlos directo contra la repisa.

---

## Declaración de uso de IA

- **Herramienta utilizada:** Gemini 3.6 Flash
- **Qué le pedí:** Le pasé los resultados de mi propia búsqueda web y le pedí que me ayudara a comparar qué tan parecidas eran esas opciones con la idea de mi repisa.
- **Qué modifiqué o rechacé de su respuesta, y por qué:** Yo hice la investigación por mi cuenta y saqué mis propias conclusiones, solo usé a la IA para contrastar los hallazgos.
