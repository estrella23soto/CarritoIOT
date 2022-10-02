# CarritoIOT
## Integrantes 
1. Jose Manuel Sanchez Arredondo
2. Cesar Alegandro Ordoñez Osorio
3. Angel Gerardo Velazquez Salazar 
4. Cruz Estrella Juarez Soto
## Objetivo General
Desarrollar un aplicacion iot  que permita la busqueda de seres vivos en lugares especificos, inalcanzables por el humano que apartir de nototificaciones,alertas visuales y sonoras, que trasmita de manera instantanea al un disposivo movil el cual tambien, sera el control remoto que sera conectado por wifi y/o Bluetood.

## Objetivos especificos 
1. Diseñar prototipo 
2. Codificar la aplicación 
3. Ensanlaje de piezas 
4. Probrar porototipo 
5. Liberar prototito 

## Tabla de Software utilizado
|id | Sofware  | Version  |Tipo   
|---|---|---|---|
| 1 |Visual Studio Code   | 1.71.2  |Freware   |  
| 2 | Arduino IDE  |2   |   2|   Freeware
| 3 | Libreria para sensor proximidad  |  x  | x  |  

## Tabla con el hardware utilizado

| Id  |Componente   | Descripción | Imagen | Cantidad |Costo Total |
|---|---|---|---|---|---|
|   1|  Esp32 | El módulo ESP32 es una solución de Wi-Fi/Bluetooth todo en uno, integrada y certificada que proporciona no solo la radio inalámbrica, sino también un procesador integrado con interfaces para conectarse con varios periféricos  | <img src= "https://user-images.githubusercontent.com/106614070/193470941-0653f560-54d1-4e7d-8ac5-168464d0293c.png"  width="200" height="200" /> | 2  | $300|
|   2| Mini Detector De Movimiento Humano Infrarrojo  | El detector de movimiento pir detecta la radiación infrarroja emitida de forma natural por la persona o animal que pasa por delante de su campo de acción, y de este modo señalan su presencia  |  <img  src="https://user-images.githubusercontent.com/106614070/193471608-649016ca-ef89-45fc-aadd-0b84d0e850b2.png" width="200" height="200" />| 1   | $331 |
|   3| Sensor De Temperatura Y Humedad Dht11 C | El DHT11 es un sensor digital de temperatura y humedad relativa de bajo costo y fácil uso. Integra un sensor capacitivo de humedad y un termistor para medir el aire circundante, y muestra los datos mediante una señal digital en el pin de datos (no posee salida analógica) | <img  src= "https://http2.mlstatic.com/D_NQ_NP_2X_638466-MLM29979046786_042019-F.webp" width="200" height="200" />  |  1 | $67  |
|   4| Esp32 Cam Ov2640 Wifi + Bluetooth Camara 2mp Desarrollo | ESP32 CAM Modulo WiFi con Bluetooth y Camara OV2640 2MP, es una tarjeta de desarrollo que integra una pequeña cámara que puede funcionar de manera independiente.| ![image](https://user-images.githubusercontent.com/106614070/193472256-a56411c9-f759-4ed1-9757-0374791806f2.png)| 1  | $239 |
|   5| 100 Leds Difusos 5mm Rojo, Ambar, Azul, Verde, Blanco  | Un diodo LED es un dispositivo que permite el paso de corriente en un solo sentido y que al ser polarizado emite un haz de luz. Trabaja como un diodo normal pero al recibir corriente eléctrica emite luz. Los LED trabajan aproximadamente con corriente de 2V|![image](https://user-images.githubusercontent.com/106614070/193472526-db15e319-4390-4c06-8c58-0bf9736962b8.png)   | 1| $59 | 
|   6|  Protoboard 830 Puntos Mb-102 | El Protoboard 830 pts MB-102 es una tablilla de pruebas, que cuenta con 830 perforaciones divididas en filas horizontales y columnas verticales para realizar conexiones eléctricas, puedes conectar cualquier elemento electrónico para realizar prototipos, prácticas y simulaciones de circuitos electrónicos  | ![image](https://user-images.githubusercontent.com/106614070/193472640-0e12c7f3-c74e-4f16-9562-9829b3982a2d.png)| 1  |$52 |
|   7| Cables Jumpers Dupont H-h, M-m, H-m 20cm 120 Pzas|  Un cable puente para prototipos (o simplemente puente para prototipos), es un cable con un conector en cada punta (o a veces sin ellos), que se usa normalmente para interconectar entre sí los componentes en una placa de pruebas. | ![image](https://user-images.githubusercontent.com/106614070/193472720-f2f6cb77-627d-4a3d-acd6-4f6ec8571d7f.png) |1   |$103   |
## Epicas del proyecto (Minimo debe de haber una épica por integrante de equipo)
- Quiero poder  buscar a personas en luagres donde no puede llegar facilmente un humano mediante un sensor de movimiento 
- Como usuario quiero poder visualizar por donde va el carrito mediante un camara conectada via bluetooth
- Como usuario quiero poder controlar el carrito desde mi celular
- Como usuario quiero poder estar al tanto de la temperatura ambiental donde se encuentra el carro

## Tabla de historias de usuario
| Id  | Historia de usuario  |Prioridad |Estimación|Como probarlo | Responsable |
|---|---|---|---|---|---|
| 1  |Quiero poder  buscar a personas en luagres donde no puede llegar facilmente un humano mediante un sensor de movimiento| Alta  | 3 semanas | Probando el sensor con la proximidad de un humano | Cesar Alegandro Ordoñez Osorio |
| 2  | Como usuario quiero poder visualizar por donde va el carrito mediante un camara conectada via bluetooth  | Alta |  2 Semanas | Probando con un aplicacion movil |Jose Manuel Sanchez Arredondo   |
|  3 | Como usuario quiero poder controlar el carrito desde mi celular  | Alta  | 2 semanas    | Con las aplicacion movil probando que el Carro responde | Angel Gerardo Velazquez Salazar    |
|  4 | Como usuario quiero poder estar al tanto de la temperatura ambiental donde se encuentra el carro  | Media  | 2 semanas | Probarlo con la interfaz de la aplicación movil | Cruz Estrella Juárez Soto |

## Prototipo en dibujo
![image](https://user-images.githubusercontent.com/106614070/193474216-bae45519-1cfb-41d5-8a74-774bf847905f.png)

