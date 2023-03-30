# IoTSistemaIntegral
IoT Arduino App controlled via Wi-Fi, Bluetooth and API Rest - alarm, lights, doors, storage. 
• Arduino IDE programing in C++ 
• ESP32 microcontroller and components: servomotor, sensors, microSD, buzzers, lights, relays  
• Wi-Fi and Bluetooth libraries - API REST and HTTP implementation 
• System controlled via web applicatio

Imágenes de Maquetado 

![imagen](https://user-images.githubusercontent.com/98788558/228697768-a710c0bc-ee15-453a-8181-9a214341d015.png)
![imagen](https://user-images.githubusercontent.com/98788558/228697788-12fc14e3-11ca-4a84-9624-4eece8223634.png)

Imágenes de Prototipo 3D
Prototipo Control de Acceso - Maestro

![imagen](https://user-images.githubusercontent.com/98788558/228697824-ae08b047-bc7c-4c88-aea1-024ab6eca64a.png)

Prototipo Alarma - Esclavo
 
![imagen](https://user-images.githubusercontent.com/98788558/228697886-a733db03-7f32-4ff3-9456-bb5741dfa7e9.png)

 ![imagen](https://user-images.githubusercontent.com/98788558/228697890-8f06d611-03a5-4b8a-9742-691efa0883a6.png)


Descripción de Funcionamiento 
El sistema cuenta con 2 dispositivos conectados integralmente denominados Maestro y Esclavo, ambos se comunican entre sí con la tecnología Bluetooth, también cuentan con conexión Wi-Fi e integración con API REST para hacer la conexión con la aplicación web y móvil así como la base de datos NoSQL, desde la cual se pueden consultar los “eventos” realizados de algunos componentes como, por ejemplo, detecciones de movimiento por los sensores de la alarma.
      A continuación, se describe la función de cada componente dentro del sistema integral IoT:

●	Alarma: cuenta con dos sensores de movimiento PIR Infrarrojo, los cuales al detectar movimiento activan actuadores como un buzzer y una luz, además de que cada “evento” es registrado tanto en la memoria micro sd como en la base de datos, la cual se puede consultar desde la aplicación.
●	Cámara Livestream: Consta de una cámara que funciona con ip para el monitoreo en tiempo real. Esta refuerza la seguridad en la alarma y en el control de acceso.
●	Puerta principal: se acciona con una chapa eléctrica que puede ser accionada manualmente o con la aplicación.
●	Cochera: consta de un servomotor el cual puede ser encendido manualmente o con la aplicación.
●	Luces: 2 luces interiores y 2 luces exteriores, todas ellas pueden ser activadas manualmente o con la aplicación.
●	Teclado electrónico: Este está conectado al dispositivo maestro el cual está comunicado con los componentes pudiéndolos activar y desactivar sin necesidad de una conexión a internet.
●	Almacenamiento MicroSD: Este registra todos los eventos que suceden con la alarma de movimiento, pues en casos de corte de energía y por ende falta de conexión a internet, este seguirá almacenando los eventos generados.
Finalmente se diseñaron modelos en 3D de los dispositivos Maestro y Esclavo, listos para su impresión, con un diseño de conexión de componentes electrónicos al microcontrolador Esp32, esto para preparar el camino a la comercialización y fabricación en masa, dando oportunidad de implementar el mismo sistema en otros entornos con necesidades similares.
