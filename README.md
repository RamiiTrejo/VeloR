[README.md](https://github.com/user-attachments/files/22640474/README.md)
# Velocista "VeloR" - Robot Seguidor de Línea

## Descripción

El velocista "VeloR" es un robot seguidor de línea diseñado para competir en desafíos de velocidad y precisión. Este repositorio posee el diseño de hardware electrónico relacionados con VeloR. Aquí encontrarás toda la información necesaria para comprender el robot seguidor de línea VeloR.

## Características principales

- **Seguimiento de línea preciso**: Coyote utiliza los sensores ópticos QRE1113 para seguir líneas con precisión y rapidez. Su firmware incorpora algoritmos de control PID que garantizan un seguimiento suave y estable.

- **Velocidad y agilidad**: Utiliza sus motores de RPM2000 con diseño aerodinámico, El Coyote puede alcanzar altas velocidades y realizar maniobras bruscas gracias a sus ruedas anchas que le ayudan a tener mejor agarre en la pista.

- **Firmware personalizable**: El firmware del robot está escrito en lenguaje C++ y se basa en la plataforma de desarrollo ESP32. Este micricontrolador nos ayuda mucho ya que tiene antena wifi/bluetooth integrada y gracias a eso podemos debuguear y calibrar el robot sin necesidad de conectarlo a la computadora.

## Contenido del repositorio

- **/firmware**: En esta carpeta encontrarás el código fuente del firmware utilizado en Coyote. El firmware está escrito en lenguaje C++ y se basa en la plataforma de desarrollo ESP32. Incluye los algoritmos de control, la lógica de seguimiento de línea y la comunicación con los sensores y actuadores del robot ademas de la interfaz bluetooth.

- **/hardware**: Aquí se encuentran los diseños y esquemas del hardware electrónico utilizado en Coyote. Estos archivos incluyen los esquemas de conexión y los diagramas de circuitos.

- **/3D**: En esta carpeta encontrarás los modelos 3D del robot Coyote. Se pueden utilizar para visualizar, modificar y fabricar las partes físicas del robot.



¡Gracias por tu interés en Coyote! 
