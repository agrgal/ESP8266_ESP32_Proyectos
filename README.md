# ESP8266_ESP32_Proyectos
 
Proyectos desarrollados con ESP8266, ESP32

## ESP8266

1. [29-08-2022] Lámpara de lectura.	
	- [29-08-2022] Esquemáticos y código de una lámpara de lectura desarrollada con dos LEDS de 1W de potencia y que puede controlarse a través de una página  web que emite el dispositivo NodeMCU (actuando como servidor asíncrono). Se conecta a través de la red local en una IP determinada. El control puede intercambiarse entre manual y automático, y para el control manual tenemos un potenciómetro de 10 KOhm. 
	- [29-08-2022] Idem anterior incluyendo un led piloto para saber cuando el sistema se ha conectado a la red por WiFi y un interruptor que conecta o desconecta el modo manual
	- [30-08-2022] Idem anterior, pero se sustituye el potenciómetro y el interruptor manual por dos pushbuttons. Los dos pulsadores, al pulsarse, conectan automáticamente con el modo manual. Alternativamente, aumentan la luminosidad de las lámparas (izquierda o derecha) o la disminuyen; el sentido de la variación se indica en la página. Se incluyen varias funciones más desde el control web. Botones para identificar situaciones como apagar las luces (ambas), encenderlas, ponerlas a media luz, intercambiar sus luminosidades, aumentar o dismunir las luces.
	- [01-09-2022] Se incluye cuenta de tiempo de encendido y posibilidad de apagado automático, con dos botones a 2 minutos y 20 minutos. 

## ESP32
