Local Area Network (LAN)



A LAN connects devices within a relatively small geographic area, such as a single building or campus. It usually belongs to a single owner.



//////////////////////////////////////////////////////////////////////////////////////////////////////////////////



Wide Area Network (WAN)



A WAN, or Wide Area Network, is a type of computer network that spans a large geographic area, such as a city, region, or even multiple countries and are usually managed by one or several Internet Service Providers (ISP). A WAN is typically composed of multiple interconnected LANs.



//////////////////////////////////////////////////////////////////////////////////////////////////////////////////



Metropolitan Area Network (MAN)



Metropolitan Area Network is a network used for interconnecting network devices within a metropolitan area like a city, urban area, or rural area.



//////////////////////////////////////////////////////////////////////////////////////////////////////////////////



Controller Area Network (CAN)



The Controller Area Network (CAN) is commonly used in vehicles to enable communication between various electronic control units (ECUs), such as engine control, transmission, and safety systems



//////////////////////////////////////////////////////////////////////////////////////////////////////////////////



Personal Area Network (PAN) IMPORTANTE PARA SONOS



These networks connect devices that are typically located within the personal space of an individual, such as a room or small area. A PAN is designed for personal use and can be used to connect a variety of devices, including smartphones, tablets, laptops, and wearable devices.



//////////////////////////////////////////////////////////////////////////////////////////////////////////////////



Wireless Local Area Network (WLAN)



A Wireless LAN, or WLAN, is a type of local area network that uses wireless communication technologies such as Wi-Fi to connect devices within a relatively small geographic area.



//////////////////////////////////////////////////////////////////////////////////////////////////////////////////





A SOHO (Small Office/Home Office)



A SOHO (Small Office/Home Office) network typically supports 1 to 10 users and combines both wired and wireless connections. This setup is designed for small businesses or remote professionals.



//////////////////////////////////////////////////////////////////////////////////////////////////////////////////



TOPOLOGIA



Es como un diagrama donde dice como estan conectadas las computadores y servidores en un network de manera física.

Existe la fisica que demuestra donde esta todo y la lógica es el describe the configuration of data through the network.



PHYSICAL TOPOLOGY

Physical topology describes how devices are physically connected to each other and the network, and how data is transmitted between them.



LOGICAL NETWORK TOPOLOGIES



Logical topology refers to the logical or virtual arrangement of devices and how data is transmitted between them. Logical topology describes the configuration of data through the network, and how devices communicate with each other regardless of their physical location or arrangement.



//////////////////////////////////////////////////////////////////////////////////////////////////////////////////



ESTOS SON LAS COSAS QUE SE PUEDEN CAMBIAR EN UN NETWORK



END DEVICES //// (Puede ser un cellphone, playstation, laptop, printer, estos son End devices, por que ahi termina la transmission de datos.

NETWORK DEVICES //// (Tambien se le llama intermediary devices, pueden ser como routers, repetidores de señal, firewall, switches, hay dos tipos de switches).

MEDIA TYPE //// (Puede ser como ethernet cable, fibra optica, esta hecho de vidrio o plastic) Hay dos tipos hay unos que son de cobre o alumunio, WIRELESS, se incluye en estos, es una forma de dispositivos de transmission de datos.



//////////////////////////////////////////////////////////////////////////////////////////////////////////////////



CLIENT VS SERVER



Hay que ver quien es el servidor y quien el cliente.





Client vs Server



Understanding the difference between a client and a server is essential for network troubleshooting. A client requests services, a server provides them—confusing the two leads to wasted time and wrong fixes. Identifying the failing side helps isolate issues faster and apply the correct solution.



Click on the image to see some common examples.



//////////////////////////////////////////////////////////////////////////////////////////////////////////////////



Client vs Server



En este caso hay varios servicios de internet como IP phone, streaming, video calls, website, music streaming.

Web services, con programas basados en la web que se pueden usar por medio de browsers, como las transacciones bancarias.



Web server /// Web server port 80 → serves websites



El email app requests mail from a mail server /// Mail server (Exchange, SMTP server) → handles email



PC Connecting to a file share: PC connecting to a file share → requests files // DHCP server → assigns IP addresses to clients





//////////////////////////////////////////////////////////////////////////////////////////////////////////////////



PEER TO PEER



The simplest P2P network consists of two directly connected computers using either a wired or wireless connection. Both computers are then able to use this simple network to exchange data and services with each other, acting as either a client or a server as necessary



