# Práctica - Ejecución de Servidor y Cliente con ORB

Este proyecto implementa un servidor y un cliente para la gestión de una biblioteca utilizando ORB (Object Request Broker).

## Requisitos
- Java instalado en el sistema
- ORB configurado correctamente

## Pasos para la Ejecución

Sigue los siguientes pasos para ejecutar el proyecto correctamente:

1. Primero debes ejecutar:
   ```sh
   tnameserv -ORBInitialPort 1050
2. Luego debes ejecutar primero el servidor antes que el cliente si no no funcionara con este comando:
   ```sh
   java ServidorBiblioteca -ORBInitialHost localhost -ORBInitialPort 1050

3. Por ultimo debes ejecutar el cliente con este codigo:
   ```sh
   java ClienteBiblioteca -ORBInitialHost localhost -ORBInitialPort 1050

DIAGEMA DE FLUJO
![Diagrama de flujo](https://github.com/user-attachments/assets/ba6e8e89-2e31-4873-968e-56ff3cfa3ace)
