# ESP8266_ESP32_Proyectos
 
Proyectos desarrollados con ESP8266, ESP32

## ESP8266

1. **[29-08-2022] Lámpara de lectura.**
  - [Previo]
    - [ESP8266 - NodeMCU Web Server asíncrono + SPIFFS](https://randomnerdtutorials.com/esp8266-web-server-spiffs-nodemcu/)
    - [Datos en Form HTML](https://randomnerdtutorials.com/esp32-esp8266-input-data-html-form/)
    - **Materiales:** ESP8266 - NodeMCU v1.0, transistores NPN BJT 2N2222A (o similares), 4 resistencias 10$\Omega$, [4 diodos LED 1W blancos](https://es.aliexpress.com/item/1005001814638969.html?spm=a2g0o.order_list.0.0.21ef194dqajOJ6&gatewayAdapt=glo2esp), dos pulsadores, diodo LED + resistencia 220 ~ 470 $\Omega$
    - **Configuración NodeMCU:** ![Configuración en IDE Arduino](ESP8266/Lámpara de lectura/Luz_lampara_configuracion_ESP8266.png)
  - [29-08-2022] Esquemáticos y código de una lámpara de lectura desarrollada con dos LEDS de 1W de potencia y que puede controlarse a través de una página  web que emite el dispositivo NodeMCU (actuando como servidor asíncrono). Se conecta a través de la red local en una IP determinada. El control puede intercambiarse entre manual y automático, y para el control manual tenemos un potenciómetro de 10 KOhm.
  - [29-08-2022] Idem anterior incluyendo un led piloto para saber cuando el sistema se ha conectado a la red por WiFi y un interruptor que conecta o desconecta el modo manual.
  - [30-08-2022] Idem anterior, pero se sustituye el potenciómetro y el interruptor manual por dos pushbuttons. Los dos pulsadores, al pulsarse, conectan automáticamente con el modo manual. Alternativamente, aumentan la luminosidad de las lámparas (izquierda o derecha) o la disminuyen; el sentido de la variación se indica en la página. Se incluyen varias funciones más desde el control web. Botones para identificar situaciones como apagar las luces (ambas), encenderlas, ponerlas a media luz, intercambiar sus luminosidades, aumentar o dismunir las luces. **Esquemáticos definitivos**.
  - [01-09-2022] Se incluye cuenta de tiempo de encendido y posibilidad de apagado automático, con dos botones a 2 minutos y 20 minutos.
  - [03-09-2022] En la versión 7, se mejora la opción del apagado retardado de las luces, pudiendo escoger entre varios lapsos de tiempo, a través de un select. Una vez escogido un lapso de apagado, no puede cambiarse. La pantalla de la aplicación cambia de color. Incluyo dos imágenes con instrucciones de uso en esta carpeta.
  - [Posibles mejoras] Mejora de los estilos de los botones y del aspecto general de controles. Uso de MQQT, Firebase o Telegram para un control por internet. 

## ESP32