//////////////////////////////////////////////////////////////////////////////////////////////////////////////////



MEDIA TYPE (Medio de transmission)



EMI Electromagnetic Interference (Algunas veces alguien que viva por una torre de alta tension, puede recibir alguna interferencia).



Esto es unwanted noise or disruption, poner el modem cerca del microondas afecta la conexión.



RFI Radio Frequency in the Electromagnetic Spectrum, las ondas que se utilizan para el WI-FI son las mismas ondas de radio, del telefono, de la radio, microndas, estas tienen ondas largas, dependiendo de eso se identifica que es ondas de rario, telefono, microondas. Estas son ondas de radio. Es como tirar dos piedras a un estanque, estas chocan y se pueden anular. Esto puede afectar el wifi o el mismo cable.



//////////////////////////////////////////////////////////////////////////////////////////////////////////////////



EL CABLE DE PLASTICO O FIBRA OPTICA, Este tipo de cable de fibra, utiliza pulsos o luz que no se afecta por el magnetismo.





//////////////////////////////////////////////////////////////////////////////////////////////////////////////////



MEDIA TYPE



Hay dos tipos de cables, el RJ45, hay otro que se llama el RJ11 que es teléfono. normalmente se utiliza el RJ45. Algunas veces esto como tiene elctricidad puede ser afectado por el electromagnetismo.



//////////////////////////////////////////////////////////////////////////////////////////////////////////////////



METAL WIRES



El cable metal wire o coaxial, es el cable del servicio de cable, algunas veces se usa para internet también. 



//////////////////////////////////////////////////////////////////////////////////////////////////////////////////



WIRELESS TRANSMISSION



El código standard es 802.11 (Codigo de indentificación). Es lo mas práctico y la gente lo usa.



Data is sent by modulating specific frequencies of electromagnetic waves.



//////////////////////////////////////////////////////////////////////////////////////////////////////////////////



MAC ADDRESS



Es el numero de cedula que se le asigna a una tarjeta de red, el numero se divide en dos partes, inicia con el "Organizationally Unique indentifier", la segunda parte es el network I"nterface Controller Specific", 



MAC

Media Access Control Address



A8:A1:59:9E:A0:7B



Los primeros tres son el Organizationally Unique Identifier

Los segundos tres son el network Interface Controller specific.



Solo las letras de la A a la F y los numeros del 0 al 9



Se identifica como seis pares de numeros dividios por dos puntos o un punto. 



//////////////////////////////////////////////////////////////////////////////////////////////////////////////////



IPV4



Es un protocolo de internet, de hecho IP quiere decir internet protocol



Formato cuatro numeros del 0 al 255.



123.198.03.221



01111011.11000110.00000011.11011101

8 bits (1 byte).8 bits (1 byte).8 bits (1 byte).8 bits (1 byte).

32 Bits (4 Bytes)





SI EL NUMERO ES MAS DE 255 



//////////////////////////////////////////////////////////////////////////////////////////////////////////////////



ip address / Internet

Mac Address / Red Local



//////////////////////////////////////////////////////////////////////////////////////////////////////////////////



MENSAJES QUE SE PUEDEN ENVIAR A TRAVES DEL INTERNET.



UNICAST



Mensaje que va de una computadora a otra, solo una.

One unique source IP communicates with one unique destination IP.

One source MAC → one destination MAC.



MULTICAST



Es una transferencia de datos que va de una computadora a varias.

One source IP sends traffic to a multicast IP address, which maps to a multicast MAC address and reaches multiple devices.



BROADCAST

Una computadora le envía un mensaje a todas las demas computadoras. Los speakers de Sonos utilizan Multicast.

Multicast needs to be enabled on the network for Sonos devices to function properly.



Algunas veces ellos desactivan los multicast en el router y eso hace que no funciona.



**CAST ES EMITIR**



###### ***SONOS NECESITA MULTICAST PARA FUNCIONAR***





***224.0.0.0 TO 239.255.255.255*** ahi le está enviando un mensaje a los dispositivos conectados desde el 244 al 239.255.255.255, tambien se hace con los mac adrresses.



Broadcast van de un IP a todas las IPs, a todas las que estan conectados a la red, cuando se envia un broadcast se envia como 255.255.255.255 / para las MAC Addresses es FF:FF:FF:FF:FF:FF son los ultimos datos que se pueden usar el numero 255 para IP y F para Mac.



//////////////////////////////////////////////////////////////////////////////////////////////////////////////////



Power Distribution Device0





//////////////////////////////////////////////////////////////////////////////////////////////////////////////////



###### ***MAC ADDRESS LEARNING***



Eso lo que quiere decir es que el switch aprende la combinación de los MAC addresses que le ingresan y por que puerto ingresó.



Para poder ver el mac addresses table



###### ***FLOODING***



Cuando el switch no sabe donde enviar un paquete, se le envía a todos menos del MAC address de donde ingresó

Es cuando el swich no sabe a quien enviar los datos entonces inunda todo o sea se lo manda a todas las interfaces o puerto (Es lo mismo puerto e interface) menos la interface de donde se originan los datos.





###### ***MAC ADDRESS TABLE***



Dentro del switch en la parde CLI, se inicia con enter y luego se pone al lado de swich se pone



**show mac-address-table**



En las compus en la seccion de ARP Table se saca poniendo "arp -a" en el command prompt de las compus.



##### ***LAS COMPUTADORAS INICIAN A CONTAR CON EL NUMERO 0, NO CON EL 1***





//////////////////////////////////////////////////////////////////////////////////////////////////////////////////



RANGOS DE IPS



El ultimo numero es 255. no se puede pasar de este numero.



192.168.1.0 - 192.168.1.255

192.168-2.0 - 





*Estos son las ips mas famosas privadas*



**Network Address And Prefix - RFC 1918 Private Address Range**

10.0.0.0/8                   10.0.0.0 - 10.225.255.255

172.16.0.0/12                172.16.0.0 - 172.31.255.255

192.168.0.0/16               192.168.0.0 - 192.168.255.255



LOS DISPOSITIVOS DE SONOS SOLO SE PUEDEN CONECTAR EN ESTOS RANGOS EN REDES PRIVADAS O LAN, SI ES UNA RED PUBLICA EL SISTEMA DE SONOS NO TRABAJA EN UNA IP PUBLICA.





RED PUBLICA

250.250.250.0 - 250.250.250.255

AHI NO SE PUEDE CONECTAR NADA DE SONOS.



PRACTICA NUMERO BINARIOS



CRC 100



&#x20;



| 128 | 64  | 32  | 16  | 8   | 4   | 2   | 1   |



| --- | --- | --- | --- | --- | --- | --- | --- |



| 0   | 0   | 1   | 0   | 0   | 1   | 0   | 0   |



|     |     |     |     |     |     |     |     |



&#x20;



\* Practice



```



| decimal | binario  |



| ------- | -------- |



| 12      |  1100    |



| 36      |  100100  |



| 231     | 11100111 |



| 56      |  111000  |



|  85     | 01010101 |



|  86     | 00111110 |



|  121    | 01111001 |





Decimal                Binario



172.16.0.20        10101100.10000.0.10100

172.168.46.3       11000000.10101000.00101110.00000011  

186.97.6.36        10111010.01100001.00000110.00100100

169.23.67.2        10101001.00010111.01000011.00000010





| Denary | Binary |



| ------ | ------ |



| 252    | 11111100 |



| 172    | 10101100 |



| 92     | 01011100 |





//////////////////////////////////////////////////////////////////////////////////////////////////////////////////





SUBNET MASK



192.168.100.1



11000000.10101000.01100100.00000001  192.168.100.1

11111111.11111111.11111111.00000000   255.255.255.0



Los primeros dos octetos son el network y el host son los otros dos octetos sobrantes.



Network / Host

142.1   / 122.100

255.255 / 0.0 



192.168.100.56

255.255.255.0



192.168.100.56/24

11111111.11111111.11111111.00000000



El 24 es por que basicamente hay 24 números unos.



/8 > 255.0.0.0

/16 > 255.255.0.0

/24 > 255.255.255.0







172.16.2.1/16

172.16.1.1/16



255.255.0.0 Estas dos estan en la misma red.





172.16.2.1 > IP

255.255.0.0 > Subnet mask

/16 Prefix

172.16.0.0 > Network address, es el primer IP De la red



LOS PRIMEROS DOS OCTETOS SON LA RED, LOS DOS OTROS OCTETOS SON EL HOSTNAME.





Network / Host

172.16.1.2/16

Cual es la primer IP o network address: 172.16.0.0 (Network address) PAPA, no se le puede asignar nada es reservada.



Cual es la última: 172.16.255.255 (Network Broadcast) MAMA, es la ultima direccion IP, no se utiliza, si se le manda algo, esta hace un broadcast y lo envia a todos menos a la señal de origne.



Cual es el subnet mask: 255.255.0.0



Primera utilizable: 172.16.0.1 (Usualmente conocida como Default Gateway)

Ultima utilizable: 172.16.255.254 



en este ip 



192.168.10.1/24 (IP Proveida)



Network       /    Host

192.168.10    /    1 (La que me dieron)

192.168.10    /    0  (Primera o PAPA (***Network address***)

192.168.10    /    1 (Primera utilizable o ***default gateway***

192.168.10    /    255 (Ultima o MAMA) MAMA ***Broadcast address***

19.168.10     /    254 (Ultima utilizable) la que sigue es la mama.





10.0.0.254

255.0.0.0



Network     /      Host

10\.         /      0.0.254    (La que me dieron)

10\.         /      0.0.0      (Primera / Network address PAPA) No utilizable

10\.         /     255.255.255 (Ultima / Broadcas address MAMA) No utilizable

10\.         /     0.0.1       (Primer utilizable / Default Gateway)

10\.         /    255.255.254  (Ultima Utilizable) 

255\.        /      0.0.0      (Subnet mask)





/////////////////////////////////////





8.8.8.8/16

255.255.0.0



(8.8.8.8) Ip que me dieron.

(8.8.0.0) Primera > Network address (PAPA)

(8.8.255.255) Ultima > Broadcast address (MAMA)

(8.8.0.1) Primera utilizable (Usually Default Gateway)

(8.8.255.254) Ultima utilizable

(255.255.0.0) Subnet mask

(8.8.0.0 - 8.8.255.255) Rango total

(8.8.0.1 - 8.8.255.254) Rango utilizable



/////////////////////////////////////



PROTOCOLO DE SEGURIDAD



WPA quiere decir WI-FI PROTECTED ACCESS



WPA2 Es el que utiliza Sonos, se podría usar el WPA3, pero no siempre sirve, no se puede usar el WPA.





/////////////////////////////////////



###### ***PERSONAL AUTHENTICATION VS ENTERPRISE AUTHENTICATION***

&#x09;

Es cuando se conecta de manera personal utilizando el mismo passowrd para todo.



También existe, otra forma de conectarse, donde se pone el usuario y contraseña especial para cada conexión, hay un servidor que se llama ***AUTHENTICATION SERVER***, el cual tiene una lista con los usuarios permitidos.

Esto es mas que todo para organizaciones grandes, con gente que ingresa y sale, se le da usuario y contraseña por separada a cada usuario que se quiere conectar.



LOS DISPOSITIVOS DE SONOS NO SOPORTAN EL ***ENTERPRISE AUTHENTICATION.***



***PRE\*-SHARED PASSWORD (PSK).***



SSID (Network Name, Wi-Fi name).



Es el nombre del wi-fi, eso es un SSID.



Sonos devices required SSID Broadcast to be enabled, and do not support hidden (Non Broadcast) Wi-Fi networks.



ROUTER ES LO MISMO QUE GATEWAY

IOT es el internet de las cosas, el internet de todas las cosas o artefactos o devices.

MD > markdown

# Notes Roberto Arias
## titulo 2
### titulo 3

Lista
- Primero
- Segundo
- Tercero


## Network Notes

<!--! rojo -->
<!--* verde -->
<!--? azul -->
<!-- todo amarillo -->

**Bold**

*Italic*

Para poner el color se selecciona la palabra y se le da Control + forward slash, eso pone los parentesis y el formato correcto, y se le pone el simbolo de exclamación, asterisco o simbolo de pregunta y toma color en la parte izquierda que es como la parte de la programación, no sale en el preview, depende mucho del simbolo.

Control + / es para agregar un comentario
|Numerico|


El switch propaga el broadcast, cuando le llega lo va a retransmitir, exceptuando el puerto y fuente de donde viene el mensaje original.

<!--! rojo El router es el que detiene un mensaje cuando se hace un broadcast, ya que el switch lo propaga y flooding a todos, menos a la fuente original del mensaje o paquete de datos. -->

EL **BROADCAST** DOMAIN ES BASICAMENTE LA RED LAN O PRIVADA
EL ROUTER DETIENE EL FLOODING

EL HOME ROUTER NO TIENE ANTENITAS, EL QUE TIENE ES MAS AVANZADO. 

Para que los speakers de SONOS funcionen en conjunto deben de estar dentro del mismo **BROADCAST DOMAIN**

Los speakers no se conectan con otro tipo de red que no sea regular wi-fi nada de internet celular o satelita.

CMD Command **TraceRT**
Ese comando es para ver cuantos servidores o broadcast domains


Which standard contains the specifications for Wi-Fi 802.11
A. IEEE 802.11
B. IEEE 802.3
C. LTE
D. GSM
E EIA/TIA 268A

La respuesta correcta es la primera, la clave es que diga 802.11, que es lo relacionado al WiFi settings.

*************************************************************

**DHCP**

DHCP discovery, es que el server envía un **flooding**, a todos para ver si hay un DHCP server.

Luego viene el **offer** de un IP address desde el DHCP server.
Lueo viene el **request** y finalmente se le da y se hace un **acknowledgement**.

Son cuatro pasos

- DHCP Discovery (La PC envía un flooding)
- DHCP Offer (Esto lo envía el DHCP server) 
- DHCP Request (La PC confirma que si y hace el request)
- DHCP Acknowledge (El DHCP server hace ack del ip que le dio a la compu)

Es como decir **DORA** la exploradora.

## **Un mensaje con las puras FFFF es un Broadcast**

El DHCP reservation puede dar problemas con Sonos, no debe de haber nada reservado.

## **EL DHCP NO SE PUEDE CONFIGURAR EN UN SWITCH, SOLO EN UN ROUTER.**

Los dispositivos de Sonos solo soportan la conexión Wi-Fi, y algunos pocos también el bluetooth, las otras deben de ir siempre en Wi-Fi

**Antenas de routers**

Omnidirectional Antenna, es la que envia a 360 grados.

Directional Antenna, este tipo de antena directional no es soportado por Sonos, debe de ser apagado en los settings del modem.

## **WIRELESS ACCESS POINT (WAP O WIRELESS ACCESS POINT)**

**Autonomous Access Point** (Funciona de manera autónoma no depende del wireless controller como el otro)

**Controller-Based AP (Lighweight AP)** este depende de otra persona, depende del wireless controller, si hay broncas se configura el wireless controller.

**Wireless Extender EXT**, no se soporta, este repite or boosts wifi signal areas with poor conexion.

**AD HOC MODE**, este es el device to device, es como un **peer to peer.**

**Tethering / Hostpot**, estos no se soportan.

**Infraestructure home of office wi-fi** Para el initial setup solo se usa el regular home Wi-Fi.

**Basic Service Set BSS** Es como la topología.

**Extended Service Set (ESS)** multiple access points, create one large Wi-Fi network. ESS se usa en buildings and campuses to provide one unified Wi-Fi network, normalmente se usa un wireless controller.

## **Standards**

There are two main options to chose from 2.4 Ghz and 5 Ghz, el mas largo tiene mas alcance pero menos señal o una señal débil, para que los dispositivos de sonos deben de estar las dos opciones, 2.4 Ghz y 5 Ghz. Si solo tiene la de 5 no sirve.

Si dos routers cercanos chocan las ondas, better distance but slower speeds.

Hay que usar non-overlapping channels, que son el **1,6 o 11** para reducir la interferencia entre modems.

Para el 5 GHz los commom non-overlapping channels include **36, 40, 44, and 48.**

**Standards**

Wi‑Fi standards determine the frequency, speed, and coverage of a wireless network.  
There are two main options to choose from: **2.4 GHz and 5GHz.**

⚠️ ALERT:  For most Sonos devices to work, the router must support both **2.4 GHz and 5 GHz.  Routers with only 5 GHz are not supported.**

## **Important settings to check for 2.4 GHz and 5 GHz**


- If both bands (5GHz and 2.4GHz) share the same Wi‑Fi name (SSID), rename them and separate the bands. Disable Band Steering and Smart Steering if available.


- Make sure the wireless mode is set to b/g/n (supports multiple Wi‑Fi standards).


- Set the channel width to 20 MHz.


- Not all Sonos devices support Wi‑Fi 5 (802.11ac), esta Wi-Fi 5 es la opción mas nueva, y algunos dispositivos viejos no lo soportan.

**Rangos válidos de IP privadas:**
10.0.0.0 – 10.255.255.255
172.16.0.0 – 172.31.255.255
192.168.0.0 – 192.168.255.255


**Rangos válidos de IP públicas:**
1.0.0.0 – 9.255.255.255
11.0.0.0 – 126.255.255.255
128.0.0.0 – 191.255.255.255
192.0.0.0 – 223.255.255.255


**TCP** 

UDP es unreliable, se enfoca mas en la velocidad, es mas para streaming, musica



















































































